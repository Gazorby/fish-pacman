# fish-pacman

Pacman abbreviations, ported from [here](https://github.com/zimfw/pacman)

## 🚀 Installation

Using [fisher](https://github.com/jorgebucaran/fisher)

```console
fisher add Gazorby/fish-pacman
```

## 🔧 Usage

### Build

  * `pacb` build package in the current directory, cleanup, and install.

### Install

  * `paci` install, sync, and upgrade packages.
  * `pacu` install, sync, and upgrade packages (forcibly refresh package list).
  * `pacU` install packages from pkg file.
  * `pacd` install all packages in current directory.

### Remove

  * `pacr` remove package and unneeded dependencies.
  * `pacrm` remove package, unneded dependencies, and configuration files.

### Query

  * `pacq` query package information from remote repository
  * `pacQ` query package information from local repository

### Search

  * `pacs` search for package in the remote repository
  * `pacS` search for package in the local repository

### Orphans

  * `pacol` list orphan packages
  * `pacor` remove all orphan packages

### Ownership

  * `pacown` list all files provided by a given package
  * `pacblame` show package(s) that own a specified file

## 📝 License

[MIT]()
