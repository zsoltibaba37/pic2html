# pic2html

This script creates an html file based on a part.txt and bmp files.

The name of the html file is the name of the current directory.

Part.txt is like a database. 

This script integrates part.txt lines and bmp files into html code.

#### Installation

You do not have to install it.

#### Files

pic2html

pic2html_all_folder

#### How to execute the script

```sh
$ chmod +x pic2html
$ sudo cp -p pic2html /usr/local/bin/ && sudo chown root:root /usr/local/bin/*
$ cd <working_folder>
$ pic2html
```

# pic2html_all_folder

The pic2html now embedded in the code.

The difference is that it runs in all subdirectories. This script use "folder.txt".

The "S" character is the separator. Find the dxf file name after the "S" character.

Before you start the script, create the "folder.txt" file, based on the example. 

#### How to execute the script

```sh
$ chmod +x pic2html_all_folder
$ sudo cp -p pic2html_all_folder /usr/local/bin/ && sudo chown root:root /usr/local/bin/*
$ cd <working_folder>
$ pic2html_all_folder

```

#### Example

In this example, there are two folders. The ```012345678``` and the ```0123456789```.

```sh
$ ll
összesen 8,0K
-rw-rw-r-- 1 user users 1,4K júl   20 13:30 folder.txt
drwxrwxr-x 3 user users 4,0K júl    6 10:11 bmp

```
You can see that the name of the html file is the same as the directory name.

#### Image example

<p align="center">
<img src="bmp/AM_BV_lv8_10_1234_1.BMP" width="20%">
<div align="center"><i>The first part example picture.</i></div>
</p>

