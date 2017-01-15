# Terminal Exercises

Please complete the following problems in terminal. 

## Explore the dotz

Go home. (NOTE: what does that mean? How does one end up at the **home** folder?).

List **all** the files in this folder - name all the DOT files (files that start with a dot) in this folder. How many do you have?

## Dig deeper

Pick one of your dot files. In terminal, display the file contents.

## Make a todo list

I bet there's stuff to do. (There's also stuff to do). In terminal, create an empty file called **todo.txt**

## JK, we're not about that life

LOL, this isn't a life management class. In terminal, delete the file you just created. This **is** a webdevelopment class tho. Create a file called **index.html**. Stick it in your desktop folder tho.

## Write some HTML

In terminal, with one command, fill your newly created **index.html** with this:

```html
<!doctype html>
<html>
  <head></head>
  <body></body>
</html>
```

**NOTE**: you might need **[this](http://unix.stackexchange.com/a/77278)**.

## Make folder structure

Build the basic structure for a website. You do this via the file system every time you create a new website. This time though, all actions must be done via terminal.

A typical website looks like this:

```
myWebSite/
  assets/
  styles/
    main.css
  index.html
```

Using terminal, create the folder structure displayed above. 

## Cat GIFs tho

A site isn't complete without gifs! Go to [Giphy.com](http://giphy.com/).

Find a gif that you like. Grab the **image address**, and in terminal, download and save it to your **assets/** folder in **myWebSite/**.

(**HINT**: you will need to use **curl**, try typing in **man curl** or googling around for **download file with curl**)

## Copy folder structures

While we can do the steps above for every website we build, it might be a lot easier to just copy and paste that above folder over and over again.

Using the terminal, copy the **entire** myWebsite folder contents to a new folder, called **myNextSite**.

Do this two more times, naming the folders **myNextSite2** and **myNextSite3**.

## Move folders around

Create a new folder called **websites**.

Move your **myNextSite2** into your **websites** folder. 
Move your **myNextSite3** into your **websites** folder.

## Display all the files

Without cd'ing into it, list *every* *single* *file* that exists in **website** directory.

## Find all CSS files in folder: CHALLENGE

With one line, list all the *.css* files that exist in **website** directory

## Go on an adventure; SPOILER: you make it back safely

First, make note of where you are right now by typing:

```bash
pwd
```

If you want, you can copy and paste the output and save it somewhere. You **will** need this later.

Then, type this:

```bash
cd ~
```

Where are you now? How can you tell?

Now, go back to where you were at the beginning of the problem. Is it possible to do this one command? 
