# CROSS v1
**Consensus-Ranking Organizational-Support System**

CROSS is developed as part of the Decision Support Systems II module for B.Sc. Computer Science & Information Systems module at the North-West University, Potchefstroom Campus. The goal of this project was to provide students with practical experience in any decision support model chosen by the student. It was expected of a student to develop a decision support application with a user friendly graphical user interface that demonstrates any decision support model chosen by the student that is at least too difficult for a second year computer science student to complete. This particular application was inspired by the original CROSS Excel system developed by Dr. Madjid Tavana who developed the system to aid NASA with their decision making in their projects. The original system developed by Dr. Tavana made use of specific criteria set by the people at NASA [2], this project generalize the idea to suit any type of projects.

**Support**
1. Linux<br /> 
This project was partly developed on a GNU/Linux system, more specifically Manjaro ArchLinux 17.03 - 17.05 KDE x86 64 running Manjaro kernel version 4.13. Linux systems are fully supported and CROSS is expected to run flawless on these systems, but as the GPL 3.0 license states it is not guaranteed. Any bugs and inconsistencies may be reported to the developers and maintainers of this application, at least one of the developers aims to maintain this project for UNIX-like systems. A shell script named install.sh is provided which one can run to install the application on a Linux system. The installation adds an application entry to the applications menu or better known as a desktop entry for the application. Since a Java .jar file is provided one can run the .jar executable on Linux systems if Java Runtime Environment 1.8 or higher is installed, very important: OpenJDK will not suffice! But it is more convenient to do the installation and to use the application as intended. One can run the install with the terminal command sudo sh install.sh, if a permission error is encountered first enter the following command before installation: sudo chmod +x install.sh, this will add executable permission to the install script. To be able to read this document a PDF reader is required such as Okular.

2. macOS<br />
This project was partly developed on a macOS 10.12.6 system and includes a dedicated .dmg installer for macOS. Run the .dmg installer and it will show you what to do to run the application on your mac. macOS will be supported as far as possible, the developer does not have his own macOS system but currently has access to one at the university. Since a Java .jar file is provided one can run the .jar executable on a macOS system if Java Runtime Environment 1.8 or higher is installed. To be able to read this document a PDF reader is required such as Skim.

3. Windows<br />
This application was never tested on a Windows platform and no support is provided for Windows systems. It is also very complicated to create an installer or portable .exe for Windows from a .jar executable and the little third party software that exists to make this process simpler is very expensive hence no Windows executable or installer. There is no guarantee that the developers will address any bugs or problems experienced on Windows systems but feedback is welcome just to keep record of what functions well. Since a Java .jar file is provided one can run the .jar executable on Windows systems if Java Runtime Environment 1.8 or higher is installed. To be able to read this document a PDF reader is required such as Adobe Reader.

**Acknowledgements**<br />
This project was developed and is being maintained with JetBrains IntelliJ IDEA Ultimate edition with a JetBrains student license. This documentation was compiled with LaTeX. GitHub is used to do version control over this project since it is easily integrable with JetBrains IntelliJ. The decision support knowledge used in this project was gained from Introduction to management science by Bernard Taylor and Prof. Hennie Kruger, the lecturer presenting the Decision Support Systems I and Decision Support Systems II honours modules at the University of the North-West: Potchefstroom Campus. The inspiration of the project came from Prof. Madjid Tavana as mentioned earlier. I would like to thank Elnette Moller for giving me permnission to reuse our effort we have put in, in our previous Cryptogen application for this assignment of mine.

**References:**

[1] Tavana, Madjid. 2003. CROSS: A Multicriteria Group-Decision-Making Model for Evaluating and Prioritizing Advanced-Technology Projects at NASA.

[2] Tavana, Madjid. 1996. CROSS: A GDSS for the Evaluation and Prioritization of Engineering Support Requests and Advanced Technology Projects at NASA.
