Setting Up Your Developer Environment 

Objective 

This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration. 

Tasks 

1. Select Your Operating System (OS) 

Step 1.1: Visit the Windows 11 download page: Windows 11 Download. 

Step 1.2: Click on "Download now" to get the installation media creation tool. Follow the instructions to create a bootable USB or DVD. 

Step 1.3: Install Windows 11 by booting from the USB or DVD and following the on-screen instructions. 

 

 

2. Install a Text Editor or Integrated Development Environment (IDE) 

Step 2.1: Visit the Visual Studio Code download page: Visual Studio Code Download. 

Step 2.2: Choose the appropriate version for your OS and download it. 

Step 2.3: Run the installer and follow the instructions to complete the installation. 

 

 

3. Set Up Version Control System 

Step 3.1: Visit the Git download page: Git Download. 

Step 3.2: Download and install Git by following the installer instructions. 

 

Step 3.3: Create a GitHub account at GitHub. 

 

Step 3.4: Open Git Bash and configure Git with your username and email: 

 

Step 3.5: Create a new repository on GitHub and clone it to your local machine: 

 

Step 3.6: Make your first commit: 

 

4. Install Necessary Programming Languages and Runtimes 

Step 4.1: Visit the Python download page: Python Download. 

Step 4.2: Download the latest version of Python and run the installer. Ensure you check the option to add Python to PATH. 

 

5. Install Package Managers 

Step 5.1: Open your terminal or command prompt. 

Step 5.2: Ensure pip is installed by running: 

 

If pip is not installed, you can install it by downloading get-pip.py from here and running: 

 

6. Configure a Database (MySQL) 

Step 6.1: Visit the MySQL download page: MySQL Installer. 

Step 6.2: Download the MySQL Installer and run it. 

Step 6.3: Follow the setup instructions to install MySQL Server and MySQL Workbench. 

 

7. Set Up Development Environments and Virtualization  

Step 7.1: Visit the Docker download page: Docker Desktop. 

Step 7.2: Download Docker Desktop and install it by following the instructions. 

8. Explore Extensions and Plugins 

Step 8.1: Open Visual Studio Code. 

Step 8.2: Click on the Extensions icon in the sidebar or press Ctrl+Shift+X. 

Step 8.3: Search for and install useful extensions like: 

Python 

GitLens 

Prettier - Code formatter 

ESLint 

 

8. challenges faced during setup and strategies employed to overcome them. 

1.Setting Up the Development Environment 

Problem: Difficulty in installing and configuring Python 

Solution: I uninstalled all the old and new python programs that were on my machine, then I reinstalled the newest version again. 

2. Understanding Version Control with Git 

Problem: Confusion with basic Git commands and version control concepts. 

Solution: Use resources like Git documentation and tutorials from websites like GitHub Learning Lab. Practice common commands such as git init, git add, git commit, and git push. 

3. Managing Dependencies 

Problem: Handling package dependencies and virtual environments in Python. 

Solution: Learn to use pip for package management and venv for creating virtual environments: 

 

4. Building and Structuring the Project 

Problem: I was uncertainty about project structure and file organization. 

Solution: I used a framework like Django or Flask which provides a standard project structure. 

5. Creating and configuring the GitHub Repository 

Problem: Confusion about how to create and initialize a GitHub repository. 

Solution: I created a new repository on my GitHub by clicking on the "New" button on my GitHub homepage. 

I named my repository 

I initialize the repository with a README file. 

Lastly, I cloned the repository to your local machine using: 

 

6. Initializing Git and Creating Configuration Files 

Problem: Difficulty in initializing Git and creating necessary configuration files like .gitignore. 

Solution: After cloning my repository, I navigated to the project directory and initialized Git 

7. Setting Up Project Structure 

Problem: Uncertainty about how to structure the e-commerce project. 

 

8. Configuring Virtual Environments 

Problem: Issues with setting up and activating virtual environments. 

Solution: Use the “Virtualenv” module to create a virtual environment 

 

9. Database Configuration 

Problem: Configuring the database settings for the project. 

Solution: Use SQLite for simplicity in a sample project. Configure the database in settings.py (for Django): 

 

10. Testing the Project 

Problem: Uncertainty about how to test the project. 

Solution: I wrote unit tests using Django’s built-in testing framework. I created a tests.py file in each app: 

e.g.) 

 

 

 

 

 

 

 

 

 

 

 

 

References 

Microsoft, 2024. Download Windows 11. [online] Available at: https://www.microsoft.com/software-download/windows11 [Accessed 14 June 2024]. 

Microsoft, 2024. Download Visual Studio Code. [online] Available at: https://code.visualstudio.com/Download [Accessed 14 June 2024]. 

GitHub, 2024. GitHub: Where the world builds software. [online] Available at: https://github.com [Accessed 14 June 2024]. 

Git, 2024. Git Downloads. [online] Available at: https://git-scm.com/downloads [Accessed 14 June 2024]. 

Python Software Foundation, 2024. Download Python. [online] Available at: https://www.python.org/downloads/ [Accessed 14 June 2024]. 

Oracle, 2024. MySQL Community Downloads. [online] Available at: https://dev.mysql.com/downloads/windows/installer/5.7.html [Accessed 14 June 2024]. 

Docker, 2024. Docker Desktop. [online] Available at: https://www.docker.com/products/docker-desktop [Accessed 14 June 2024]. 

 

 
