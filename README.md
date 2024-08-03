### **Setting Up WSL2**:

To set up WSL2, you need to be running Windows 10 version 2004 or higher (Build 19041 or higher) or Windows 11. If you are using an older version, check this webpage or refer to the guide for Docker Toolbox in section 2.1.2.

1. Open Command Prompt as Administrator:
   - Right-click on 'Command Prompt' and select 'Run as administrator' to launch it.

2. Install WSL:
   - In the Command Prompt, enter and run the following command: `wsl --install`.

3. Access Your Linux Distribution:
   - After installation, you’ll have a Linux distribution available via WSL, with Ubuntu being the default. Open the Start menu, search for "Ubuntu," and run it to access the Linux shell.

The first time you launch the newly installed WSL Linux distribution, a console window will open. You’ll need to wait for files to decompress and be stored on your machine. Future launches should be quick, taking less than a second. You will also need to set up a username and password for Linux, similar to your Windows account credentials.

### **Configuring VS Code to Work with WSL2**:

1. Install WSL Extension in VS Code:
   - Open VS Code.
   - Go to Extensions (`Ctrl + Shift + X`).
   - Search for and install "WSL".

2. Connect to WSL:
   - Open command palette
   - Type `WSL: Connect to WSL in new window` and select it. This opens a new VS Code window in WSL.

4. Alternative Method:
   - Open the terminal in VS Code.
   - Click the dropdown next to the terminal type (e.g., "PowerShell").
   - Select `WSL` from the list.

### **Installing NVM in WSL**
I used the following link to install nvm: https://github.com/nvm-sh/nvm
1. Run the Installation Command:
   - Open your WSL terminal.
   - Run the following command to install NVM:
     ```bash
     curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash
     ```

2. Close and Reopen the Terminal:
   - Close your WSL terminal and open a new one to apply the changes.

3. Verify NVM Installation:
   - In the new terminal, run:
     ```bash
     command -v nvm
     ```
   - If NVM is installed correctly, this command should output `nvm`.
