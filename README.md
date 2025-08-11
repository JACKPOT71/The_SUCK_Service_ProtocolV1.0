
The S.U.C.K. Service Protocol 🚀

A FortKnight's Legacy by JACKPOT_ZB

Welcome to the "Secret Unlocked Circle of FortKnight's" (SUCK) Service Protocol! This PowerShell script is a powerful tool for advanced Windows users looking to configure their system for maximum performance and minimal background activity. It allows for the targeted disabling and re-enabling of system services, drivers, and critical system files.

Find us on Discord: https://discord.gg/xtgBxkpc2x

<img width="897" height="776" alt="suuu" src="https://github.com/user-attachments/assets/90faeb01-898c-4a9f-8e0e-24776d0b4096" />


⚠️ Important Warning

This script makes deep modifications to the Windows operating system. Disabling system services, drivers, or renaming system files can lead to instability, unexpected behavior, or the failure of critical system functions (such as Windows Update, Windows Defender, network features, etc.).

Use at your own risk!

It is strongly recommended to create a system backup or a system restore point before applying any major changes.

This script is intended for power users, gamers, and tweakers who understand the potential consequences of their actions.

✨ Features

Interactive Menu: A user-friendly, color-coded console for easy navigation.

Robust Administrator Check: Ensures the script is executed with the necessary privileges.

Modular Functions: Disable exactly what you don't need—from non-essential services to Windows Update and Bluetooth.

All-in-One Options: Disable or re-enable all offered tweaks with a single command.

Dangerous Operations: Special functions for renaming critical system files and disabling system drivers for ultimate tweaking.

Safe Revert Functions: Every "Disable" or "Rename" action has a corresponding "Reactivate" or "Revert" function to safely undo the changes.

Detailed Feedback: After each operation, you receive a summary of successful and failed actions.

Pro-Tips: In case of access errors, the script provides tips on how to resolve them (e.g., by using tools like NSudo or PowerRun).

🚀 How to Use

Download: Download the The_SUCK_Service_ProtocolV1.0.ps1 file.

Run as Administrator:

Right-click on the .ps1 file.

Select "Run with PowerShell". The script will automatically check for administrator rights.

Navigate the Menu: Choose the desired option from the menu and press ENTER to confirm.

Reboot: After most changes, a reboot is required for them to take full effect. The script will remind you.

For Maximum Control (in case of 'Access Denied' errors)

Some services or files are protected even from a standard Administrator account. To gain full control:

Run the script in Windows Safe Mode.

Use tools like NSudo or PowerRun to launch the script with TrustedInstaller privileges.

🛠️ Menu Options Overview

[A] DISABLE ALL: Executes all disabling scripts for a minimal system configuration.

[B] REACTIVATE ALL: Restores all services modified by this script to their default settings.

[C/D] UNNECESSARY services: Disables/Re-enables a long list of services that are often not required for basic operation.

[O/P] RENAME critical system files: (DANGEROUS) Renames system files related to services like Windows Defender and other monitoring tools. For experts only!

[S/T] DISABLE specific system drivers: (DANGEROUS) Disables specific ACPI and system drivers via the registry. For experts only!

[R] REBOOT PC NOW: Performs an immediate system restart.

[Q] QUIT PROGRAM: Exits the script.
