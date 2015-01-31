# Lesson 1: printing and commenting

Comments are very important. They help you keep your program understandable,
it helps other people to start working on your code , and generally you
should comment as much as you can.

Single line commenting is good for a short, quick comment (or for debugging),
while the block comment is often used to describe something much more in detail
or to block out an entire chunk of code.

Open python interpreter as explained in introduction and type in:
```python
print("Hello world")
```
and run (interpret) the code by pressing enter.

Your terminal should look like this:
```
Python 2.7.5
Type "help", "copyright", "credits" or "license" for more information.
>>> print("Hello world")
Hello world
>>>
```

You just told python to print everything inside quotes "" and to do that you
used pythons built in function print() . You can also omit the brackets and do like following:

```python
print "Hello."
```
We talked about comments a lot but didn't see any of those so far.
To comment you just can use the # (pound) sign to comment out everything that follows it on that line.

```python
>>>print("Not a comment")
>>>Not a comment
>>>#print("Am a comment")
>>>
```
You can also do multiple line comments too.
To make one you can simply use 3 single or 3 double quotes before and after the
part you want commented.
```python
'''
print("We are in a comment")
print ("We are still in a comment")
'''
print("We are out of the comment")
```
Output would be like following:
```
We are out of the comment
```
