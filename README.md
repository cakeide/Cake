## What is Cake?
Cake is a macOS, Terminal-based Python IDE. It is simple, straightforward and super lightweight (the total size is less than 3kb!) It has all the Python functionality you could ever imagine (as it's written in Python) and works with any version of Python 3. And you get all of that in one little easy-to-use, 100% integrated package. It's also free and open source and will stay that way forever.
### Getting Started
Before you do anything, make sure you have these installed:
- Python 3.6 or higher (make sure it's installed to the PATH)
- Git 2.2 or higher
Installation is extremely simple. First of all, just open Terminal and type
```sh
git clone https://github.com/donoru/cake
```
After that, navigate to the directory of the repository you just cloned and type
```sh
python3 Cake.py
```
And, if you've done it right, you should be greeted with this screen:
```
( Cake Python Development Enviroment )
Copyright ©2020 Spencer Reynolds
Enter Filename to Edit:
```
Now, just type the desired file to open and edit. If the file entered doesn't already exist, Cake will create that file and open it. Otherwise, Cake will open the file. Now, you can edit to your heart's content!
### Usage & Commands
To list all possible commands, simply type`:help`. Here are all of the commands and their uses described in more detail:
- `:save`- Writes all entered lines to the end of the current opened file
- `:svcls`- Executes the `:save` command, then counts down to 3 and exits Cake
- `:debug`- Starts at the beginning of the currently opened file and executes it, if Cake runs into any errors it returns them and 
