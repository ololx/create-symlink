# create symlink

Create Symlink is a simple mac Automator workflow which provides a GUI for the symbolic links creation on macOS.

[![status](https://img.shields.io/badge/status-completed-inactive?style=flat-square)](BADGES_GUIDE.md#status) [![version](https://img.shields.io/badge/version-1.0.0-informational?style=flat-square)](BADGES_GUIDE.md@version) [![build](https://img.shields.io/badge/build-passing-success?style=flat-square)](https://github.com/ololx/create-symlink) [![oss lifecycle](https://img.shields.io/badge/oss_lifecycle-maintenance-important?style=flat-square)](BADGES_GUIDE.md#oss-lifecycle) [![maintenance](https://img.shields.io/badge/maintenance-yes-informational?style=flat-square)](BADGES_GUIDE.md#maintenance)  [![latest release date](https://img.shields.io/badge/latest_release_date-April_01,_2020-informational?style=flat-square)](BADGES_GUIDE.md#release-date) [![last commit](https://img.shields.io/badge/last_commit-May_14,_2021-informational?style=flat-square)](BADGES_GUIDE.md#commit-date)

[![license](https://img.shields.io/badge/license-MIT-informational?style=flat-square)](LICENSE) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](code_of_conduct.md)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fololx%2Fcreate-symlink.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fololx%2Fcreate-symlink?ref=badge_shield)

[![platform](https://img.shields.io/badge/platform-macOS_10.11+-important?style=flat-square)](https://en.wikipedia.org/wiki/Computing_platform)

---

## 📇 Table of Contents

- [About](#about)
- [Demo](#demo)
- [Features](#feature)
- [Getting Started](#getting-started)
- [Built With](#built-with)
- [Contributing](#contributing)
- [Code of Conduct](#code-of-conduct)
- [Versioning](#versioning)
- [Authors](#authors)
- [Licensing](#licensing)

##  📖 About

For me the symbolic links is a useful feature of macOS. They can be especially useful when it's needed to store the `Documents` folder on a hard drive or SD card, but on the ssd to create a just link to this folder.
Create Symlink is a mac Automator workflow which allows to create symbolic links of selected folders or files. It can be added to the "Services” menu and called by right-clicking on selected folders or files and selecting `Services --> create symlink` from the context menu.

**There is an alternative project with similar functionality, but a different implementation - a `Finder extension`.; for more details see https://github.com/ololx/quick-symlink.**

## 📸 Demo

Demo shows how it works.

![create symlink](resources/demo/demo-create-symlink.gif)

## 🎚 Features

- Create a symbolic links in a several clicks via the context menu instead of the terminal promt;
- Create a symbolic links for the selected files or folders;
- Save a symbolic links to the selected directory.

### To Do

- ~~For more information on an upcoming development, please read the todo list.~~ No plans.

### Changelog

- For more information on a releases, a features and a changes, please read the [changelog](CHANGELOG.md) notes.

## 🚦 Getting Started

These instructions allow to get a copy of this project and run it on a local machine.

### Prerequisites

Before using it, make sure that follows software are installed on the local machine:

- **[macOS](https://www.apple.com/ru/macos/what-is/)** - the operating system under which the process is executing;
- **[Automator](https://support.apple.com/guide/automator/welcome/mac)** - the program for operations automation.

If any of the listed programs is not installed, then it can be installed by instruction as described below.

1. #### macOS
    - Install macOS by [this](https://support.apple.com/ht201372) instruction.

2. #### Automator

    - Automator is included on macOS. Just install the macOS.

### Installing

In order to install it is quite simple to:

1. Clone this repository;

2. Go to the directory with this tool (optionally):

   - via Finder;
   - via Terminal prompt; 

   ```bash
   cd /{path to dir with tool}/create-symlink
   ```

3. Install the tool in macOS (optionally):

   - via double-click on _create symlink.workflow_;
   - via Terminal prompt;

   ```bash
   open create\ symlink.workflow
   ```
4. Push the `Install` button.

### Cloning

For the cloning this repository to a local machine, just use the follows link:

```bash
https://github.com/ololx/create-symlink
```

### Using

For use it is required to:

1. Select folders or files for which a symbolic link is needed;
2. Call the context menu by right-clicking on selected;
3. Select menu item `services --> create symlink`;
4. Select a destination folder on the choosing dialog and push the `Select` button.

## 🛠 Built With

- **[Automator](https://support.apple.com/guide/automator/welcome/mac)** - the program for operations automation.

## 🎉 Contributing

If you want to contribute this project - you are welcome and have fun.
Please visit the [contributing](CONTRIBUTING.md) section for details on this code of conduct, and the process for submitting pull requests.

## 📝 Code of Conduct

In order to ensure that all is welcoming, please review and abide by the [code of conduct](CODE_OF_CONDUCT.md).

## 🗒 Versioning

For the versioning is used [Semantic Versioning](http://semver.org/). For the versions available, see the [changelog](CHANGELOG.md) or the tags on this repository.

## ©️ Authors

* **Alexander A. Kropotin** - *Initial work* - [ololx](https://github.com/ololx).

## 🔏 Licensing

This project is licensed under the MIT license - see the [lisence](LICENSE) document for details.


[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fololx%2Fcreate-symlink.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fololx%2Fcreate-symlink?ref=badge_large)