# Preparing Your Environment
Hello Guys!!Welcome back!!</br>
Today, I went on to setup my React development environment which is the core requirement to get started. For the newbies, setting up the development environment means that downloading and installing all the necessary softwares to help us get started with the actual development work.</br>
First of all, I needed a good text editor in which I code write the code, assemble my files, debug the code and other essential stuff. For this I had two choice, whether to use an online text editor or download one to my system. Now, online text editors have their own benefits like you don't have to update them every now and then, you always get the required language's latest and completely stable version available to work on, and also some editors enable file structuring to store your entire project. But I personally prefer offline text editors because I've slow internet and offline editors give you more control and flexibility in your development environment, like I can work with any release of the language I want to, I don't have to worry about losing my files due to internet issues, and others. Here's a [**link**](https://scratch.mit.edu/discuss/topic/134206/?page=1#post-1691632) to a open discussion about **online vs offline text editors**.</br>
Now, there are several options for offline code editors like VS Code, Sublime Text, Atom, Eclipse, Visual Studio, Vim, and many others. All of these editors have pretty much same properties or functionalities, but they generally differ in UI. And it's completely upto you to choose any of the available offline code editors depending upon your requirement. For me VS Code is awesome, though I have done my most of web development work using Sublime Text, but I prefer using VS Code when I've to manage the file structure of the project as well as need a terminal to execute few commands related to it. Atom is also one of my choices but I somehow found it difficult to work with Atom, hence VS Code.</br>
With the editor choosen, I now need to install React into my system. But in order to do that I've to install Nodejs into my system. I'll be using Nodejs' NPM (Node Package Manager) to download and install the React library into my system.</br>
To install NodeJs, visit to this [**link**](https://nodejs.org/en/download/).
</br>
Once you've downloaded NodeJs, then install it into your system using the installer you just now donwloaded. Then, to check if your installation was successfull or not, open the command prompt on Windows or the terminal on Mac. Then type the following command:</br>
```
npm -v
```
</br>
It'll return the version of the NodeJs installed on your system.
</br>*For curious minds*-It's the -v option which tells the npm command to only return the version of npm installed in the system.
</br>
Now you've successfully installed NodeJs in your system. It's time to install React. Open the command prompt in Windows or the terminal in Mac once again. To install React type the following command in it:</br>
*For Windows*</br>
```
npm i -g create-react-app
````
</br>
*For Mac*
```
sudo npm i -g create-react-app
```
</br>
*For curious minds-* In above commands *i* is shorthand for install which commands the npm package to install something specified in the command ahead. To be honest I couldn't find the meaning of the *-g* flag. If you know it please tell me. And finally the *create-react-app* means that npm package should install React into my system.
</br>
With this done we've completed the installation of React into our system. And also the React development environment is done.</br>
That's all for today. I hope this helped you.</br>
Will se you tomorrow.**Happy Learning**</br>
By-Bye!!
