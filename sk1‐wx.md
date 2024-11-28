[Welcome to the sk1-wx wiki!
](https://github.com/aibolem/sk1-wx/wiki)

releases: https://github.com/aibolem/sk1-wx/releases/tag/2.0

https://excalidraw.com/  

![image](https://github.com/user-attachments/assets/6f86348a-a07a-4846-8cac-57441dcc0e8e)


or on ВЕБჼ СТРАННИ©А *Иgорь Новuков*: https://sk1project.net/sk1/download/

CPACNჼ°: *d'PogИN h²о'в'ико'в*  [Игорь Новиков]

разъяснение по теме "d'Род_ИN_Å", кჼ транслит + кჼ кириллица + кჼ ситква

___
___

<html>
<body>
<!--StartFragment--><h2 style="box-sizing: border-box; padding: 0px; margin: 0px 0px 12px; transition: 0.5s ease-in-out; font-weight: normal; letter-spacing: 1px; background-image: -webkit-repeating-radial-gradient(left center, rgb(0, 0, 0), rgba(0, 0, 0, 0) 1px, transparent 100%, transparent 2px, transparent 100%, transparent 7px, transparent 100%); background-repeat: repeat-x; background-position: center bottom; background-size: 5px 1px; font-size: 26px; color: rgb(55, 55, 55); font-family: Ubuntu; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: normal; background-color: rgb(255, 255, 255); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial;"><font style="box-sizing: border-box; padding: 0px; margin: 0px; transition: 0.5s ease-in-out; vertical-align: inherit;"><font style="box-sizing: border-box; padding: 0px; margin: 0px; transition: 0.5s ease-in-out; vertical-align: inherit;">Исходный код tarball</font></font></h2>
  | sk1-2.0rc5.tar.gz
-- | --


<!--EndFragment-->
</body>
</html>

# sK1 2.0

[![Build Status](https://app.travis-ci.com/sk1project/sk1-wx.svg?branch=master)](https://app.travis-ci.com/sk1project/sk1-wx) ![platform](https://img.shields.io/badge/platform-Linux-blue.svg) ![platform](https://img.shields.io/badge/platform-Windows-blue.svg) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

<center>

![sK1 2.0 under Ubuntu 14.04](./docs/images/sk1_2_0.png "sK1 2.0 under Ubuntu 14.04")

</center>

sK1 2.0 is a cross-platform open source vector graphics editor similar to CorelDRAW, 
Adobe Illustrator, or Freehand. sK1 is oriented for prepress industry, 
so it works with CMYK color space and produces CMYK-based PDF and PS output.

sK1 Project (https://sk1project.net)

### How to install: 

---

* to build package:   `python setup.py build`
* to install package:   `python setup.py install`
* to remove installation: `python setup.py uninstall`

---

* to create source distribution:   `python setup.py sdist`

---

* to create binary RPM distribution:  `python setup.py bdist_rpm`
* to create binary DEB distribution:  `python setup.py bdist_deb`

---

* help on available distribution formats: `python setup.py bdist --help-formats`

---


## DETAILS

If you wish testing sK1 you have two installation ways. 
First option is a distutils install with commands:
```
python setup.py build
python setup.py install
```
But this way is not recommended. The most preferred option is a package 
installation (deb or rpm). You can create package using command:
```
python setup.py bdist_deb (for Ubuntu|Mint|Debian etc.)
python setup.py bdist_rpm (for Fedora|OpenSuse|Mageia etc.)
```
By installing the package you have full control over all the installed files 
and can easily remove them from the system (it's important for application
preview).

### Dependencies

Please note that application uses Python 2.x version. So Python interpreter
and python based dependencies should be for 2.x, but not 3.x

For successful build either distutils or deb|rpm package you need installing
some development packages. We describe dev-packages for Ubuntu|Debian, but for
other distros they have similar names. So, you need:
```
git
gettext
curl
libcairo2-dev
liblcms2-dev
libmagickwand-dev
libpango1.0-dev
python-dev
python-cairo-dev
```

To run application you need installing also:
```
python-wxgtk3.0
python-pil 
python-reportlab
python-cairo
python-cups
```

Also the project depends on several subprojects: `uniconvertor`, `wal`, `build-utils`. You don't need to clone these sources manualy because `setup.py` does it for you automatically.

Исходный код tarball
Исходный код tarball	[sk1-2.0rc5.tar.gz](https://downloads.sk1project.net/sk1/sk1-2.0rc5.tar.gz)

Окна
MS Windows
MSI-установщик	[sk1-2.0rc5-win64_headless.msi](https://downloads.sk1project.net/sk1/MS_Windows/sk1-2.0rc5-win64_headless.msi)
MSI-установщик	[sk1-2.0rc5-win32_headless.msi](https://downloads.sk1project.net/sk1/MS_Windows/sk1-2.0rc5-win32_headless.msi)
портативный архив	[sk1-2.0rc5-win64-portable.zip](https://downloads.sk1project.net/sk1/MS_Windows/sk1-2.0rc5-win64-portable.zip)
портативный архив	[sk1-2.0rc5-win32-portable.zip](https://downloads.sk1project.net/sk1/MS_Windows/sk1-2.0rc5-win32-portable.zip)
Примечание: эти бинарные файлы предназначены для Windows 7 или новее. Для портативной версии вам просто нужно распаковать ее и запустить sk1.exe

Убунту Линукс
Убунту Линукс
DEB-пакет	[python-sk1-2.0rc5_ubuntu_20.04_amd64.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_20.04_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_19.10_amd64.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_19.10_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_19.04_amd64.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_19.04_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_18.10_amd64.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_18.10_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_18.04_amd64.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_18.04_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_16.04_amd64.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_16.04_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_16.04_i386.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_16.04_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_14.04_amd64.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_14.04_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_ubuntu_14.04_i386.deb](https://downloads.sk1project.net/sk1/Ubuntu/python-sk1-2.0rc5_ubuntu_14.04_i386.deb)


LinuxMint
Линукс Минт
DEB-пакет	[python-sk1-2.0rc5_mint_20_amd64.deb](https://downloads.sk1project.net/sk1/LinuxMint/python-sk1-2.0rc5_mint_20_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mint_19_amd64.deb](https://downloads.sk1project.net/sk1/LinuxMint/python-sk1-2.0rc5_mint_19_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mint_18_amd64.deb](https://downloads.sk1project.net/sk1/LinuxMint/python-sk1-2.0rc5_mint_18_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mint_18_i386.deb](https://downloads.sk1project.net/sk1/LinuxMint/python-sk1-2.0rc5_mint_18_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_mint_17_amd64.deb](https://downloads.sk1project.net/sk1/LinuxMint/python-sk1-2.0rc5_mint_17_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mint_17_i386.deb](https://downloads.sk1project.net/sk1/LinuxMint/python-sk1-2.0rc5_mint_17_i386.deb)

Дебиан Линукс
Дебиан
DEB-пакет	[python-sk1-2.0rc5_debian_10_amd64.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_10_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_debian_10_i386.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_10_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_debian_9_amd64.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_9_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_debian_9_i386.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_9_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_debian_8_amd64.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_8_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_debian_8_i386.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_8_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_debian_7_amd64.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_7_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_debian_7_i386.deb](https://downloads.sk1project.net/sk1/Debian/python-sk1-2.0rc5_debian_7_i386.deb)

Элементарная ОС
элементарная ОС
DEB-пакет	[python-sk1-2.0rc5_elementary5.0_amd64.deb](https://downloads.sk1project.net/sk1/elementaryOS/python-sk1-2.0rc5_elementary5.0_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_elementary0.4_amd64.deb](https://downloads.sk1project.net/sk1/elementaryOS/python-sk1-2.0rc5_elementary0.4_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_elementary0.3_amd64.deb](https://downloads.sk1project.net/sk1/elementaryOS/python-sk1-2.0rc5_elementary0.3_amd64.deb)

Арч Линукс
Arch Linux (Manjaro, Antergos и т. д.)
	[sk1-2.0rc5.archlinux.pkgbuild.zip](https://downloads.sk1project.net/sk1/ArchLinux/sk1-2.0rc5.archlinux.pkgbuild.zip)

Арч Линукс
MX-линукс
DEB-пакет	[python-sk1-2.0rc5_mx19_amd64.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx19_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mx19_i386.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx19_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_mx18_amd64.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx18_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mx18_i386.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx18_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_mx17_amd64.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx17_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mx17_i386.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx17_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_mx16_amd64.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx16_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mx16_i386.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx16_i386.deb)
DEB-пакет	[python-sk1-2.0rc5_mx15_amd64.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx15_amd64.deb)
DEB-пакет	[python-sk1-2.0rc5_mx15_i386.deb](https://downloads.sk1project.net/sk1/MX_Linux/python-sk1-2.0rc5_mx15_i386.deb)

Fedora Linux
Федора
Пакет RPM	[sk1-2.0rc5-0.fc31.x86_64.rpm](https://downloads.sk1project.net/sk1/Fedora/sk1-2.0rc5-0.fc31.x86_64.rpm)
Пакет RPM	[sk1-2.0rc5-0.fc30.x86_64.rpm](https://downloads.sk1project.net/sk1/Fedora/sk1-2.0rc5-0.fc30.x86_64.rpm)
Пакет RPM	[sk1-2.0rc5-0.fc29.x86_64.rpm](https://downloads.sk1project.net/sk1/Fedora/sk1-2.0rc5-0.fc29.x86_64.rpm)
Пакет RPM	[sk1-2.0rc5-0.fc28.x86_64.rpm](https://downloads.sk1project.net/sk1/Fedora/sk1-2.0rc5-0.fc28.x86_64.rpm)
Пакет RPM	[sk1-2.0rc5-0.fc27.x86_64.rpm](https://downloads.sk1project.net/sk1/Fedora/sk1-2.0rc5-0.fc27.x86_64.rpm)

SuSE Linux
OpenSUSE
Пакет RPM	[sk1-2.0rc5-0.opensuse15.0.x86_64.rpm](https://downloads.sk1project.net/sk1/OpenSuse/sk1-2.0rc5-0.opensuse15.0.x86_64.rpm)
Пакет RPM	[sk1-2.0rc5-0.opensuse42.3.x86_64.rpm](https://downloads.sk1project.net/sk1/OpenSuse/sk1-2.0rc5-0.opensuse42.3.x86_64.rpm)

https://sk1project.net/color-picker/developer-resources/

и.в.