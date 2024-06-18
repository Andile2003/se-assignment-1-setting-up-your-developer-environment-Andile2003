[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15280694&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Steps on how to to download and install Windows 11

   Step 1: the most important part is to check the system requirements so that you can see if you have enough memory or space for windows to be downloaded and installed.

   Step 2: To download visit https://www.microsoft.com/software-download/windows11 then click "download now" below Windows 11 Installation Assistant![alt text](<windows11 screenshot-1.png>)

   Step 3: After installing the windows 11 installation assistant, open the downloaded file.![alt text](<downloaded windows 11.png>)
   Accept the license terms and take either between "Upgrade this PC now". Follow the installation instructions and your PC will restart many times.
   After completing these steps, Windows 11 should be installed on your PC.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Steps on how to download Visual Studio Code.

   Step 1: Go to the official download page on this link: https://code.visualstudio.com/Download. The page will show different types of Operating Systems which are, Windows, MacOs and Linux.![alt text](<VS _Code-1.png>)

   Step 2:On the right handside corner there is a "Download" button,click on it so that the download will begin.![alt text](<Download button for Visual Studio Code.png>)

   Step 3: When installing in windows if you are windows user once the Visual studio code is downloaded you should open the downloaded file so that the installing process will begin. Follow all the instructions to complete the installation.

   Step 4: After the installation the Visual Studio Code will appear on the file explorer you can launch it then ![alt text](<Visual studio file explorer ii.png>)

   Step 5: Click on the downloaded Visual Studio Code on the file explorer then open your Visual Studio Code after that it will be installed and launched to be used. Home page will appear.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

    Installing and configuring Git:

   Step 1: Download Git for windows![alt text](<Git download.png>) then click on the 64-bit but it depends on the PC you are using. 

   Step 2:After downloading go to the downloads then press the Git you have downloaded.![alt text](<Git after downloading.png>)

   Step 3: Follow all the prompt on the above page the Git will be installed. After the installation open a terminal and type the command "Git --version" to see the version of the Git you installed.

   Creating a GitHub account:

   Step 1: Visit the github download page, https://github.com the git ![alt text](<Github sign up page-1.png>)

   Step 2: Fillout the registration and put all your valid information and verify your email.

   Step 3: Initialize a git repository, open a command on git bash. Navigate your project directory if you don't have it create it and navigate in it. 

   Step 4: Initialize the git repository. Create a new file in your projrct directory.

   Step 5: Add the file use the 'git add' command, make the first commit using 'git commit'command to commit the staged file with a commit message. The git repisitory is initialized, added a file, and made the first commit.


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Installing Pyython:
  
  Step 1: Go to http://wwww.python.org then click on downloads and download the latest version of python! ![alt text](<python download.png>)
  
  Step 2: Double-click the downloaded .exe file.Check the box that indicates "Add Python to PATH"andClick "Install Now" and follow the instructions.

Step 3: Verify the installation by opening a command prompt. Write 'python --version' to ensure Python is installed correctly. ![alt text](<Python comand prompt.png>)

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Step 1: Make that python is installed and verify on the command prompt by writing 'python --version'.

   Step 2: Pip gets pre installed with Python, Verify the 'pip' installation by commanding 'pip --version'. 

   Step 3: If pip is not already installed, download 'get-pip.py' by running curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py.

   Step 4: Run the scripts by typing python get-pip.py.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Step 1: Visit the download page, https://dev.mysql.com/downloads/windows/installer/5.7.html click the first download button after clicking it don't sign up just click the 'No thanks, just start my download' ![alt text](<My sql download page.png>)

   Step 2: After the download go to the downloads run it to start the installation process.

   Step 3: Installer setup, The MySQL Installer will show instructions for the setup. Choose "Developer Default" or "Server only" options for a typical installation. You can customize installation options if needed.

   Step 4: Configuration, during installation, you may be prompted to configure MySQL settings such as root password, port number and more. Follow the instructions and set these options according to your preferences or leave them as default.

   Step 5: Once the installation completes successfully, you should see a confirmation message.

   Step 6: verify that MySQL has been installed correctly, you can try connecting to the MySQL server using the command line or MySQL Workbench.

   Step 7: Connect to MySQL server, Use the 'mysql' command-line client to connect to MySQL and run 'mysql -u root -p'. Enter your root password when prompted.

   Step 8: Launch MySQL Workbench, configure a new connection using the credentials set during installation.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

    Step 1: Install docker,  Firstly install Docker on your machine. Docker provides containers that encapsulate your application and its dependencies, ensuring consistency across different environments.

   Step 2: Create a 'Dockerfile' in the root of your project. This file specifies the environment your application needs to run. Adjust the FROM line and commands according to your specific application and its dependencies.

   Step 3: In the directory containing your 'Dockerfile', run: 'docker build -t my-node-app'.This command builds a Docker image named 'my-node-app' based on your 'Dockerfile'.

   Step 4: Once the image is built, you can run a container based on it: docker run -p 3000:3000 my-node-app. Reference (https://chatgpt.com/c/89d6f3ed-4889-4d69-9fac-f47c91084811)

   Virtual Machine Approach:

   Step 1: Choose a Virtualization Tool: Install a virtualization platform like VirtualBox, VMware, or Hyper-V.

   Step 2: Create a new virtual machine and configure its settings (CPU, memory, disk space) according to your project’s requirements.
   
   Step 3: Install an operating system suitable for your project on the virtual machine.
   
   Step 4: Install all necessary dependencies and tools within the virtual machine as you would on a physical machine. Reference (https://chatgpt.com/c/89d6f3ed-4889-4d69-9fac-f47c91084811)

   Benefits of using a virtual machine

   Isolation: Virtualization provides a way to isolate different applications and operating systems from each other on the same physical machine. This isolation prevents conflicts and ensures that one application or environment does not affect others, improving overall stability and security.
   
   Efficient Resource Utilization: Virtualization allows you to run multiple virtual machines or containers on a single physical server. This optimizes the use of hardware resources such as CPU, memory, and storage, leading to cost savings and increased efficiency compared to running each application on separate physical machines. Reference (https://chatgpt.com/c/89d6f3ed-4889-4d69-9fac-f47c91084811)

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Visual Studio Code (VS Code):
   
   Extensions Marketplace: VS Code has a vast marketplace for extensions. Some essential ones included.
   
   ESLint: Linting tool for JavaScript and TypeScript to catch errors and enforce coding styles.
   
   Prettier: Code formatter for various languages including JavaScript, TypeScript, HTML, CSS, etc., ensuring consistent code style.
   
   GitLens: Provides Git integration directly within the editor, showing Git blame information, history, and more.

   Sublime Text:
   
   Package Control: Sublime Text uses Package Control to manage extensions. Key packages include:
   
   SublimeLinter: Framework for linting code with support for various languages and linters.
   
   HTML/CSS/JS Prettify: Code formatter for HTML, CSS, and JavaScript.
   
   Git: Provides Git integration features within the editor.

   IntelliJ IDEA (Java development):
   
   Plugins: IntelliJ IDEA supports plugins via its marketplace. Useful plugins include:
   
   SonarLint: Finds and fixes bugs and quality issues in Java code.
   
   CheckStyle-IDEA: Ensures coding style compliance with CheckStyle.
   
   Git Integration: Built-in Git integration for version control.
   Refrence (https://chatgpt.com/c/89d6f3ed-4889-4d69-9fac-f47c91084811)



9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

    When doing this assignment had no obsticles I must say because I finished it without struggling. Even though I did not have all the screenshorts that were needed I made sure that I cover in writing and making a picture in writing. Some of the things that were needed to e installed I had them on my PC so I did not have any struggles. Some of them was the first time seeing them so I used an AI tool which I referenced where I was supposed to. This assignment made me learn about many things in technology since I am a beginner I learnt so much while doing it.

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
