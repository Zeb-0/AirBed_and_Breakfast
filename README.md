# DAY 19 - 100-Days_of_Code

Attempting to create a clone of [AirBnB website](https://www.airbnb.com/).

### Concepts to check out:
- [Python packages](https://intranet.alxswe.com/concepts/66)
- [packages](https://docs.python.org/3.4/tutorial/modules.html#packages)
- [AirBn clone](https://intranet.alxswe.com/concepts/74)

## Resources:
- [cmd module](https://docs.python.org/3.8/library/cmd.html)
- [cmd module in depth](http://pymotw.com/2/cmd/)
- packages concept page
- [uuid module](https://docs.python.org/3.8/library/uuid.html)
- [datetime](https://docs.python.org/3.8/library/datetime.html)
- [unittest module](https://docs.python.org/3.8/library/unittest.html#module-unittest)
- [args/kwargs](https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/)
- [Python test cheatsheet](https://www.pythonsheets.com/notes/python-tests.html)
- [cmd module wiki page](https://wiki.python.org/moin/CmdModule)
- [python unittest](https://realpython.com/python-testing/)

### Execution:
The shell is supposed to work as shown below in **Interactive mode**
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```

In **Non-Interactive mode**:

```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```

**Run all Tests in non-interactive mode using:**

`$ echo "python3 -m unittest discover tests" | bash`

---

# DAY 21 - 100-Days_of_Code

#### Tried writing unittests for AirBnB project and i can cinfidently say i am so fucked.
