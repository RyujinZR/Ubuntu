---
## Ubuntu on Termux Android

---
• Install Apps on Android
- [x] [Termux](https://apkcombo.com/id/termux/com.termux)
- [x] [Vnc Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)

## Installation

Copy and paste this command to Termux :
> pkg update && pkg upgrade

* Install Ubuntu
```
pkg install wget -y ; wget https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/install.sh ; chmod +x install.sh ; ./install.sh
```

* Start Ubuntu
```
ubuntu
```

* Stop Ubuntu
```
exit
```

* Remove Ubuntu
```
rm -rf ubuntu-fs
```

---
Basic commands Ubuntu
> apt update : Update list package.</br>
> apt upgrade : Upgrade package.</br>
> apt search (pkg) : Search package.</br>
> apt install (pkg) : Install package.</br>
> apt autoremove (pkg) : Delete package.</br>
> apt -h : Help all commands.

---
## Desktop Environment

on Ubuntu, run this command :
> apt update && apt upgrade

<details></br>
<summary><b><code>Install Desktop Xfce</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/RujinZR/Ubuntu/main/Images/xfce.jpg"</p>
</details>

```
apt install wget -y ; wget https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/Desktop/de-xfce.sh ; chmod +x de-xfce.sh ; ./de-xfce.sh
```

<details></br>
<summary><b><code>Install Desktop Lxde</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/Images/lxde.jpg"</p>
</details>

```
apt install wget -y ; wget https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/Desktop/de-lxde.sh ; chmod +x de-lxde.sh ; ./de-lxde.sh
```

<details></br>
<summary><b><code>Install Desktop Lxqt</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/Images/lxqt.jpg"</p>
</details>

```
apt install wget -y ; wget https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/Desktop/de-lxqt.sh ; chmod +x de-lxqt.sh ; ./de-lxqt.sh
```

<details></br>
<summary><b><code>Install Desktop Kde</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/Images/kde.jpg"</p>
</details>

```
apt install wget -y ; wget https://raw.githubusercontent.com/RyujinZR/Ubuntu/main/Desktop/de-kde.sh ; chmod +x de-kde.sh ; ./de-kde.sh
```

<details></br>
<summary><b><code>More List Desktop</code></b></summary>
Warning :</br>
It is not recommended to install because there are some problems.
</details>

[Click here,.](https://github.com/RyujinZR/Ubuntu/issues/10)

---
Feature
- [x] Fixed Sound
- [x] Access to Sdcard
- [x] Fixed Browser Crash
- [x] Install Applications [Click here,.](https://github.com/RyujinZR/Ubuntu/tree/main/Apps)

Visit problems now in : [Issues](https://github.com/RyujinZR/Ubuntu/issues)

---
## VNC Viewer

* Start VNC Server

on Ubuntu, run this command to start :
```
vnc-start
```

* Open Vnc Viewer

Add (+) VNC Client to connect, fill with :

Address
```
localhost:1
```

Name
```
Ubuntu Desktop
```

To disconnect VNC Client, click (X) on the right.

* Stop VNC Server

on Ubuntu, run this command to stop :
```
vnc-stop
```

</br>

---
<p align="center">Good Luck</p>

---
