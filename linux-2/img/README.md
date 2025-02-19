# Installing Ubuntu as Windows Subsystem for Linux (WSL)

This guide provides steps for installing and setting up Ubuntu within Windows Subsystem for Linux (WSL).

## 1. Enabling WSL functionality

1. Open PowerShell as an administrator (right-click the Start button > Windows Terminal (Admin) or PowerShell (Admin)).

2. Enter the following command and press Enter:

   ```powershell
   wsl --install
   ```

3. Wait for the installation to complete and restart your computer if prompted.

If `wsl --install`, is not available, enable WSL manually::

1. Open **Control Panel** > **Programs** > **Turn Windows features on or off**.
2. Check the following options:
   - **Windows Subsystem for Linux**
   - **Virtual Machine Platform**
3. Click **OK** and restart your computer.

## 2. Installing Ubuntu

1. Open **Microsoft Store**.
2. Search for **Ubuntu**.
3. Select a version (Ubuntu 22.04 LTS is recommended).
4. Click **Get** (ili **Install**) and wait for the installation to complete.

## 3. Running and Initial Setup

1. Open **PowerShell** or **Command Prompt** and type in:

   ```powershell
   wsl
   ```

   ili

   ```powershell
   ubuntu
   ```

2. Wait for Ubuntu to start for the first time.
3. When prompted, enter a username and password.
4. Ubuntu is now installed and ready to use.

