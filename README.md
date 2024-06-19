[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15279855&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

SYSTEM REQUIREMENT FOR WINDOWS 11
- Processor: 1 GHz or faster with at least 2 cores on a compatible 64-bit processor or System on a Chip (SoC)
- RAM: 4 GB or more
- Storage: 64 GB or larger storage device
- System firmware: UEFI, Secure Boot capable
- TPM: Trusted Platform Module (TPM) version 2.0
- Graphics card: DirectX 12 compatible graphics / WDDM 2.x
- Display: >9” with HD Resolution (720p)
- Internet connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

STEP 1: BACKUP YOUR DATA
Before installing a new operating system, it's important to back up your data. Use an external hard drive or a cloud service to back up important files.

STEP 2: DOWNLOAD WINDOWS 11 
Using Windows Update
Go to Settings > Update & Security > Windows Update.
Click on Check for updates. If your PC is eligible for Windows 11, you will see an option to upgrade to Windows 11.


Using Windows 11 Installation Assistant
Go to the official Windows 11 download page.
Click on Download Now under the Windows 11 Installation Assistant section.
Run the downloaded file and follow the instructions to upgrade to Windows 11.

Creating a Bootable USB Drive
On the Windows 11 download page, scroll down to the Create Windows 11 Installation Media section.
Click on Download Now to download the Media Creation Tool.
Run the Media Creation Tool and follow the instructions to create a bootable USB drive.

STEP 3: INSTALL WINDOWS 11 
Using Windows Update or Installation Assistant

Follow the on-screen instructions provided by the tool to complete the installation process.
Clean Installation Using Bootable USB Drive

Insert the bootable USB drive into your PC and restart it.
Press the appropriate key (usually F2, F12, Delete, or Esc) to enter the BIOS/UEFI settings.
Set the USB drive as the primary boot device and save the changes.
Restart your PC, and it should boot from the USB drive.
Follow the on-screen instructions to install Windows 11. You can choose to upgrade your existing OS or perform a clean installation.

STEP 4: POST-INSTALLATION
Setup Windows 11

Follow the setup prompts to configure your region, language, and keyboard layout.
Connect to a network and sign in with your Microsoft account.
Customize your settings and privacy preferences.
Update Drivers and Software

After installation, go to Settings > Update & Security > Windows Update and check for updates to ensure you have the latest drivers and system updates.
Reinstall necessary applications and restore your backed-up data.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

STEP 1: DOWNLOAD VISTUAL STUDIO CODE 
Visit the official VS Code website: Go to https://code.visualstudio.com/.
Download the installer: Click on the download button that corresponds to your operating system (Windows, macOS, or Linux).

STEP 2: INSTALL VISUAL STUDIO CODE ON WINDOWS 
- Run the installer: Locate the downloaded file (usually named something like VSCodeSetup-x.x.x.exe) and double-click it to run the installer.
- Accept the license agreement: Read through the license agreement and click "I accept the agreement" to proceed.
- Choose the installation location: Select the destination folder where you want to install VS Code, or leave the default location as it is. Click "Next".
- Select additional tasks:
  Add "Open with Code" action to Windows Explorer file context menu.
  Add "Open with Code" action to Windows Explorer directory context menu.
  Register Code as an editor for supported file types.
  Add to PATH (you might need this to open VS Code from the command line).
- Install: Click "Install" to begin the installation process.
- Launch VS Code: Once the installation is complete, you can check the "Launch Visual Studio Code" option and click "Finish" to open VS Code.

STEP 3: CONFIGURE AND START USING VISUAL STUDIO CODE
- Open VS Code: Launch Visual Studio Code from your Start Menu (Windows), Applications folder (macOS), or via your application launcher/terminal (Linux).
- Install extensions: Click on the Extensions view icon on the Sidebar or press Ctrl+Shift+X to open the Extensions view. From here, you can search for and install extensions to enhance your development experience.
- Configure settings: Customize your VS Code settings by navigating to File > Preferences > Settings (Windows/Linux) or Code > Preferences > Settings (macOS).



3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

STEP 1: INSTALL GIT
On Windows
- Download the Git installer: Visit the official Git website at https://git-scm.com/ and click the "Download for Windows" button.
- Run the installer: Locate the downloaded .exe file and double-click it to run the installer.
- Setup Git: Follow the installation steps, choosing your preferred settings. The default options are usually suitable for most users.
- Adjusting your PATH environment: Ensure "Git from the command line and also from 3rd-party software" is selected.
- Choosing a SSH executable: Use the bundled OpenSSH.
- Configuring the line ending conversions: Choose "Checkout Windows-style, commit Unix-style line endings" (recommended).
- Configuring the terminal emulator: Use the default "Use MinTTY" option. 

STEP 2: CONFIGURE GIT
After installing Git, you'll want to configure it with your user information. This is important because Git uses this information for commit messages.

- Open a terminal or Git Bash: (Git Bash on Windows, Terminal on macOS and Linux).
- Set your username: Run the following command, replacing "Your Name" with your actual name: git config --global user.name "Your Name"
- Set your email address: Run the following command, replacing "your.email@example.com" with your actual email address: git config --global user.email "your.email@example.com"
- Verify your configuration: To verify that your changes were applied, run: git config --list

STEP 3: BASIC GIT COMMANDS
Here are a few basic Git commands to get you started:

- Initialize a new Git repository: git init
- Clone an existing repository:git clone <repository-url>
- Add files to the staging area: git add <file>
- Commit changes: git commit -m "Commit message"
- Check the status of your repository:git status
- View commit history: git log
 
STEP 1: Sign Up for a GitHub Account
Visit GitHub: Open your web browser and go to GitHub's website.

Sign Up:

- Click on the "Sign up" button at the top right corner of the page.
- Enter your email address and click "Continue".
- Create a password and click "Continue".
- Choose a username (this will be your GitHub handle) and click "Continue".
- You may be asked to solve a puzzle or complete a CAPTCHA to verify you're not a robot.
- Choose whether you want to receive updates and announcements from GitHub, then click "Continue".
- Verify your email address by clicking the link sent to your email.

STEP 2: Set Up Your Profile
Complete Your Profile:

After verifying your email, you will be redirected to the GitHub welcome page.
Fill out the profile information, including your name, bio, and other details. This step is optional and can be completed later.
Personalize Your Experience:

GitHub may ask a few questions to personalize your experience, such as your level of programming experience and your interests. Answer these questions or skip them.

STEP 3: Create a New Repository
Create a Repository:

- Click on the + icon in the top right corner of the GitHub homepage and select "New repository".
- Fill out the repository details:
- Repository Name: Enter a unique name for your repository.
- Description: Provide a short description of your project (optional).
- Public or Private: Choose whether your repository will be public (anyone can see it) or private (only you can see it).
- Initialize this repository with a README: Check this box if you want to create a README file.
- Add .gitignore: Optionally, select a .gitignore template that fits your project needs.
- Add a license: Optionally, choose a license for your project.
- Create Repository: Click the "Create repository" button to finish.


4. Install Necessary Programming Languages and Runtimes:
  Install Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

STEP 1: DOWNLOAD THE PYTHON INSTALLER 
Visit the official Python website: Go to https://www.python.org/.
Navigate to the Downloads page: The site should automatically detect your operating system and provide the appropriate download link. If not, you can manually select your operating system.

STEP 2: INSTALL PYTHON ON WINDOWS
- Download the Installer: Click on the download link for the latest version of Python for Windows (usually, it's the first button on the Downloads page).
- Run the Installer: Locate the downloaded .exe file and double-click it to run the installer.
- Customize the Installation:
- Check the box that says Add Python to PATH. This is important for accessing Python from the command line.
- Click on Customize installation if you want to modify the default settings (recommended for advanced users). Otherwise, click on Install Now.
- Complete the Installation: Follow the prompts and wait for the installation to complete. You can verify the installation by opening Command Prompt and typing: python --version



5. Install Package Managers:
   If applicable, install package managers like pip (Python).

INSTALL PIP (Python Package Installer)
Most Python installations come with pip pre-installed. To check if pip is installed, open your command line (Command Prompt, Terminal, etc.) and type: pip --version

If you get a version number, pip is installed. If not, follow these steps:
Download get-pip.py:

Open a web browser and go to the get-pip.py page.
Right-click and save the file to your computer.
Run get-pip.py:

Open your command line.
Navigate to the directory where you saved get-pip.py.
Run the script:python get-pip.py

VERIFT THE INSTALLATION
Check Python Version: Open your command line and type: python --version

Install a Virtual Environment (Optional but Recommended)
Using virtual environments is a good practice for managing dependencies for different projects.

Install virtualenv: pip install virtualenv
Create a Virtual Environment:
Navigate to your project directory.
Create a virtual environment: python -m venv env
Activate the virtual environment: .\env\Scripts\activate



6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html


STEP 1: DOWNLOAD MYSQL
- Visit the MySQL website: Go to the official MySQL download page at https://dev.mysql.com/downloads/.
- Select MySQL Community Server: Under the "MySQL Community (GPL) Downloads" section, click on "MySQL Community Server".

STEP 2: INSTALL MYSQL ON WINDOWS MySQL 
- Download the Installer: Click on the "Windows (x86, 64-bit), MySQL Installer MSI" to download the installer.
- Run the Installer: Locate the downloaded .msi file and double-click it to run the installer.
- Choose Setup Type:
- Developer Default: Installs MySQL Server, MySQL Shell, MySQL Workbench, and other development tools.
- Server only: Installs only the MySQL Server.
- Client only: Installs MySQL client programs.
- Full: Installs all components.
- Custom: Allows you to choose the components to install.
- Follow the Installation Steps:
- Click "Next" and then "Execute" to download and install the required components.
- After installation, click "Next" to proceed to configuration.
- Configure MySQL Server:
- Config Type: Choose "Development Machine", "Server Machine", or "Dedicated Machine".
- Authentication Method: Select the preferred authentication method (strongly recommended to use the "Use Strong Password Encryption").
- Accounts and Roles: Set the root password and optionally create a new user.
- Windows Service: Choose to run MySQL as a Windows Service and optionally set it to start at boot.
- Complete the Installation: Click "Finish" after the installation and configuration are complete.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

Setting Up Python Virtual Environments
Python virtual environments allow you to create isolated environments for your projects, each with its own dependencies.

USING VENV
- Install Python: Ensure Python is installed on your system. You can check this by running: python --version
- Create a Virtual Environment: python -m venv myenv
- Activate the Virtual Environment: myenv\Scripts\activate
- Install Packages: With the virtual environment activated, you can install packages using pip: pip install package_name
- Deactivate the Virtual Environment: deactivate

USING DOCKER FOR CONTAINERIZATION 
Docker allows you to package applications and their dependencies into containers, ensuring consistency across different environments.

INSTALL DOCKER
- Download Docker Desktop: Go to Docker's website and download Docker Desktop for your operating system.
- Install Docker Desktop: Follow the installation instructions for your OS.
- Basic Docker Commands
- Pull an Image from Docker Hub: docker pull image_name
- Run a Container: docker run -it --name container_name image_name
- List Running Containers: docker ps
- Stop a Container: docker stop container_name
- Remove a Container: docker rm container_name



Setting Up Virtual Machines with VirtualBox
VirtualBox allows you to run multiple operating systems on your host machine, each in its own isolated environment.

INSTALL VIRTUALBOX
- Download VirtualBox: Go to VirtualBox's website and download the installer for your operating system.
- Install VirtualBox: Follow the installation instructions for your OS.
- Create a Virtual Machine
- Open VirtualBox and click New to create a new VM.
- Name and Operating System: Enter a name for your VM and select the operating system type and version.
- Memory Size: Allocate memory (RAM) to the VM. A recommended amount is typically half of your system's RAM.
- Hard Disk: Create a virtual hard disk now, or use an existing one.
- Hard Disk File Type: Choose VDI (VirtualBox Disk Image).
- Storage on Physical Hard Disk: Choose between dynamically allocated or fixed size.
- File Location and Size: Specify the location and size of the virtual hard disk.
- Install an Operating System on the VM
- Start the VM: Select your new VM and click Start.
- Select Installation Media: Choose the installation media for the operating system (ISO file or physical disk).
- Follow OS Installation Steps: Follow the steps to install the operating system on the VM




8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.


Visual Studio Code (VS Code)
VS Code is a popular code editor with a vast marketplace of extensions.

INSTALLING EXTENSION IN VS CODE
- Open VS Code.
- Access the Extensions View: Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X (Windows/Linux) or Cmd+Shift+X (macOS).
- Search for Extensions: Use the search bar to find extensions. For example, search for "Python" or "Docker".
- Install an Extension: Click on the extension you want to install, then click the Install button.
- Manage Extensions: Installed extensions can be enabled, disabled, or uninstalled from the Extensions view.
- Recommended Extensions for VS Code
- Python: Adds support for Python programming, including linting, debugging, and code navigation.
- Docker: Provides tools to work with Docker containers and images directly from VS Code.
- ESLint: Integrates ESLint JavaScript into VS Code.
- Prettier - Code Formatter: Automatically formats your code to maintain consistency.
- GitLens: Enhances the Git capabilities built into VS Code.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

Comprehensive Guide to Setting Up a Developer Environment
Table of Contents
Introduction
Installing Python
Setting Up Python Virtual Environments
Installing and Configuring Visual Studio Code
Setting Up Docker
Setting Up Virtual Machines with VirtualBox
Exploring Extensions and Plugins
Troubleshooting
Introduction
This document provides a step-by-step guide to setting up a development environment, including installing Python, setting up virtual environments, configuring Visual Studio Code, using Docker, and setting up virtual machines with VirtualBox. It also covers exploring useful extensions and plugins.

Installing Python
Download Python:
Go to Python's official website.
Download the latest version of Python for your operating system.

Install Python:
Windows: Run the downloaded .exe file. Make sure to check the "Add Python to PATH" box and click "Install Now".
macOS: Run the downloaded .pkg file and follow the installer instructions.
Linux:sudo apt update
      sudo apt install python3

Verify Installation: python --version

Setting Up Python Virtual Environments
Create a Virtual Environment: python -m venv myenv

Activate the Virtual Environment:
Windows: myenv\Scripts\activate
macOS/Linux: source myenv/bin/activate

Install Packages: pip install package_name
Deactivate the Virtual Environment: deactivate

Installing and Configuring Visual Studio Code
Download and Install VS Code:
Go to Visual Studio Code's website.
Download and install the appropriate version for your operating system.

Install Essential Extensions:
Open VS Code.
Go to the Extensions view by clicking the Extensions icon or pressing Ctrl+Shift+X.
Search for and install the following extensions:
Python
Docker
Prettier - Code Formatter
GitLens
ESLint

Configure VS Code:
Open settings (Ctrl+,).
Set preferences such as theme, font size, and editor format on save.
Setting Up Docker

Download and Install Docker:
Go to Docker's website.
Download and install Docker Desktop for your operating system.

Verify Docker Installation:
docker --version

Basic Docker Commands:
Pull an image: docker pull python:3.8
Run a container: docker run -it --name mypythoncontainer python:3.8
Setting Up Virtual Machines with VirtualBox

Download and Install VirtualBox:
Go to VirtualBox's website.
Download and install the appropriate version for your operating system.

Create a Virtual Machine:
Open VirtualBox and click New.
Follow the prompts to create a new VM, specifying the OS type, memory size, and virtual hard disk settings.

Install an OS on the VM:
Start the VM and select the installation media (ISO file).
Follow the OS installation steps.

Exploring Extensions and Plugins
Visual Studio Code
Python: Adds support for Python programming.
Docker: Tools for Docker containers.
Prettier - Code Formatter: Code formatting.
GitLens: Enhances Git capabilities.
ESLint: Integrates ESLint JavaScript.

PyCharm
Docker: Adds Docker support.
Markdown: Support for Markdown files.
IdeaVim: Vim emulation.
Database Tools and SQL: Enhanced database management.
Git Integration: Built-in Git support.

Docker
Portainer: Management UI for Docker environments.
Docker Compose: Define and run multi-container applications.
Docker App: Package, install, and share Docker applications.

Troubleshooting
Python Path Issues:
Ensure Python is added to your PATH.
Verify by running:
python --version

Virtual Environment Activation Issues:
Ensure you are using the correct command for your OS.
Verify the environment path is correct.

VS Code Extensions Not Working:
Check for updates and reinstall the extension.
Restart VS Code.

Docker Daemon Not Running:
Ensure Docker Desktop is running.
Verify Docker service status: sudo systemctl status docker

VirtualBox VM Issues:
Check VM settings for correct resource allocation.
Ensure your system supports virtualization and it is enabled in BIOS

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
