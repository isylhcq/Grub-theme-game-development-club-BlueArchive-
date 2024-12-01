# Grub-theme-game-development-club-BlueArchive
## 1.简介(Introduce)
- 1.The grub theme is about Game Development Club which from the game Blue Archive.
- 1.这是一个关于游戏开发部的grub主题，来自游戏《Blue Archive》
- 2.本项目参考了[GameDevClub-GRUB-Theme](https://github.com/Machillka/GameDevClub-GRUB-Theme)
- 3.[哔哩哔哩视频介绍](https://www.bilibili.com/video/BV18FzpYSEHQ/)
## 2.预览(Preview)
![image](background.png)
## 3.安装方式(Installation)
- 1.将主题文件解压至“/boot/grub/themes/ba”(注意:主题文件夹的名字不一定为"ba",您不一定需要解压至“/boot/grub/themes”,如果这样请自行修改接下来的操作！)
- 1.Extract the theme file to "/boot/grub/themes/ba" (Note: the name of the theme folder does not have to be "ba", you do not necessarily need to extract it to "/boot/grub/themes", if so, please modify the next operation by yourself!) )
- 2.在“/etc/default/grub”中添加"GRUB_THEME="/boot/grub/themes/ba/theme.txt"
- 2.Add "GRUB_THEME="/boot/grub/themes/ba/theme.txt" to /etc/default/grub".
```sh
sudo nano /etc/default/grub        #使用nanp编辑grub文件。如果没有nano用别的也行
GRUB_THEME="/boot/grub/themes/sleek/theme.txt" #添加以下内容
```
- 3.更新grub设置
- 3.Update the GRUB settings
```sh
sudo update-grub #Debian/Ubuntu
sudo grub-mkconfig -o /boot/grub/grub.cfg #Arch
```
## 4.许可(permission)
- 1.本项目遵循GPL-3.0 许可证
- 1.This project is licensed under the GPL-3.0 license
- 2.本项目所使用的美术素材来自网络由相关作者所有，IP形象归属《Blue Archive》
- 2.The art materials used in this project come from the Internet and are owned by the relevant authors.
- 3.以下为使用的美术素材来源：
- 3.The following are the sources of art materials used:

1.[背景图片](https://wallhaven.cc/w/28p296)
2.[tips的表情包](https://www.gamekee.com/ba/605400.html)
## 5.支持我(Support me)
[bilibili](https://www.bilibili.com/video/BV18FzpYSEHQ/)