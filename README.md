# Visual Studio Code Intro
### Learning Objectives
  * installing extensions
  * settings configuration
  * Command Palette
  * cloning a repository
  * loading project folders
  * working with folders/files
  * open file shortcut
  * splitting windows
  * terminal window

### Installing Essential Extensions

One of the great things about VS Code is the huge number of extensions that have been written for it. There are a few that are really useful that we want to load.
* **Live Server** - Web Server to detect changes in HTML pages in browser
* **Live Share** - allow others to join your VS Code session.
* **Prettier** - code formatter
* **Bracket Pair Colorizer**: pairs beginning and ending brackets


To load VS Extensions, click on the **blocks** icon on the left navigation bar.
![](https://raw.githubusercontent.com/hoc-labs/images/main/vs-code-3.png)

 Refer to this [resource](https://github.com/hoc-courses/shared-resources/blob/main/vs-code-intro.md) for the current list of useful extensions. 

### Configuration Settings

You can configure all sorts of settings for VS Code. Most don't need any change from the defaults, but it's good to know where they are.

To bring up the configuration settings, click on the gear icon on the nav bar on the left at the very bottom. Then click the Settings... option and a tab will open in the Code View.

You can type in keyword to search for the setting of interest. For example, type in editor tab and it will show the setting for setting the Tab Size.

![](https://raw.githubusercontent.com/hoc-labs/images/main/vs-code-4.png)

Here are a few that we want to make sure are set correctly.
* Word Wrap: on
* Tab Size: 2

Refer to this [resource](https://github.com/hoc-courses/shared-resources/blob/main/vs-code-intro.md) for the complete list of extensions and configuration settings.

### Themes
You can choose a theme other than the default, either from the built-in selection, or by loading one as an extension.

To look at the built in default, click on the gear icon at the bottom left, and then click **Color Theme**. Or, click on the Extensions icon on the left nav bar and search for theme and you will see some of the most popular. 


### Command Palette
Ctrl-Shft-P brings up the Command Palette, where you can search for commands. It lists the recent commands first.

For example, you can search for **Git: Clone** to start the process of cloning a repo.

Other useful commands are:

**Format Document**
  * Load the sample.html file
  * Do Ctrl-A to select the entire contents of the file
  * Do Ctrl-Shift-P to bring up the Command Palette and search for "Format Document".
  * When you find it select it and hit enter. This should format the html in the document.

**Wrap Element**
A frequent operation when editing HTML documents is to wrap one or more elements with an element.
* select the elements you want to wrap, for example, the `<h2>` and `<img>` elements for Elephant 1.
* Do Ctrl-Shift-P to bring up the Command Palette and search for "Wrap" and select Emmet: Wrap with abbreviation.
* Type in "div" and hit enter.
* This will wrap the two elements with a parent  `<div>` element.

<br/>

### Get Assignment Repo
You should have gone through the steps to create a repo on GitHub for this assignment. See this [resource](https://github.com/hoc-courses/shared-resources/blob/main/github-classroom-intro.md) if you need help with this step.

### Cloning the Repo
We will clone the GitHub repo from within VS Code instead of the CLI. Follow the directions from this [resource](https://github.com/hoc-courses/shared-resources/blob/main/git-cloning-existing-repo.md), using the steps to use VS Code.


### Working with Folders/Files
VS Code works with project folders. After loading your repo in VS Code, the folder will be visible in the Explorer view.

In the Explorer view you can create folders and files either through the File menu or by clicking on the icons that show up when you hover at the top of the project folder. 

![](https://raw.githubusercontent.com/hoc-labs/images/main/vs-code-1.png)


**Create a new file named index.html**
The new file will be opened automatically in the Code View to the right.

* Each file displayed in the Code View has it's own tab and the title of the tab is the name of the file. The title is either in normal or *italics*. 

* If the title is in *italics* that means that the file is not pinned to the Code View and can be replaced by another file when it is opened. If it is in normal text, then it is pinned to the Code View and opening a new file will not close this file.

To change a file from *italic* to normal, double-click on the title tab or double-click on the file in the Explorer View.

**Loading a file with Ctrl-P.**
Ctrl-P brings up a search box where you can type in the name of a file rather than selecting it in the Explorer View. Try using it to search for "owl" to find the owl.jpeg file in the images directory.

**Splitting Windows** 
It's often useful to have more than one file open simultaneously. To do this, just click on the tab for the file and select the **Split** option you want: Up, Down, Left and Right.

### Working with the Terminal Window

VS Code has a built in terminal window, which makes it really convenient to execute git and other commands without leaving VS Code.

To bring up the Terminal Window just click on the Terminal menu, and choose New Terminal.

The Terminal Window will appear at the bottom in its own pane. It will default to the project folder as its current directory.

To create a new Terminal Window you can click the **+** symbol on the upper-right of the Terminal window.

Each terminal window will show up on the right edge and you can switch between the by click on them.

![](https://raw.githubusercontent.com/hoc-labs/images/main/vs-code-2.png)

<br/>

### Previewing HTML Files in the Browser
Right click on the html file in the Explorer you want to view in the browser. Then click **Open with Live Server**. This will open a new tab in the browser and load the HTML file. Try doing it with sample.html.



















  

