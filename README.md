# A03

<h2>Directions on Using Webstorm</h2>

<h3>Open, check out, or create a project</h3>

<h4>To open a project</h4>

<h5>On the Welcome Screen, click Open and then select the folder with your application in the dialog that opens</h5>

<h4>To check out a project from a version control system</h4>

<h5>1. Click Get from VCS on the Welcome screen. Alternatively, select File | Project from Version Control or <Your_VCS> | Get from Version Control from the main menu.

<Your_VCS> stands for the Version Control System with which your currently opened project is associated.</h5>

<h5>2. In the dialog that opens, select your version control system from the list and specify the repository to check out the application sources from. See Check out a project (clone) for details.</h5>

<h4>To create an empty WebStorm project</h4>
 
<h5>1. Click Create New Project on the Welcome screen or select File | New | Project from the main menu. The Create New Project Dialog opens.</h5>

<h5>2. In the left-hand pane, choose Empty Project. In the right-hand pane, specify the application folder and click Create.</h5>
  
<h5>You can also generate a project from a template, see Generating framework-specific projects for details.</h5>

<h4>To create a new file in a project</h4>

<h5>In the Project tool window, select the folder where you want to create a new file and press Alt+Insert.</h5>

<h5>Alternatively, choose New from the context menu of the selection and then choose the file type from the list.</h5>

<h3>Get familiar with the WebStorm user interface</h3>
  
<h4>The WebStorm window consists of the Editor where you read, create, and modify your code, menus and toolbars, a navigation bar, a status bar, and a number of WebStorm tool windows. These secondary windows are attached to the bottom and to the sides of your workspace and let you debug your code, run tests, interact with your version control system, and so on.</h4>
  
<h4>You can organize the layout of WebStorm as you like. For example, if you want to focus on writing your code, try the Distraction Free Mode. It removes all toolbars, tool windows, and editor tabs, so you have more free space. To switch to this mode, choose View | Appearance | Enter Distraction Free Mode from the main menu.</h4>
  
<h4>An alternative to the Distraction Free Mode may be hiding all tool windows by pressing Ctrl+Shift+F12. You can restore the layout to its default by pressing this shortcut once again.</h4>
  
<h4>When the tool windows are hidden, you can access any of them via a shortcut - the input focus moves to the tool window and you can use any keyboard command in its context. To get back to the editor, just press Escape. When a tool window is visible, pressing its shortcut just brings the focus to it.</h4>

<h3>Complete your code</h3>

<h4>WebStorm automatically completes keywords, symbols from standard language API's and from the project dependencies. Press Ctrl+Space to get the code completion options for the current context, the icon next to each suggested member indicates its type</h4>

<h4>To have more variants shown, press Ctrl+Space once again.</h4>
 
<h4>By default, completion suggestions in JavaScript and TypeScript files are sorted by their relevance based on machine-learning algorithms. To turn off this sorting, open the Settings/Preferences dialog Ctrl+Alt+S, go to Editor | General | Code Completion, and clear the Sort completion suggestions based on machine learning checkbox. Learn more from Sort suggestions based on Machine Learning.</h4>
  
<h3>Inspect and fix your code on the fly</h3>
  
<h4>WebStorm monitors your code and tries to keep it accurate and clean. It detects potential errors and problems and suggests quick-fixes for them. Every time WebStorm finds unused code, an endless loop, a missing import statement for a symbol, and many other things that probably require your attention, you’ll see a highlight and a light bulb. Click this bulb or press Alt+Enter to apply a fix.</h4>

<h4>You forgot an import statement? WebStorm marks the symbol as unresolved and shows a tooltip with the suggested quick-fix.</h4>

<h4>Alternatively, press Alt+Enter and click Insert 'import "Customer"'.</h4>

<h4>For ES6 and TypeScript symbols, WebStorm can add missing import statements on code completion.</h4>

<h4>To see the full list of available inspections, in the Settings dialog Ctrl+Alt+S, click Inspections under Editor. You can disable some of them, or enable others, plus you can adjust the severity of each inspection. You decide whether it should be considered an error or just a warning.</h4>

<h3>Refactor your code</h3>
  
<h4>Refactoring means updating the source code without changing the behaviour of the application. Refactoring helps you keep your code solid, dry, and easy to maintain. WebStorm ensures that after refactoring the code works in the same way as before it, because changes are made smartly to the whole project. For example, if you rename a class, WebStorm automatically renames all its usages and import statements.</h4>

<h5>1. In the editor or in the Project tool window, select the expression or symbol to refactor, and press Ctrl+Alt+Shift+T</h5>

<h5>2. From the Refactor This list, choose the required refactoring.</h5>

<h3>Run and debug your application</h3>

<h4>In WebStorm, the entry point to running or debugging an application is a run/debug configuration. WebStorm comes with a number of predefined run/debug configuration templates for different types of applications and files. The information you need to provide in a configuration depends on its type, it can be a file to run or a test. Some configurations can attach to already running applications, in this case you need to specify the URL and port to attach to.</h4>

<h5>To run your application</h5>

<h6>Create a run configuration of the type that fits your app and click Run.</h6>

<h6>In some cases, you can run your app or file without creating a run configuration, WebStorm can do it for you. For example, to run any file with Node, just choose Run <file_name> on its context menu or press Ctrl+Shift+F10. This also works for an HTML file, WebStorm just opens it in the browser.</h6>

<h6>If your project has an npm script that starts your application in the development mode or builds it, just open your project package.json in the editor, click Run in the gutter next to the start task, and choose Run 'start' from the list.</h6>

<h5>To start debugging</h5>
  
<h6>With WebStorm, you can debug various kinds of applications - client-side applications, Node.js applications, tests, and so on. Here's how you can debug client-side JavaScript running on an external development web server, for example, powered by Node.js.</h6>

<h6>1. Set the breakpoints in the JavaScript code, as required.</h6>
  
<h6>2. Run the application in the development mode, possibly with npm start as described above, and copy the URL address at which the application is running in the browser.</h6>

<h6>3. Select Run | Edit Configuration from the main menu, click the Add button on the toolbar and select JavaScript Debug from the list.</h6>

<h6>In the Run/Debug Configuration: JavaScript Debug dialog that opens, specify the URL address at which the application is running. This URL can be copied from the address bar of your browser as described in Step 2 above.</h6>

<h6>4.Select the newly created configuration from the Select run/debug configuration list on the toolbar and click the Debug button.</h6>

<h6>Alternatively, hold Ctrl+Shift and click the application URL link in the Run tool window.</h6>

<h6>The URL address specified in the run configuration opens in the browser and the Debug tool window appears.</h6>

<h6>5. In the Debug tool window, proceed as usual: step through the program, stop and resume the program execution, examine it when suspended, view actual HTML DOM, run JavaScript code snippets in the Console, and so on.</h6>

<h6>WebStorm has a built-in web server that can be used to preview and debug your application. This server is always running and does not require any manual configuration. All the project files are served on the built-in server with the root URL http://localhost:<built-in server port>/<project root>, with respect to the project structure. See Debugging an application running on the built-in server for details.</h6>
  
  <sub><a href=https://www.jetbrains.com/idea>IntelliJ IDEA</a></sub>
  <sub><a href=https://www.jetbrains.com/pycharm>PyCharm</a></sub>
  <sub><a href=https://www.jetbrains.com/webstorm>WebStorm</a></sub>
  <sub><a href=https://www.jetbrains.com/phpstorm>PHPStorm</a></sub>
  <sub><a href=https://www.jetbrains.com/rider>Rider</a></sub>
  <sub><a href=https://www.jetbrains.com/clion>CLion</a></sub>
  <sub><a href=https://www.jetbrains.com/datagrip>DataGrip</a></sub>
  <sub><a href=https://www.jetbrains.com/ruby>RubyMine</a></sub>
  <sub><a href=https://www.jetbrains.com/go>GoLand</a></sub>

<h2>Glossary</h2>

<h4><strong>Branch</strong></h4>

  <h5>A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without     disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.</h4>

<h4><strong>Clone</strong></h4>

  <h5>A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can     edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote         version so that you can push your local changes to the remote to keep them synced when you're online.</h5>

<h4><strong>Commit</strong></h4>

  <h5>A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or         "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief             description of what changes were made.</h5>

<h4><strong>Fetch</strong></h4>

  <h5>When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to       review changes before committing them to your local branch.</h5>

<h4><strong>GIT</strong></h4>

  <h5>Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the 
  social and user interface, is built on top of.</h5>

<h4><strong>Github</strong></h4>

  <h5>GitHub is a web-based interface that uses Git, the open source version control software that lets multiple people make separate changes to web pages at the same time.</h5>

<h4><strong>Merge</strong></h4>

  <h5>Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be       thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or   can always be done via the command line.</h5>

<h4><strong>Merge Conflict</strong></h4>

  <h5>A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a     file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.</h5>

<h4><strong>Push</strong></h4>

  <h5>To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others   may access them.</h5>

<h4><strong>Pull</strong></h4>

  <h5>Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those   changes to your local copy so that it's up to date.</h5>

<h4><strong>Remote</strong></h4>

  <h5>This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be     synced.</h5>

<h4><strong>Repository</strong></h4>

  <h5>A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including                 documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.</h5>

<sub>Sources</sub>
<sub><a href=https://docs.github.com/en/get-started/quickstart/github-glossary>Github.com "Github Glossary"</a></sub>
<sub><a href=https://digital.gov/resources/an-introduction-github>Digital.gov "An Introduction to Github"></a></sub>
