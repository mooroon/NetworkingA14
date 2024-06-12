# Basics

## cd

cd stands for Change Directory and it is used to navgigate your terminal.
To use it, type it into your terminal, hit space, and then enter the path to the directory you want to go to.

```cmd
$cd /home/seconddirectory
```

```cmd
$cd -
$cd --
```
cd - goes to the previous directory 
and cd -- goes back to the root directory

## cat 
cat is short for concatenation. It can be used for a lot of things including printing the contents of files which is useful for this task.

to use it type it into your terminal, hit space and then enter the desired file.

```cmd
$cat file.txt
```

### pwd

if you ever get lost use pwd to see where you are.

```cmd
$pwd
/home/seconddirectory/lost
```

### ls

to see the files and directories stored in the directory you're currently in use ls.

```cmd
$ls
file1.txt file2.txt file3.txt
```

to see hidden files use -a

```cmd
ls -a
.file4.txt .file5.txt file1.txt file2.txt file3.txt
```
to see all files including hidden files formatted with permissions displayed use -la
```cmd
ls -la
```
