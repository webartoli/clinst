# clinst - Command Line Installer

Simple provisioning application cross platform to set-up all must have application with a single script that will be useful for:

 * OsX
 * Windows
 * Linux - apt based distros

In example:

```bash
clinst git
```
> will install git on your machine

## How is it works

This project is a simple wrapper/alias of platform specific software

 * Windows: chocolately + boxstarter
 * OsX: homebrew + cask
 * apt distros: apt-get
