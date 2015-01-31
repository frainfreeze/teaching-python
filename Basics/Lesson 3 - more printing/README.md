# Lesson 3: more printing
Open main.py found inside this same directory in your favorite editor.

Strings
----
Every time you put "" (double-quotes) around a piece of text you have been making a string.
You can print strings, save strings to files, send strings to web servers,
and many other usefull things.
Python knows you want something to be a string when you put either
" (double-quotes) or ' (single-quotes) around the text.
The triple quotes can be used to span the string across multiple lines.
For example, all the following are legal:

```python
word = 'word'
sentence = "This is a sentence."
paragraph = """This is a paragraph.
It is made up of multiple lines and sentences."""
```

Strings may contain the format characters you have discovered so far.
You simply put the formatted variables in the string, and then a % (percent) character,
followed by the variable. The only catch is that if you want multiple formats in your
string to print multiple variables, you need to put them inside ( ) (parenthesis)
separated by , (commas). It's as if you were telling me to buy you a list of items
from the store and you said, "I want milk, eggs, bread, and soup."
Only as a programmer we say, "(milk, eggs, bread, soup)."

Important thing to remember: %r is for debugging and is "raw representation" while %s is for display.
