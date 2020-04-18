# SQLite安装指南



# SQLite安装
SQLite的一个重要特性是零配置，这意味着不需要复杂的安装和管理。本文将介绍在Windows上的安装设置。

## 在Windows上安装SQLite
- 请访问SQLite下载页面，从Windows区下载预编译的二进制文件。
- 您需要下载**sqlite-tools-win32-*.zip**和**sqlite-dllwin32-*.zip**压缩文件。
- 创建文件夹C:\sqlite，并在此文件夹下解压上面两个压缩文件，将得到**sqlite3.def**、**sqlite3.dll**和**sqlite3.exe**文件。
- 添加C:\sqlite到PATH 环境变量，最后在命令提示符下，使用sqlite3 命令，将显示如下结果。

```C
C:\sqlite3
SQLite version 3.31.1 2020-04-18 11:53:05
Enter ".help" for instructions
Enter SQL statements terminated with a ";"
sqlite>
```







# Installation Guide of SQLite



# SQLite Installation
An important feature of SQLite is zero configuration, which means that no complex installation and administration is required. This document describes the installation of SQLite on Windows:

## SQLite on Windows
- Visit the SQLite download page, download the precompiled binary file from Windows area.
- Download two zip files **sqlite - tools - win32 - *. zip** and **sqlite dllwin32-*. zip**.
- Create the folder C: \ sqlite and extract the above two zip files under this folder, will get **sqlite3. def**, **sqlite3. dll** and **sqlite3. exe**.
- Add the C: \ sqlite to the PATH environment variables, finally at the command prompt, run sqlite3 command, will show the following message:

```C
C:\sqlite3
SQLite version 3.31.1 2020-04-18 11:53:05
Enter ".help" for instructions
Enter SQL statements terminated with a ";"
sqlite>
```