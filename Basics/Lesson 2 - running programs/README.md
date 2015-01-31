# Lesson 2: running programs

In this lesson you will learn how to run python programs.

You will need an text editor.
Notepad can do the job but it doesn't have nice syntax coloring.
You can grab Notepad++ , Sublime text or any other scripting editor you want.
For sake of simplicity and nice system integration I suggest you to use ![Atom editor](https://atom.io/).

To begin open your new editor and add a new blank file.
Copy and paste following code into your new file.
(Also If you actually cloned repository on your machine you can open main.py inside this directory)

```python
x = "There are %d types of people." % 10
binary = "binary"
do_not = "don't"
y = "Those who know %s and those who %s." % (binary, do_not)

print x
print y
```

Just for now you don't need to understand what the code does. Save your file as main.py
Now open your terminal / cmd again and type in python but instead of pressing enter
add one space and click and drag your saved file into the terminal.
You can now press enter to execute.

If everything went fine, your screen should look like following:
![success](http://i.hizliresim.com/L2a5pG.png)
