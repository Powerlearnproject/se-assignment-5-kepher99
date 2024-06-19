# SE-Assignment-5: Installation and Navigation of Visual Studio Code (VS Code)

## 1. Installation of VS Code

### Steps to Download and Install Visual Studio Code on Windows 11:
1. **Download VS Code:**
   - Visit the [Visual Studio Code website](https://code.visualstudio.com/).
   - Click on the "Download for Windows" button.
   - The download should start automatically. Save the installer file (e.g., `VSCodeUserSetup-x64-1.60.0.exe`).

2. **Run the Installer:**
   - Locate the downloaded installer file and double-click it to run.
   - Follow the setup wizard. Accept the license agreement and click "Next".

3. **Choose Installation Location:**
   - Select the destination folder where you want to install VS Code. The default location is usually fine. Click "Next".

4. **Select Additional Tasks:**
   - Choose additional tasks you want the installer to perform. Common options include:
     - Adding VS Code to PATH (so you can use `code` command in the terminal).
     - Creating a desktop icon.
     - Registering VS Code as an editor for supported file types.

5. **Install:**
   - Click "Install" to begin the installation process.
   - Once the installation is complete, click "Finish".

### Prerequisites:
- Windows 11 operating system.
- Administrative privileges to install software.
- Internet connection to download the installer.

## 2. First-time Setup

### Initial Configurations and Settings:
1. **Theme and Appearance:**
   - Open VS Code and go to `File > Preferences > Color Theme` to choose a preferred theme (e.g., Dark, Light).

2. **Font Size and Family:**
   - Navigate to `File > Preferences > Settings`, then search for "Font Size" to adjust the font size.
   - Similarly, search for "Font Family" to change the font family.

3. **Extensions:**
   - Open the Extensions view by clicking the Extensions icon in the Activity Bar or pressing `Ctrl+Shift+X`.
   - Essential extensions for web development include:
     - **ESLint**: Provides linting capabilities.
     - **Prettier**: Code formatter.
     - **Live Server**: Launches a local development server.
     - **Debugger for Chrome**: Debug your JavaScript code in the Google Chrome browser.

4. **Settings Sync:**
   - Enable Settings Sync via `File > Preferences > Settings Sync`, allowing you to sync your settings, extensions, and preferences across multiple machines.

## 3. User Interface Overview

### Main Components:
1. **Activity Bar:**
   - Located on the left side of the window.
   - Provides access to various views like Explorer, Search, Source Control, Run and Debug, and Extensions.

2. **Side Bar:**
   - Displays different views and their contents based on the selected Activity Bar icon.
   - For example, the Explorer view shows the file and folder structure of your project.

3. **Editor Group:**
   - Central part of the interface where you open and edit your files.
   - You can split the editor into multiple groups for side-by-side editing by right-clicking on the tab and selecting "Split Right" or "Split Down".

4. **Status Bar:**
   - Located at the bottom of the window.
   - Displays important information about the current workspace, like encoding, line endings, and the current branch if using version control.

## 4. Command Palette

### Description and Access:
- The Command Palette is a powerful tool in VS Code that provides quick access to various commands and features.
- Access it by pressing `Ctrl+Shift+P` (or `F1`).

### Common Tasks Using Command Palette:
- **Open a file**: Type `>Open File`.
- **Change language mode**: Type `>Change Language Mode`.
- **Run a task**: Type `>Run Task`.
- **Toggle terminal**: Type `>Toggle Integrated Terminal`.

## 5. Extensions in VS Code

### Role and Management:
- **Role**: Extensions add functionality to VS Code, enhancing the development experience with features like linting, debugging, and code formatting.
- **Finding Extensions**: Open the Extensions view (`Ctrl+Shift+X`) and search for the desired extension.
- **Installing Extensions**: Click the "Install" button next to the extension's name.
- **Managing Extensions**: Manage installed extensions from the Extensions view, where you can disable or uninstall them.

### Essential Extensions for Web Development:
- **ESLint**: Helps in identifying and fixing coding errors.
- **Prettier**: Formats code consistently.
- **Live Server**: Provides a local server with live reload capabilities.
- **Debugger for Chrome**: Allows you to debug your code directly in the Chrome browser.

## 6. Integrated Terminal

### Opening and Using the Integrated Terminal:
- **Opening**: Access the integrated terminal by selecting `View > Terminal` or pressing `` Ctrl+` `` (backtick).
- **Using**: You can use the terminal just like any other terminal to run commands, install packages, or execute scripts.

### Advantages:
- **Convenience**: Work within the same window as your code editor.
- **Integrated Environment**: Seamless access to the project files and code context.
- **Multiple Terminals**: Open and manage multiple terminal instances.

## 7. File and Folder Management

### Creating, Opening, and Managing Files and Folders:
- **Creating**:
  - Right-click in the Explorer view and select `New File` or `New Folder`.
  - Use `File > New File` or `File > New Folder`.

- **Opening**:
  - Double-click a file in the Explorer view.
  - Use `File > Open File` or `File > Open Folder`.

- **Managing**:
  - Rename: Right-click the file or folder and select `Rename`.
  - Delete: Right-click and select `Delete`.

### Efficient Navigation:
- **Quick Open**: Press `Ctrl+P` to quickly open files by typing their names.
- **File Explorer**: Use the Explorer view to navigate through the directory structure.
- **Breadcrumb Navigation**: Use the breadcrumb trail at the top of the editor to navigate folders.

## 8. Settings and Preferences

### Customizing Settings:
- **Access Settings**: Go to `File > Preferences > Settings` or press `Ctrl+,`.
- **Changing Theme**: Search for "Color Theme" and select a preferred theme.
- **Adjusting Font Size**: Search for "Font Size" and set the desired size.
- **Keybindings**: Navigate to `File > Preferences > Keyboard Shortcuts` to customize keybindings.

## 9. Debugging in VS Code

### Setting Up and Starting Debugging:
1. **Open a File**: Open the file you want to debug.
2. **Set Breakpoints**: Click in the gutter next to the line numbers to set breakpoints.
3. **Configure Debugging**: Go to the Run and Debug view (`Ctrl+Shift+D`). Click on `create a launch.json file` to configure your debugger.
4. **Start Debugging**: Click the green play button or press `F5`.

### Key Debugging Features:
- **Breakpoints**: Pause code execution at specific lines.
- **Watch Variables**: Monitor variable values during execution.
- **Call Stack**: View the call stack to trace function calls.
- **Step Over/Into/Out**: Navigate through code execution line by line.

## 10. Using Source Control

### Integrating Git with VS Code:
1. **Initialize a Repository**: 
   - Open the terminal and run `git init` in your project directory.
   - Alternatively, use `Source Control > Initialize Repository`.

2. **Making Commits**:
   - Stage changes by clicking the `+` icon next to the file in the Source Control view.
   - Write a commit message and click the checkmark icon to commit.

3. **Pushing Changes to GitHub**:
   - Ensure you have a remote repository set up on GitHub.
   - Add the remote URL: `git remote add origin <repository-url>`.
   - Push changes: `git push -u origin master`.

### Example Workflow:
- **Initialize**: `git init` or `Source Control > Initialize Repository`.
- **Stage Changes**: Use the Source Control view or `git add <file>`.
- **Commit**: Write a commit message and commit changes.
- **Push**: Push changes to GitHub using the terminal or integrated Git commands.

 By following these guidelines, you will be able to effectively install, configure, and utilize Visual Studio Code for your development projects. For further information and visual aids, refer to the official [Visual Studio Code documentation](https://code.visualstudio.com/docs)
