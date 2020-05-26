# Introduction To React
***Welcome to Day 1***</br>
Today, I started with getting an introduction about React, and why I should be learning React.<br/>
First of all, let's list down all the major topics that I learned today in a sequential manner:-
- What is React?
- Why React?
- React vs other competitors
- How does React work?
</br>
Let's get through each of these topics one by one.</br>
## What is React?
React is a javascript library. Now, *what actually a javascript library is?*</br>
All of us has visited zillion of webpages. And most of the webpages have several things in common like the image carousel, the various transitions, and others. So, all the web developers doesn't have written codes for these. They must have used a standard code written by someone else and modified it according to their requirement. This collection of code which provides reusibility of some feature is known as a library. And if the code of this library is written in JavaScript then it's called JavaScript Library.</br>
More on JS libraries can be read [here](https://www.khanacademy.org/computing/computer-programming/html-css-js/using-js-libraries-in-your-webpage/a/whats-a-js-library).</br>
React was developed by Facebook in 2011 for their internal use, but in 2013 Facebook open sourced it.</br>
React is a JS library which is used to develop UI components.(More about components in later sections) In other words, React is a front-end library which makes UI development easier, faster and cheaper.

## Why React?
First question that we face while learning React is why do we learn React. And most convient answer is that it is in trend now a days. But why is it in trend? or why so many people are switching to React?</br>
The answer is simple. React is cheap, fast and easy to learn. Let's take a look at these points on by one:-
- **React is cheap** - It means that React utilizes small amount of memory, and it is because each React component or, for now element returns a React Element which is just a simple JavaScript object. This React Element maps the DOM. In other words, it represents the DOM in memory. And it contains all the recently updated components or elements rather then holding the entire application. Doing so React Element creates a virtual DOM which is much more lighter then the actual DOM. Hence, the light weight of React!!</br>
- **React is fast** - When other libraries are updated they reload or updates the entire DOM, whereas in case of React, React Element compares the DOM with the current components and updates only those components which are changed recently, thus avoiding unnecessaay reloading of the DOM.
- **React is easy to learn** - Most of the JS libraries and frameworks require you to remember their unique syntaxs and methods. But the beauty of React is that it renders HTML inside the JS instead of implementing JS within HTML. Let me illustrate this point with the help of the following code snippets-
  - JS within HTML:
  ```
  <ul>
    <li *ngFor="let person of people; let i = index">
      {{ i + 1 }} - {{ person.name }}
    </li>
  </ul>
  ```
  - HTML within JS (React):
  ```
  class Example extends React.Component {
    render() {
      return(
        <h1>HTML within JS</h1>
      );
    }
  }
  ```
</br>
## React vs Other Competitors
React as of writing this has only two vital competitors which are Angular and Vue. Angular is maintained by Google, and is a JS framework which makes it heavy and limited. Similarly, Vue is also a JS framework but it's not considered much of a threat to React as Angular does. The reason I'm going with React is beacuse of the above mentioned characteristics of React, and also the fact the in today's world React is more versatile then both of it's competitors. If you'll learn React then you'll be able to create native applications with few new topics to learn because of React-Native which is the most widely used native building library. Moreover, React has ReactVR for VR development. And there are several other platforms for which you can develop scalable and amazing applications by just learning the basics of React.
## How Does React Work?
React works with components. Let's consider the Youtube home page, you can divide the entire page into small pecies like the navigation bar, the quick links, the recommendation bar, and the video listing part. All of these are called components. Now, components can be as simple as a like button and can be as complex as the video card or the video listings. Each React application consist of a central component which is kind of the mandaotry component, it is called the root component. All the other components are the part of this root component. And these components can again consist of several other components which ultimately takes a form of tree structure.</br>
Each React component is a JavaScript class which consists of a status, and a render method. Status defines the data which has to be displayed inside the component. And the render method defines the display of the component. It is this render method which returns a React Element object which goes forward to create a virtual DOM.</br>
Following is a simple syntax of a React component:
```
class myComponent extends React.Component {
  status: {};
  render() {
    return();
  }
}
```
</br>
*For the curious minds* - The **extends** keyword means that the Class myComponent is inheriting some properties from a class called *Componet* which is a part of the *React* package. It can be understood as that, myComponent is a  young basketball player who is being trained by a coach christened Component. So, the boy myComponent learns the tactics and methods of his coach Component as well as he has own unique methods and tactics. And the coach works for a school called React.
</br>
So, guys that's all I learned today. I hope this might have helped you.
Will meet you tomorrow. Till then **Happy Learning!!**
By-Bye!
