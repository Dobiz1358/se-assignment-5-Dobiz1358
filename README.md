[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15323938&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on the Windows 11 operating system. Include any prerequisites that might be needed.

  Prerequisites: Ensure that you have Windows 11 and administrator access
  Open a web browser, go to Visual Studio Code's website, and click the "Download" button for Windows.
  Open the downloaded file and allow changes if prompted.
  Accept the license agreement, choose the installation location and Start Menu folder, select additional tasks e.g., add to PATH, Click "install" and wait for the process to complete.
  Check "Launch Visual Studio Code" and click "Finish" or launch it later from the Start Menu or desktop icon.
 

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

Configurations and settings:
   Choosing a color theme and file icon theme, setting preferred font and size in the settings, configuring tab size and spaces for indentation, enabling autosave to prevent data loss, enabling automatic code formatting on save, toggling the visibility of the code minimap, setting line number display to on, off, relative or interval

 Recommended Extensions:
 Python, Javascript/Typescript, C/C++, HTML/CSS extensions, GitLens, GitHub Pull Requests and Issues, Debugger for Chrome, ESLint and Jest, Prettier, Liver Server, Path Intellisense, Javascript(ES6) snippets, Python snippets.
 

4. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
  
     the main components of the VS code user interface are:
     - Activity Bar: It provides quick access to core features such the Explorer, Search, Source Control, Run and Debug, and Extensions.
     - Side Bar: it displays detailed content for the selected activity e.g., file explorer, search results, etc
     - Editor Group: the central area where you edit files, with tabs for open files and options for splitting the editor into multiple views.
     - Status Bar: it shows information about the current state of the editor and workspace such as cursor position, language mode, encoding, line endings, Git branch, and notifications.
       

5. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

  it is a powerful tool for quickly accessing commands and features without navigating the menus. it can be accessed by pressing 'Ctrl+Shift+P' for Windows/Linux or 'Cmd+Shift+P' for Mac or via 'View > Command Palette' in the menu 
  Common Tasks: 
  - Open files: '>Open File'
  - Run Commands: '>Go to Line', '>Format Document', '>Toggle Sidebar'
  - Manage Extensions: '>Extensions: Install Extension', '>Extensions: Show Installed Extensions'
  - Search and Replace: '>Replace in Files'
  - Version Control: '>Git: Commit'
  - Debugging: '>Debug: Start Debugging'
  - Terminal: '>Terminal: Create New Integrated Terminal'
  - Settings: '>Preferences: Open Settings'
     

6. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

Extensions enhance VS code by adding support for additional languages, tools, and features, customizing the development environment to meet specific needs

To find extensions: click the Extensions icon in the Activity Bar, press 'Ctrl+Shift+X', or browse the visual studio code Marketplace online 
To find install extensions: Search and click the install button next to the desired extension, open the Command Palette, type '>Extensions: Install Extension', and search.
To manage extensions: use the gear icon next to an installed extension, notifications will appear for updates or update via the Extensions view and the same applies to uninstall.

Essential Extensions: 
ESLint for Javascript linting. Prettier which is a code formatter, HTML CSS Support which enhances HTML and CSS, JavaScript(ES6) code snippets which provides code snippets, GitLens which enhances Git capabilities, GitHub Pull Requests and Issues which manages GitHub pull requests and issues, Live Server which launches a local server with live reload, Path INtellisense which autocompletes file paths, Debugger for Chrome which debugs JavaScript in chrome.


7. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

Press 'Ctrl+'' or use 'View > Terminal' to open the integrated terminal, Use the Command Palette and type '>Terminal: Create New Integrated Terminal'
Navigate directories ('cd', 'ls'/'dir') and execute commands directly within the terminal.

Advantages:
- Access to the terminal without leaving VS Code
- Maintains project context while navigating files and directories
- Executes Git, debugging, and other commands seamlessly within VS Code
- Minimizes switching between VS Code and external terminals
- Tailors terminal settings and behavior to personal preferences
  

8. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

 Creating and Opening: Use the Explorer panel or 'Ctrl+P' to create new files, right-click in the Explorer panel to create new folders, Double-click on files in the Explorer panel, or use 'Ctrl+P' to open files by name.
 
 Managing: Right-click and select 'Rename' in the Explorer panel to rename files, Right-click and select 'Delete' in the Explorer panel to delete files, Drag and drop within the Explorer panel or use 'Ctrl+C' and 'Ctrl+V' to copy and paste files.
 
 How users can navigate efficiently:
 - By using the Explorer Panel to navigate folders and files
 - By using 'Ctrl+Tab' to cycle through open files
 - By using 'Ctrl+P' to open files quickly by typing their names
 - By navigating directories and performing advanced file operations using the integrated terminal ('Ctrl+'')

9. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

Open the Settings editor with 'Ctrl+,' or through 'File > Preferences > Settings' or Use the Command Palette and search for 'Preferences: Open Settings'

Examples of customization:
- Changing the theme: Navigate to 'File > Preferences > Color Theme' or use shortcuts ('Ctrl+K Ctrl+T')
- Adjusting Font Size: Search for 'editor.fontSize' in settings and modify the value
- Modifying Keybindings: Navigate to 'File > Preferences > Keyboard Shortcuts' or use shortcuts ('Ctrl+K Ctrl+S') to customize keybindings.
  

10. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

Ensure debugger extensions are installed for your programming language
Open your project, click on the Debugging icon ('Ctrl+Shift+D'), and configure 'launch.json' for your environment 
Click in the gutter or press 'F9' to set breakpoints in your code 
Press 'F5' or click 'Start Debugging' to begin debugging
Use shortcuts ('F10', 'F11', 'Shift+F11') for step-over, step-into, step-out; 'F5' to continue; 'Ctrl+Shift+F5" to restart; 'Shift+F5' to stop.

Key Debugging Features:
Variable watch, call stack navigation, conditional breakpoints, exception handling, integrated terminal('Ctrl+Shift+Y'), and multisession debugging.


11. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
   
Initialize a Repository: 
Open VS code, and navigate to your project folder. 
Open the integrated terminal and initialize Git with 'git init'.

Make Commits: 
Make changes to your files in Vs Code.
Stage changes in the Source Control view ('Ctrl+Shift+G') by clicking the '+' icon
Commit changes with a message.

Push Changes to GitHub:
Create a repository on GitHub if not already done.
set the GitHub repository as the remote origin in the terminal using this 'git remote add origin https://github.com/username/repository.git'.
push changes using this 'git push -u origin main' substituting 'main' with your branch name.



 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

