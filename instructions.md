Prerequisites
Windows OS

Claude Pro or Team Subscription (Required for usage, as shown at 02:59)

Step 1: Install Node.js
Timing: 00:00 – 00:39 Claude Code runs on Node.js. You must install this first if you don't have it.

00:00 Search for "Node js" on Google.

00:04 Go to the official website and download the LTS version (v24.12.0 in the video).

00:08 Run the downloaded .msi installer.

00:11 Follow the setup wizard:

Accept the license agreement (00:14).

Keep the default destination folder (00:17).

Keep default component settings.

00:20 Do not check "Automatically install the necessary tools..." (leave it blank).

Click Install and then Finish.

Step 2: Install Claude Code via Command Prompt
Timing: 00:40 – 01:03 Once Node is installed, you use its package manager (npm) to install Claude Code.

00:48 Open the Windows Start menu and search for cmd or "Command Prompt".

00:56 Type the following command and hit Enter:

Bash

npm install -g @anthropic-ai/claude-code
01:00 Wait for the installation to complete (it should take a few seconds).

Step 3: Install Git (Required for Version Control)
Timing: 01:04 – 02:15 Claude Code requires Git to manage your code changes.

01:04 Search for "git scm" on Google.

01:08 Go to the official site and click "Install for Windows".

01:20 Download the "Standalone Installer" (64-bit).

01:32 Run the installer and click "Next" through the standard options. The user in the video keeps almost all defaults:

01:41 Editor: Vim (default).

01:44 Default Branch: Let Git decide.

01:47 Path Environment: "Git from the command line and also from 3rd-party software" (Recommended).

01:50 SSH Executable: Use bundled OpenSSH.

01:51 HTTPS Backend: Use the native Windows Secure Channel library.

01:54 Line Endings: Checkout Windows-style, commit Unix-style line endings.

01:55 Terminal Emulator: Use MinTTY.

02:00 Click Install.

Step 4: Initialize and Authenticate
Timing: 02:16 – 03:45

02:16 Create a folder for your project (e.g., "test" on the Desktop).

02:35 Open PowerShell (or Command Prompt) and navigate to your folder (cd into the folder path).

02:41 Run the command:

Bash

claude
02:46 Theme Setup: Use the arrow keys to select a theme (e.g., Dark mode) and press Enter.

02:54 Login: Select "Claude account with subscription".

Note: A browser window will open. You must have a Pro or Team plan.

03:00 – 03:28 If you don't have a paid plan, you will be prompted to upgrade and pay.

03:33 Click Authorize to connect Claude Code to your account.

03:37 You can close the browser once you see "You're all set up".

03:41 Privacy Policy: Back in the terminal, read the data retention options and press Enter to accept (The user selects "Accept terms + Help improve Claude: ON" initially, or toggles it).

Optional: Privacy Settings Management
Timing: 03:49 – 04:04 If you want to opt out of training data after installing:

Go to Claude.ai in your browser.

Click your profile icon -> Settings.

Go to the Privacy tab.

Toggle OFF "Help improve Claude" to stop your data from being used for training models.