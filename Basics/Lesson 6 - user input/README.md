# Lesson 6: user input
```python
print "What's your name?"
name = raw_input()

print 'hi %s' % (name)
```
When you execute the script above it will expect your input,
you can write something and press enter. As you might noticed we used
raw_input() which is python function, then we assigned recived input onto 'name'
and later on we were able print or manipulate that string or whatever type of data you entered.

Note! You shouldn't use input() function, its usage is different in python 3,
and python 2.x ! Also you should input only string,
latter on we will see how to handle numbers and unicode characters.

Nice thing feature of raw_input() is that you can give it some argument and
it will print it while asking for input, example:

```python
egg = "Another test input > "
test2 = raw_input(egg)
```
