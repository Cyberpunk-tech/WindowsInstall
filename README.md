# WindowsInstall


    Download the Windows ISO:
        Visit the Microsoft website (https://www.microsoft.com) and navigate to the Windows download section.
        Select the desired Windows version (e.g., Windows 10) and download the ISO file.

    Create a new Virtual Machine:
        Launch Oracle VirtualBox.
        Click on the "New" button to create a new virtual machine.
        Give it a name (e.g., "Windows VM") and select the appropriate Windows version from the drop-down menu.
        Assign an appropriate amount of memory (RAM) for the virtual machine.
        Create a new virtual hard disk and allocate the desired amount of storage space.

    Configure the Virtual Machine settings:
        Select the newly created virtual machine and click on the "Settings" button.
        In the "Storage" tab, click on the "Empty" CD/DVD drive.
        On the right side, click on the small disk icon and select the Windows ISO file you downloaded.
        Go to the "Network" tab and ensure that the "Adapter 1" is set to "NAT" for internet access.
        Adjust other settings as per your requirements.

    Install Windows:
        Start the virtual machine by selecting it and clicking on the "Start" button.
        The Windows installation process should begin. Follow the on-screen instructions to install Windows on the virtual machine.
        When prompted, create the first user account and set Alice as the administrator.
        Complete the installation process, including any additional settings and updates.

    Create a restricted user account (Bob):
        Log in to Windows with the administrator account (Alice).
        Open the "Settings" app by clicking on the Start menu and selecting the gear icon.
        In the Settings app, click on "Accounts" and then "Family & other users."
        Click on "Add someone else to this PC" under "Other users."
        Follow the prompts to create a new user account for Bob, making sure to select the "Standard User" option.
        Set a password for Bob if desired.

    Install and Configure Antivirus and Firewall:
        Download and install a reputable antivirus software from a trusted vendor (e.g., Avast, Avira, Bitdefender, etc.).
        Follow the installation wizard to set up the antivirus software.
        Once installed, open the antivirus program and configure it according to the manufacturer's instructions.
        Enable real-time scanning and automatic updates to keep the system protected.
        Similarly, configure the built-in Windows Firewall to provide basic network protection. You can access the firewall settings through the Windows Control Panel or the Windows Security app.

You have successfully installed Windows in Oracle VirtualBox, created two users (Alice and Bob), and set up an antivirus and a firewall. Remember to regularly update the antivirus software and apply Windows updates to ensure the system remains secure.
