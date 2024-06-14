[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15275217&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Prerequisites:
Windows 11 Operating System: Ensure your computer is running Windows 11.
Internet Connection: You will need an internet connection to download the installer.
Administrative Privileges: Make sure you have administrative rights to install software on your computer.
Steps to Download and Install Visual Studio Code:
Open Web Browser:
Launch your preferred web browser (e.g., Microsoft Edge, Google Chrome).
Navigate to Visual Studio Code Website:
Go to the official Visual Studio Code website: https://code.visualstudio.com/.

Download the Installer:
On the homepage, you will see a large "Download" button.
The website automatically detects your operating system. Click the button that says "Download for Windows".
Alternatively, if it doesn't auto-detect, you can manually select Windows from the drop-down menu.

Run the Installer:
Once the installer is downloaded (the file name will be something like VSCodeSetup-x64-<version>.exe), locate the file in your downloads folder.
Double-click the installer file to start the installation process.

Install Visual Studio Code:
The setup wizard will open. Follow the prompts to install VS Code:
Step 1: Accept the license agreement and click "Next".
Step 2: Choose the installation location (the default location is usually fine) and click "Next".
Step 3: Select additional tasks (optional). These might include creating a desktop icon, adding "Open with Code" action to Windows Explorer file context menu, etc. Choose the ones you prefer and click "Next".
Step 4: Review the setup and click "Install".

Finish Installation:
Once the installation is complete, you will see a screen that says "Setup has finished installing Visual Studio Code on your computer".
Ensure the option "Launch Visual Studio Code" is checked if you want to start it immediately, and click "Finish".

First Launch and Configuration:
If you didn't check the "Launch Visual Studio Code" box during installation, you can start VS Code by searching for it in the Start menu.
On the first launch, you might be presented with a welcome screen that includes options for setting up your development environment, installing extensions, etc.

Optional: Install Recommended Extensions
Extensions: Visual Studio Code's functionality can be extended with various extensions. To install extensions, click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X. Search for and install any extensions you need (e.g., Python, C++, JavaScript, etc.).

Updating Visual Studio Code
Automatic Updates: VS Code typically updates automatically. If you need to check for updates manually, go to Help > Check for Updates

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   General Settings
User Interface Customization:
Theme: Choose a theme that is comfortable for your eyes. Popular themes include:
Dark themes: "One Dark Pro," "Dracula Official"
Light themes: "Light+ (default light)"
File Icon Theme: Customize the file icon theme for better file type recognition. "Material Icon Theme" is a popular choice.

Editor Settings:
Font Size and Family: Adjust the font size and choose a monospaced font like "Fira Code" or "Source Code Pro."
Line Numbers: Ensure line numbers are visible ("editor.lineNumbers": "on").
Word Wrap: Enable word wrap for easier reading of long lines ("editor.wordWrap": "on").
Auto Save: Set auto save interval or on focus change ("files.autoSave": "afterDelay" or "files.autoSave": "onFocusChange").

Workspace Settings:
Default Formatter: Set a default code formatter for your language (e.g., Prettier for JavaScript).
Indentation: Set your preferred tab size and whether to use tabs or spaces ("editor.tabSize": 2, "editor.insertSpaces": true).
Important Extensions

Language-Specific Extensions:
Python: "Python" extension by Microsoft for linting, debugging, and IntelliSense.
JavaScript/TypeScript: "ESLint" and "Prettier" for linting and formatting, "npm Intellisense" for package autocompletion.
C++: "C/C++" by Microsoft for IntelliSense, debugging, and code browsing.

Version Control:
GitLens: Enhances the built-in Git capabilities of VS Code with more features like blame annotations, commit search, etc.

Code Quality and Formatting:
ESLint: For JavaScript/TypeScript linting.
Prettier - Code formatter: For consistent code formatting.
EditorConfig: Helps maintain consistent coding styles between different editors and IDEs.

Productivity Tools:
Live Server: Launch a development local server with live reload feature for static & dynamic pages.
Path Intellisense: Autocompletes filenames.
Bracket Pair Colorizer 2: Colorizes matching brackets to make code more readable.

Debugging:
Debugger for Chrome: Debug JavaScript code in the Chrome browser directly from VS Code.

Remote Development:
Remote - SSH: Connect to any remote machine using SSH.
Remote - WSL: Develop in Windows Subsystem for Linux.
Remote - Containers: Develop inside Docker containers.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   Visual Studio Code (VS Code) is a popular code editor developed by Microsoft, known for its versatility and extensive feature set. The main components of the VS Code user interface include the Activity Bar, Side Bar, Editor Group, and Status Bar. Here's a detailed look at each component:

1. Activity Bar
The Activity Bar is located on the far left side of the VS Code interface. It contains a series of icons that allow you to switch between different views and functionalities within the editor. The default icons typically include:

Explorer: Provides a file explorer for your project.
Search: Allows you to search across files in your project.
Source Control: Integrates with version control systems like Git.
Run and Debug: Manages debugging configurations and controls.
Extensions: Manages extensions that add functionality to VS Code.
The Activity Bar's purpose is to provide quick access to these essential tools and to allow you to easily navigate between different functionalities within VS Code.

2. Side Bar
The Side Bar is located immediately to the right of the Activity Bar. Its content changes based on the currently active view selected from the Activity Bar. For example:

Explorer View: Displays the file and folder structure of your project, allowing you to open and manage files.
Search View: Displays search results for queries run through the search functionality.
Source Control View: Shows version control information, including changes, branches, and repositories.
Run and Debug View: Provides debugging tools and configuration options.
Extensions View: Lists installed extensions and allows you to search for and install new ones.
The Side Bar's purpose is to display detailed information and options related to the active view, helping you manage your project and tools effectively.

3. Editor Group
The Editor Group is the main area where you write and edit your code. This section is highly flexible and supports multiple editors open simultaneously in a grid layout. Key features include:

Tabs: Each open file is represented by a tab at the top of the editor group, allowing easy switching between files.
Split Editors: You can split the editor into multiple groups (vertical or horizontal), enabling side-by-side code editing.
Minimap: A small overview of your code, providing quick navigation within large files.
Syntax Highlighting and IntelliSense: Features that enhance the coding experience with color-coded syntax and code completion suggestions.
The purpose of the Editor Group is to provide a robust and flexible workspace for writing and managing code files, facilitating efficient coding practices.

4. Status Bar
The Status Bar is located at the bottom of the VS Code interface. It provides various pieces of information and controls related to your current workspace and active file. Common elements include:

Line and Column Number: Indicates the current cursor position within the file.
Encoding and Language Mode: Displays the file's encoding and language mode, with options to change them.
Git Branch and Status: Shows the current Git branch and status of the repository.
Problems and Notifications: Displays icons for errors, warnings, and other notifications related to your code or extensions.
Quick Access Controls: Provides shortcuts for common actions like changing language mode, formatting code, and more.
The purpose of the Status Bar is to offer real-time feedback and quick access to common actions and information, enhancing overall productivity and awareness while working in VS Code.

These components together create an efficient and user-friendly environment for coding, allowing developers to manage their projects and workflows seamlessly within VS Code.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   The Command Palette in Visual Studio Code (VS Code) is a powerful tool that allows users to access and execute a wide range of commands from a single interface. It provides a quick and efficient way to perform various tasks without navigating through menus or remembering complex keyboard shortcuts.

Accessing the Command Palette
To open the Command Palette in VS Code, you can use one of the following methods:
Keyboard Shortcut: Press Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Menu: Click on the View menu and select Command Palette.
Common Tasks Performed Using the Command Palette
Here are some examples of tasks you can perform using the Command Palette:

Opening Files:
Command: > Open File
Action: Allows you to quickly search for and open files within your workspace.
Running Extensions:

Command: > Extensions: Install Extensions
Action: Opens the Extensions view, where you can search for and install new extensions.
Changing Settings:

Command: > Preferences: Open Settings
Action: Opens the Settings editor, where you can view and modify your user or workspace settings.

Git Commands:
Command: > Git: Commit
Action: Opens the Git commit interface to commit changes in your repository.

Running Tasks:
Command: > Run Task
Action: Lists available tasks (like build or test tasks) defined in your project, allowing you to run them directly.

Searching for Commands:
Command: Typing any keyword (e.g., "format", "debug", "terminal") brings up related commands.
Action: Helps you quickly find and execute commands related to the keyword.

Opening Terminals:
Command: > Terminal: Create New Integrated Terminal
Action: Opens a new integrated terminal within VS Code.

Navigating to Symbol Definitions:
Command: > Go to Symbol in Workspace
Action: Allows you to search for and navigate to symbols (functions, variables, classes) across your entire workspace.

Toggling Panels:
Command: > View: Toggle Terminal
Action: Shows or hides the integrated terminal.

Changing Color Theme:
Command: > Preferences: Color Theme
Action: Allows you to quickly switch between different color themes for the editor.
Example Usage
Imagine you want to format the code in the currently open file:
Open the Command Palette using Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac).
Type "format" and select the command Format Document.
VS Code will automatically format your code based on the default formatter settings.
The Command Palette is a versatile and integral part of the VS Code experience, enabling users to streamline their workflow and perform tasks efficiently.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   Extensions in VS Code play a crucial role in extending its functionality beyond its core features, catering to specific programming languages, frameworks, and workflows. Here’s an overview of their role and how users can find, install, and manage them:

Role of Extensions in VS Code
Enhancing Functionality: Extensions add new features, language support, debugging capabilities, themes, and more to VS Code.

Customization: Users can tailor their development environment by choosing extensions that fit their needs, making VS Code highly versatile.

Support for Various Technologies: Extensions cover a wide range of technologies such as JavaScript, Python, HTML/CSS, Git integration, Docker, and more.

Finding and Installing Extensions
VS Code Marketplace: This is the primary source for extensions. Users can access it directly from within VS Code or via the VS Code Marketplace website.

Search and Filters: Users can search for extensions by name or functionality (e.g., "Python", "Git"). Filters help narrow down results based on popularity, rating, and compatibility.

Installation: Installing an extension is straightforward:
Go to the Extensions view in VS Code (Ctrl+Shift+X).
Search for the desired extension.
Click "Install" next to the extension name.
Managing Extensions
Enabling/Disabling: Users can enable or disable extensions to control which ones are active at any given time.

Updating: VS Code notifies users when updates are available for installed extensions, and updates can be applied with a click.

Settings: Extensions often provide customizable settings accessible via VS Code's settings (Ctrl+,), allowing users to tweak behavior and appearance.

Essential Extensions for Web Development
ESLint: Provides JavaScript linting (code quality analysis) to ensure consistent coding styles.

Prettier - Code formatter: Automatically formats code to maintain consistent style across the project.

Live Server: Launches a local development server with live reload capability, helpful for web development.

Debugger for Chrome: Allows debugging JavaScript code in Google Chrome directly from VS Code.

HTML CSS Support: Adds CSS support for HTML documents, providing autocomplete and linting.

Auto Rename Tag: Automatically renames paired HTML/XML tags when one is renamed.

Path Intellisense: Autocompletes filenames and paths in your code.

GitLens: Enhances Git integration by providing detailed insights into code history, inline blame annotations, and more.

Example Workflow
For a typical web development project, you might install extensions like ESLint, Prettier, Live Server, Debugger for Chrome, and HTML CSS Support. These extensions together enhance productivity by ensuring code quality, automating formatting, providing live preview, enabling debugging, and improving CSS/HTML coding experience.

By leveraging extensions, VS Code can be tailored to suit different programming needs, making it a powerful and flexible IDE for developers across various domains.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   Opening and using the integrated terminal in Visual Studio Code (VS Code) is straightforward and offers several advantages over using an external terminal.

Opening the Integrated Terminal:
Open VS Code: Start by opening Visual Studio Code on your computer.

Access Terminal: There are several ways to open the integrated terminal:
Using the Menu: Go to View -> Terminal.
Using Keyboard Shortcut: Press Ctrl+` (backtick key, usually located above the Tab key on most keyboards).
Switch Terminal Types (Optional): By default, VS Code opens the terminal using the system's default shell (like Command Prompt on Windows, Bash on Linux/macOS). You can switch the terminal shell by clicking on the dropdown arrow in the terminal panel and selecting the desired shell (like PowerShell, Git Bash, etc.).

Using the Integrated Terminal:
Once the integrated terminal is open, you can use it just like any other terminal:
Run Commands: Type commands directly into the terminal and press Enter to execute them.
Navigate Directories: Use cd command to navigate through directories.
Manage Files: Perform file operations (create, delete, move files and directories).
Run Scripts: Execute scripts, build projects, and run tests.
View Output: See the output of commands, scripts, and build processes directly within VS Code.

Advantages of Using the Integrated Terminal:
Seamless Integration: The terminal is integrated into the same window as your code editor, reducing the need to switch between applications.
Contextual Awareness: The integrated terminal understands the current workspace and project context, making it easier to run commands relative to your project files.
Customization: You can customize the integrated terminal with specific shell configurations and preferences directly from VS Code settings.
Efficiency: Avoids the overhead of switching between windows or managing multiple applications for coding and terminal tasks.
Output Interactivity: Terminal outputs are clickable in VS Code, allowing you to quickly jump to errors, warnings, or specific lines within your code.
Debugging: Integrated debugging capabilities can interact with the terminal, providing a more seamless debugging experience.

In summary, using the integrated terminal in VS Code enhances productivity by providing a unified environment for coding and terminal-based tasks, reducing context-switching overhead and improving workflow efficiency.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   In Visual Studio Code (VS Code), managing files and folders and navigating between them efficiently is straightforward and can greatly enhance your productivity. Here’s a detailed guide on how to create, open, and manage files and folders, and navigate between them efficiently:

Creating and Opening Files and Folders
Creating a New File:
To create a new file, you can either:
Use the Explorer view Ctrl+Shift+E and right-click on the parent directory where you want to create the file. Then select New File and enter the file name.
Use the Command Palette Ctrl+Shift+P, type "New File", and select File: New File. Enter the file name and press Enter.

Creating a New Folder:
To create a new folder, follow similar steps:
In the Explorer view, right-click on the parent directory where you want to create the folder, then select New Folder and enter the folder name.
Use the Command Palette, type "New Folder", and select File: New Folder. Enter the folder name and press Enter.

Opening Files and Folders:
You can open files and folders in VS Code in several ways:
Using the Explorer view: Double-click on a file or folder to open it.
Using the Command Palette: Ctrl+P to open the file picker, where you can type the name of the file to open.
Using the File Menu: File > Open... Ctrl+O on Windows to open a file picker dialog where you can select files or folders.

Managing Files and Folders
Renaming Files and Folders:
In the Explorer view, right-click on a file or folder and select Rename (or press F2). Enter the new name and press Enter.

Deleting Files and Folders:
In the Explorer view, right-click on a file or folder and select Delete. Alternatively, you can press Delete or Shift+Delete (permanent delete) after selecting the file or folder.

Moving Files and Folders:
To move files or folders within the workspace:
Drag them to the desired location in the Explorer view.
Cut (Ctrl+X) and paste (Ctrl+V) them to the new location.
Navigating Between Files and Directories Efficiently

Using the Explorer View:
The Explorer view Ctrl+Shift+E displays a tree view of your files and directories. You can expand and collapse directories to navigate through your project.

Using Tabs:
When you open a file, it appears in a tab at the top of the editor. You can switch between open files by clicking on their tabs.

Using the Go to File Feature:
Ctrl+P opens the Go to File command. Type the name of the file you want to open, and VS Code will suggest matches based on the files in your workspace.

Using the Command Palette:
Ctrl+Shift+P opens the Command Palette. Here, you can type various commands to navigate, open files, switch between tabs, etc.

Keyboard Shortcuts for Navigation:
Use Ctrl+Tab to cycle through open files.
Use Ctrl+PageUp and Ctrl+PageDown to navigate through tabs.

Working with Multiple Windows:
You can open multiple instances of VS Code or use the Split Editor feature (Ctrl+\) to view and edit multiple files side by side.
By leveraging these features and shortcuts, you can efficiently manage files and folders, and navigate through your project's directory structure with ease in Visual Studio Code.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Accessing Settings
Open the Settings Interface:
Click on the gear icon in the lower left corner of the VS Code window and select "Settings".
Alternatively, use the shortcut Ctrl+.

Settings UI:
The settings interface will open in the main editor area. You can search for specific settings using the search bar at the top.

Changing the Theme
Open Command Palette:
Use the shortcut Ctrl+Shift+P to open the Command Palette.
Type Preferences: Color Theme and select it from the list.

Select a Theme:
A list of available themes will appear. You can preview and select a theme by clicking on it.

Changing the Font Size
Open Settings:
Go to the settings interface as described above.

Search for Font Size:
In the search bar, type Font Size.

Change the Font Size:
You will see an option called Editor: Font Size. Adjust the value to your desired font size (e.g., change it from 14 to 16).

Customizing Keybindings
Open Keyboard Shortcuts:
Click on the gear icon in the lower left corner and select "Keyboard Shortcuts".
Alternatively, use the shortcut Ctrl+K Ctrl+S (Cmd+K Cmd+S on macOS).

Modify Keybindings:
You can search for a specific command using the search bar.
To change a keybinding, click on the pencil icon next to the command you want to change, then press the new key combination you wish to assign.

Example Customizations
Example 1: Changing the Theme
Press Ctrl+Shift+P.
Type Preferences: Color Theme.
Select a theme, such as "Dark+ (default dark)".

Example 2: Changing the Font Size
Press Ctrl+, (Cmd+, on macOS) to open settings.
Type Font Size in the search bar.
Change Editor: Font Size from 14 to 16.

Example 3: Changing Keybindings
Press Ctrl+K Ctrl+S.
Search for the command you want to rebind, such as Copy.
Click the pencil icon next to Copy.
Press the new key combination, such as Ctrl+Shift+C.
By following these steps, users can effectively customize their VS Code environment to suit their preferences

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Setting up and debugging a simple program in Visual Studio Code (VS Code) involves several steps. Here’s a comprehensive guide:

Setting Up a Simple Program for Debugging in VS Code
Install VS Code:
Download and install VS Code from the official website.

Install Necessary Extensions:
Depending on the programming language, install the relevant extensions. For example, if you are working with Python, you need the Python extension by Microsoft. Go to the Extensions view (Ctrl+Shift+X) and search for the required extension.

Open or Create a Project:
Open a folder containing your project or create a new file within a folder.

Write Your Code:
Create a new file with the appropriate file extension (e.g., example.py for Python, example.js for JavaScript) and write your code.

Set Up the Debug Configuration:
Click on the Run and Debug icon on the sidebar (or use Ctrl+Shift+D).
Click on the "create a launch.json file" link to create a debug configuration file.
Select the appropriate environment (e.g., Python, Node.js) and a launch.json file will be created in the .vscode folder.

Configure the Launch.json File:
Modify the launch.json file if needed. For example, for a Python file, it might look like this:
{
  "version": "3.2.0",
  "configurations": [
    {
      "name": "Python: Current File",
      "type": "python",
      "request": "launch",
      "program": "${file}",
      "console": "integratedTerminal"
    }
  ]
}
Starting the Debugging Process
Set Breakpoints:
Click in the gutter to the left of the line numbers where you want to set breakpoints. A red dot will appear indicating a breakpoint.

Start Debugging:
Click on the green play button in the Run and Debug view or press F5 to start debugging. Your program will start, and execution will pause at any breakpoints you’ve set.

Inspect Variables and State:
Use the Debug sidebar to inspect variables, watch expressions, and view the call stack.
Hover over variables in the code to see their current values.

Key Debugging Features in VS Code
Breakpoints:
Set and remove breakpoints to pause program execution at specific lines of code.

Watch Variables:
Add expressions to the Watch panel to monitor variable values over time.

Call Stack:
View the call stack to see the sequence of function calls that led to the current point in the program.

Variable Inspection:
Hover over variables in your code to see their current values.

Step Controls:
Use the toolbar to step over (F10), step into (F11), step out (Shift+F11), or continue running (F5).

Integrated Terminal:
Run commands and see output directly within the integrated terminal without leaving the editor.

Conditional Breakpoints:
Set conditions for breakpoints to pause execution only when certain conditions are met (right-click on a breakpoint and select "Edit Breakpoint").

Log Points:
Insert log points to print messages to the console without modifying the code (right-click on a breakpoint and select "Log Message").
By following these steps and utilizing the key debugging features, you can effectively debug your programs in Visual Studio Code.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

Install Git
First, ensure that Git is installed on your system. You can download and install Git from git-scm.com.

Install VS Code
Make sure you have Visual Studio Code installed on your system. You can download it from code.visualstudio.com.

Configure Git
After installing Git, configure it with your name and email address using the following commands in your terminal or command prompt:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Open Your Project in VS Code
Open VS Code and navigate to the folder containing your project. You can do this by opening VS Code and selecting File > Open Folder... or by using the terminal:
code /path/to/your/project

Initialize a Git Repository
In VS Code, open the integrated terminal by pressing Ctrl+` or going to View > Terminal. In the terminal, run:
git init
This command initializes a new Git repository in your project folder.

Make Initial Commit
Stage your files for the initial commit by running:
git add .
This stages all the files in your project. Then, commit the staged files:
git commit -m "Initial commit"

Connect to GitHub
To push your repository to GitHub, you need to create a new repository on GitHub. Go to GitHub, log in, and create a new repository.

Add Remote Repository
Copy the repository URL from GitHub (either HTTPS or SSH). In the terminal, add the remote repository:
git remote add origin https://github.com/your-username/your-repository.git

Push Changes to GitHub
Push your initial commit to GitHub:
git push -u origin master

Using Git in VS Code
VS Code has built-in Git support. Here’s how you can use it for further commits and pushes:
Stage and Commit Changes
Make changes to your files.
Open the Source Control view by clicking on the Source Control icon in the sidebar or pressing Ctrl+Shift+G.
You will see a list of changed files. Click the + icon next to each file to stage it, or click the + icon at the top to stage all changes.
Enter a commit message in the input box at the top and click the checkmark icon to commit.

Push Changes
After committing your changes, you can push them to GitHub. In the Source Control view, click on the ... menu and select Push, or use the terminal:
git push

Pull Changes from GitHub
To pull changes from GitHub (if you have collaborators or made changes directly on GitHub):

Open the Source Control view.
Click on the ... menu and select Pull, or use the terminal:
git pull

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

