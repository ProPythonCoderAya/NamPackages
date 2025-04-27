# NamPackages

NamPackages is a collection of `.neap` package files for the NebulaOS package manager. It serves as a repository for all the packages that are installed via the `nam` package manager on NebulaOS.

## Description

This repository contains various `.neap` packages that are used by the NebulaOS operating system. These packages can be installed and managed using the NebulaOS `nam` package manager.

## Contents

- **Packages/**: Directory containing `.neap` packages. These are compressed files used to install software or resources on NebulaOS.
- **README.md**: This file.
  
## Installation

To install these packages, you need [NebulaOS](https://github.com/ProPythonCoderAya/NebulaOS) installed virtually, with python, or an actual device. Follow these steps to install a package with `nam`

1. Open NebulaOS and log in

2. Run:

    ```bash
    nam install <package_name>
    ```
    Replace `<package_name>` with the name of the package you want to install.

## Usage

The `.neap` packages are like apps for NebulaOS. They will not work on other operating systems.

To view all available packages, use the following command:

```bash
nam list available
```

To view all installed packages, use the following command:

```bash
nam list
```
