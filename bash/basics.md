## The Basics
Navigating the command line is simple!
Try this out!

### Listing Directories

```bash
$ ls

Desktop/  Documents/  Downloads/  Music/  Pictures/  Public/  Templates/  Videos/

```
Whoa! You got a list of directories inside /home/ <username> / (Or you $HOME env variable)!
`ls` stands for *L*i*s*t Directories.


You can list files in a directory using `ls <directory name>`. It defaults to `ls <your/home/path>`, so that's why you see the contents of your home folder.

```bash
$ ls Documents

afile.txt 'Copy of Untitled Document.pdf'  wiki/
```

### Changing Directories
Listing directories may be cool, but once you go into them you can do a lot more cool stuff.
```bash
$ cd Downloads
```

It is that simple.


If you want to go to the directory above, you can use `cd ..`. 

In Unix, `..` means the above directory.

If you ever need to go to the $HOME or your home folder, and you need to do it quick, you can plainly just use `cd` and it will by default transport you there.


### Creating files by touching them and editing them with nanomized fingers
What if you need to create a file? Say, an empty file. Well, now you can using the power of `touch`!
```bash
$ touch testfile.txt
$ ls

Desktop/  Documents/  Downloads/  Music/  Pictures/  Public/  Templates/  Videos/  testfile.txt
```

Perfect! Now we need to edit it to add super cool stuff like: 
```
qfj p djfoajsv [sfL' JSOIAHFJO[ AOIJO[AHOLJAFO o ho dvhf dosajfa' fjoasdh f0 =4-939900f adf m
```

Nano the Editor is here for help!

Start up nano using
```bash
$ nano
```

A screen like this will show up:
![](https://leha-code.github.io/wiki/bash/assets/nano.png)


To edit a file with nano, pass it using the command line arguments:
```bash
$ nano testfile.txt
```


You can now edit whatever you want! YOU ARE UNSTOPPABLE!!!

![](https://leha-code.github.io/wiki/bash/assets/nano2.png)

