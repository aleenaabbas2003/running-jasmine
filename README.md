Setting Up WSL2

To set up WSL2, you need to be running Windows 10 version 2004 or higher (Build 19041 or higher) or Windows 11. If you are using an older version, check this webpage or refer to the guide for Docker Toolbox in section 2.1.2.

1. Open Command Prompt as Administrator:
   - Right-click on 'Command Prompt' and select 'Run as administrator' to launch it.

2. Install WSL:
   - In the Command Prompt, enter and run the following command: `wsl --install`.

3. Access Your Linux Distribution:
   - After installation, you’ll have a Linux distribution available via WSL, with Ubuntu being the default. Open the Start menu, search for "Ubuntu," and run it to access the Linux shell.

The first time you launch the newly installed WSL Linux distribution, a console window will open. You’ll need to wait for files to decompress and be stored on your machine. Future launches should be quick, taking less than a second. You will also need to set up a username and password for Linux, similar to your Windows account credentials.
