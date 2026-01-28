# Stay Safe

Stay Safe is a simple tool that installs a recurring reminder on your computer to lock it. This helps raise awareness about the importance of securing unattended devices.

## How It Works

Once installed, Stay Safe will remind you to lock your computer by making a sound or sending a visual notification every hour.
## Install

Open the *Terminal* app on your macOS or Linux machine.

Paste the following command into the terminal:

```bash
curl -fsSL https://marcusmichaels.com/stay-safe/install | bash
```

## Uninstall

If you want to remove Stay Safe, simply run:

```bash
curl -fsSL https://marcusmichaels.com/stay-safe/uninstall | bash
```

## Notes

- This tool uses cron for scheduling reminders.

- The reminder will be a spoken alert on macOS (using say), and a visual notification on Linux (using notify-send).

- It’s completely safe to re-run the script. No system files are modified.

## Educational Purpose

This tool is designed to raise awareness of the security implications of leaving your computer unlocked and unattended, especially in shared or public spaces. It’s for educational use only.
