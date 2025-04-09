
```markdown
# RetroArch Auto-Installer and Configuration Script

This script automates the installation, configuration, and management of [RetroArch](https://www.retroarch.com/), a powerful frontend for emulators and game engines. It supports multiple package managers and provides options for minimal installation, core-only updates, or full uninstallation.

## Features

- **Easy Installation**: Installs RetroArch and its dependencies automatically.
- **Configuration Management**: Sets up directories for ROMs, cores, saves, and states.
- **Core Installation**: Installs common emulator cores based on your package manager.
- **Controller Detection**: Automatically detects and configures connected game controllers.
- **Custom Configuration**: Creates or updates RetroArch configuration with optimized defaults.
- **Desktop Shortcut**: Optionally creates a desktop shortcut.
- **Uninstallation**: Supports full uninstallation, including optional removal of configuration and ROM files.
- **Logging**: Generates a log file for debugging and reference.

## Requirements

- **Root Privileges**: This script requires `sudo` or root access to install packages and configure directories.
- **Supported Package Managers**: The script supports `apt`, `dnf`, `yum`, and `pacman`.

## Installation Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/elithaxxor/ROM-Downloader---Web-CLI.git
   cd ROM-Downloader---Web-CLI/CLI
   ```

2. Make the script executable:
   ```bash
   chmod +x _download.sh
   ```

3. Run the script:
   ```bash
   sudo ./_download.sh
   ```

4. Follow the on-screen prompts to complete the installation.

### Command-Line Options

| Option                 | Description                                      |
|------------------------|--------------------------------------------------|
| `-h, --help`           | Displays help information.                       |
| `-v, --version`        | Shows the script version.                        |
| `-y, --yes`            | Runs in non-interactive mode, assumes "yes".     |
| `-q, --quiet`          | Minimizes output verbosity.                      |
| `-c, --cores-only`     | Installs or updates only the emulator cores.     |
| `-m, --minimal`        | Performs a minimal installation.                |
| `-u, --uninstall`      | Uninstalls RetroArch and optionally removes files.|

### Example Usage

- Default installation:
  ```bash
  sudo ./_download.sh
  ```

- Minimal non-interactive installation:
  ```bash
  sudo ./_download.sh --yes --minimal
  ```

- Install or update emulator cores only:
  ```bash
  sudo ./_download.sh --cores-only
  ```

- Uninstall RetroArch:
  ```bash
  sudo ./_download.sh --uninstall
  ```

## Warning

This script is provided **as is** for the benefit of the community. However, **abuse of this work** is strictly prohibited. Redistribution of this work for malicious purposes or any unauthorized use that violates laws or ethical guidelines is not tolerated.

By using this script, you agree to:
- Respect the intellectual property of others.
- Use BIOS files and ROMs only for systems you legally own.
- Avoid redistributing this script without proper credit.

Failure to adhere to these terms may result in legal consequences. The author assumes no responsibility for misuse.

## Disclaimer

This script is designed for educational purposes only. Ensure you comply with all local, national, and international laws regarding emulators, ROMs, and BIOS files. The author is not liable for any misuse or damage caused by this script.

---

For help or troubleshooting, please refer to the log file generated during the installation process.
```

This README provides a comprehensive explanation of the script, installation instructions, usage examples, and warnings about misuse. Let me know if you'd like any further modifications!
