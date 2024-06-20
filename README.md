# Developer Environment Setup Documentation

## Objective:
This documentation outlines the process of setting up an efficient developer environment for software engineering projects, including the installation and configuration of necessary tools and software.

## Tasks and Steps:

### 1. Select Your Operating System (OS)
- **Chosen OS:** Windows 11
- **Steps:**
  1. Visit the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).
  2. Click "Download now" to get the installation media.
  3. Follow the on-screen instructions to install Windows 11 on your machine.

### 2. Install a Text Editor or Integrated Development Environment (IDE)
- **Chosen IDE:** Visual Studio Code (VS Code)
- **Steps:**
  1. Visit the [Visual Studio Code download page](https://code.visualstudio.com/Download).
  2. Download the appropriate installer for Windows.
  3. Run the installer and follow the prompts to complete the installation.

### 3. Set Up Version Control System
- **Tools:** Git and GitHub
- **Steps:**
  1. **Install Git:**
     - Visit the [Git download page](https://git-scm.com/download/win).
     - Download and run the Git installer for Windows.
     - Follow the installation prompts, ensuring "Use Git from the command line and also from 3rd-party software" is selected.
  2. **Configure Git:**
     - Open Git Bash and configure your Git user information:
       ```bash
       git config --global user.name "Your Name"
       git config --global user.email "your.email@example.com"
       ```
  3. **Create a GitHub Account:**
     - Go to [GitHub](https://github.com) and sign up for a new account if you don't have one.
  4. **Initialize a Git Repository:**
     - Create a new directory for your project:
       ```bash
       mkdir MyProject
       cd MyProject
       ```
     - Initialize a Git repository:
       ```bash
       git init
       ```
     - Create a README file and make your first commit:
       ```bash
       echo "# MyProject" >> README.md
       git add README.md
       git commit -m "Initial commit"
       ```
     - Push the repository to GitHub:
       ```bash
       git remote add origin https://github.com/yourusername/MyProject.git
       git push -u origin master
       ```

### 4. Install Necessary Programming Languages and Runtimes
- **Programming Language:** Python
- **Steps:**
  1. Visit the [Python download page](https://www.python.org/downloads/).
  2. Download the Python installer for Windows.
  3. Run the installer and ensure "Add Python to PATH" is checked.
  4. Complete the installation and verify the installation by running:
     ```bash
     python --version
     ```

### 5. Install Package Managers
- **Package Manager:** pip (comes with Python installation)
- **Steps:**
  1. Verify pip installation:
     ```bash
     pip --version
     ```

### 6. Configure a Database (MySQL)
- **Database:** MySQL
- **Steps:**
  1. Visit the [MySQL Installer page](https://dev.mysql.com/downloads/windows/installer/5.7.html).
  2. Download and run the MySQL Installer.
  3. Follow the installation steps, selecting the appropriate configuration for your needs.

### 7. Set Up Development Environments and Virtualization (Optional)
- **Tool:** Docker (optional)
- **Steps:**
  1. Visit the [Docker Desktop for Windows page](https://www.docker.com/products/docker-desktop).
  2. Download and run the Docker Desktop installer.
  3. Follow the installation instructions and start Docker Desktop.

### 8. Explore Extensions and Plugins
- **VS Code Extensions:**
  1. Open VS Code and navigate to the Extensions view by clicking the Extensions icon in the Activity Bar.
  2. Install the following extensions:
     - Python
     - GitLens
     - Prettier - Code formatter
     - ESLint

### Documentation of the Setup Process
- **Steps Documentation:**
  - Detailed steps are outlined above with links and commands.
- **Screenshots:**
  - Include screenshots of installation processes, configuration files, and IDE setups.

### Reflection on Challenges and Solutions
- **Challenges:**
  - Ensuring all installations are correctly configured to avoid path issues.
  - Familiarizing with different configurations and settings in VS Code and Git.
- **Solutions:**
  - Thoroughly reading official documentation and following community forums for troubleshooting.
  - Testing each setup step to ensure proper functionality before proceeding to the next.

### Submission
- **GitHub Repository Link:**
  - [MyProject Repository](https://github.com/yourusername/MyProject)
- **Document Submission:**
  - Submit this document and the GitHub repository link to the designated platform or email to the instructor by the specified deadline.

## Evaluation Criteria
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

### Installation of Visual Studio Code (VS Code)

**Steps to Download and Install Visual Studio Code on Windows 11:**

1. **Visit the VS Code Website:**
   - Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).

2. **Download the Installer:**
   - Click on the Windows download link to download the VS Code installer (VSCodeUserSetup-{version}.exe).

3. **Run the Installer:**
   - Once the download is complete, open the installer by double-clicking on it.

4. **Follow the Installation Wizard:**
   - Accept the agreement and click "Next".
   - Choose the destination folder (default is usually fine) and click "Next".
   - Select additional tasks (e.g., creating a desktop icon, adding to PATH) and click "Next".
   - Click "Install" to start the installation process.

5. **Complete the Installation:**
   - After installation, click "Finish" to launch Visual Studio Code.

**Prerequisites:**
- There are no specific prerequisites for installing VS Code itself, but for optimal performance, ensure your system meets the [minimum requirements](https://code.visualstudio.com/docs/supporting/requirements) for running VS Code.

### First-time Setup

**Initial Configurations and Settings:**

1. **Theme and Appearance:**
   - Go to `File > Preferences > Color Theme` to choose a preferred theme.
   - Popular themes include "Dark+ (default dark)" and "Light+ (default light)".

2. **Extensions:**
   - Open the Extensions view by clicking on the Extensions icon in the Activity Bar.
   - Search for and install essential extensions like Python, Prettier - Code formatter, and GitLens.

3. **Settings Sync:**
   - Enable Settings Sync by going to `File > Preferences > Settings Sync` and follow the prompts to sync settings across devices.

4. **Keyboard Shortcuts:**
   - Customize keyboard shortcuts by going to `File > Preferences > Keyboard Shortcuts`.

### User Interface Overview

**Main Components of the VS Code User Interface:**

1. **Activity Bar:**
   - Located on the far left, it provides access to different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.

2. **Side Bar:**
   - Displays different views like Explorer (file navigation), Search, Source Control, and Extensions. It changes based on the selected view from the Activity Bar.

3. **Editor Group:**
   - The central area where you edit files. You can have multiple editors open in tabs and split them into multiple groups for side-by-side editing.

4. **Status Bar:**
   - Located at the bottom of the window, it provides information about the current file, such as line number, column, encoding, and the active Git branch. It also displays errors and warnings.

### Command Palette

**What is the Command Palette and How to Access it:**

- The Command Palette is a quick way to access various commands and features in VS Code.
- **Accessing the Command Palette:**
  - Press `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (Mac).
  
**Common Tasks Using the Command Palette:**
- Open a file: `Ctrl+P`
- Change the color theme: `Preferences: Color Theme`
- Install extensions: `Extensions: Install Extensions`
- Run tasks: `Tasks: Run Task`

### Extensions in VS Code

**Role of Extensions:**
- Extensions enhance the functionality of VS Code, providing additional features like language support, debuggers, linters, and more.

**Finding, Installing, and Managing Extensions:**
1. Open the Extensions view by clicking on the Extensions icon in the Activity Bar.
2. Search for extensions using the search bar.
3. Click the "Install" button next to the desired extension.
4. Manage installed extensions via the "Installed" tab in the Extensions view.

**Essential Extensions for Web Development:**
- **Live Server:** Launch a development local server with live reload feature.
- **ESLint:** Integrate ESLint for JavaScript and TypeScript linting.
- **Prettier - Code formatter:** Automatically format code.

### Integrated Terminal

**Opening and Using the Integrated Terminal:**
- Open the integrated terminal by pressing `Ctrl+` (Windows/Linux) or `Cmd+` (Mac).
- Use the terminal for running commands, managing projects, and executing scripts directly within VS Code.

**Advantages of Integrated Terminal:**
- Context switching is minimized as the terminal is embedded within the editor.
- Multiple terminals can be opened and managed simultaneously.
- Terminal sessions are saved and restored when reopening VS Code.

### File and Folder Management

**Creating, Opening, and Managing Files and Folders:**
1. **Create a New File/Folder:**
   - Right-click in the Explorer view and select `New File` or `New Folder`.
   - Alternatively, use the Command Palette and type `File: New File` or `File: New Folder`.
2. **Open Files/Folders:**
   - Use `File > Open File` or `File > Open Folder`.
   - Drag and drop files/folders into the Explorer view.
3. **Navigate Between Files:**
   - Use `Ctrl+P` (Windows/Linux) or `Cmd+P` (Mac) to quickly open files by name.
   - Use `Ctrl+Tab` to cycle through open files.

### Settings and Preferences

**Finding and Customizing Settings:**
1. **Open Settings:**
   - Go to `File > Preferences > Settings`.
2. **Change Theme:**
   - In Settings, search for "Color Theme" and select a theme from the dropdown.
3. **Change Font Size:**
   - In Settings, search for "Font Size" and adjust the value.
4. **Change Keybindings:**
   - Go to `File > Preferences > Keyboard Shortcuts` and customize shortcuts as needed.

### Debugging in VS Code

**Setting Up and Starting Debugging:**
1. **Open Debug View:**
   - Click the Run and Debug icon in the Activity Bar or press `Ctrl+Shift+D`.
2. **Configure Debugging:**
   - Click on `create a launch.json file` to configure debugging for your project.
3. **Set Breakpoints:**
   - Click in the gutter next to the line numbers to set breakpoints.
4. **Start Debugging:**
   - Click the green play button or press `F5`.

**Key Debugging Features:**
- Breakpoints
- Watch Variables
- Call Stack
- Debug Console

### Using Source Control

**Integrating Git with VS Code:**
1. **Initialize a Repository:**
   - Open the Source Control view by clicking the Source Control icon in the Activity Bar.
   - Click `Initialize Repository` to create a new Git repository.
2. **Making Commits:**
   - Stage changes by clicking the `+` icon next to the files.
   - Enter a commit message in the message box and click the checkmark icon to commit.
3. **Pushing Changes to GitHub:**
   - Click the ellipsis (`...`) in the Source Control view and select `Push`.
   - If prompted, provide your GitHub credentials.
   - Link the local repository to a GitHub repository using the command:
     ```bash
     git remote add origin https://github.com/yourusername/your-repo.git
     git push -u origin master
     ```

By following these instructions, you'll have a fully set up and functional developer environment with Visual Studio Code, tailored to your coding needs.