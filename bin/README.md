# Healthcare Facilities

## Contents

- [Usage](#usage)
  - [Prerequisites](#prerequisites)
  - [Miniconda Installation](#miniconda-installation)
  - [Uninstalling Miniconda](#uninstalling-miniconda)

## Usage

### Prerequisites

- A Linux-based operating system
- `wget` installed on your system

### Miniconda Installation

This script automates the installation of Miniconda on a Linux system. It downloads the Miniconda installer, installs it, and sets up the environment.

To learn more about Miniconda, visit the official documentation by clicking on this link: [Miniconda Documentation](https://docs.anaconda.com/miniconda/)

Instructions:

1. Navigate to the `bin` directory:

```bash
cd bin
```

2. Make the script executable:

```bash
chmod +x install_miniconda.sh
```

3. Run the script:

```bash
./install_miniconda.sh
```

### Uninstalling miniconda

To uninstall Miniconda, run the following command:

```bash
rm -rf ~/miniconda
```

Note: The above commands will remove miniconda and all its associated files from your system. Use with caution.
