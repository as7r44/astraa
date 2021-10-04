## Java Installation In Manjaro or Archlinux

## Options
1. OpenJDK package (which is free and GPL-licensed) - Support by Arch Linux and Manjaro
2. Oracle Java SE Development Kit package - Can be installed from the AUR

## Installation
### Install OpenJDK
`sudo pacman -S jre-openjdk-headless jre-openjdk jdk-openjdk openjdk-doc openjdk-src` - for current version

* Other versions
`sudo pacman -S jre[X]-openjdk-headless jre[X]-openjdk jdk[X]-openjdk openjdk[X]-doc openjdk[X]-src` - replace X with version number

### Install Oracle Java SE Development Kit
`yay -S jre jdk` - current version from AUR packages

* Other versions
`yay -S jre[X] jdk[X]` - replace X with version number

## Test Java Installation
`java -version`