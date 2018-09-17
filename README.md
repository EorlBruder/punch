# punch


Punch for Todo.txt

Punch is a time-tracking add-on for todo.txt - a command line to-do list list utility. Punch works alongside the todo.txt script files popularized by Life Hacker and todotxt.org. All time tracking info is kept in a separate file, so no harm is done to the todo.txt system. It does use your todo.cfg file and todo.txt file to streamline time tracking. 

## Usage

You should set `TODOTXT_CFG_FILE` if your `todo.cfg` isn't located on a standard location. 

To use `punch.py` execute the file `Punch.py` with python (2). You may want to add an alias for this. 

You can use punch as follows (this is the output from `punch -h`):

```
Punch.py [-h] command [line-number] [filename] [archive-date]
        
  Commands:
  'in' : start the timer for a todo task [line-number]
  'out' : stop the timer for the current task
  'what' : print the current 'active' task. shortcut is 'wh'
  'report' : print a report. shortcut is 'rep'
  'archive' : archive all time records previous to [archive-date] inclusive
        
  line-number is the number of the item in the todo.txt file (or filename)
```


## Fork

This is a project originally forked from http://code.google.com/p/punch-time-tracking/:


