tmux
---

list sessions
```
tmux ls 
...
...
```

connect session  
```
tmux a -t >"name"<
```

new session 
```
tmux new -s >"name"<
```

split 
```
^b + "
```

|	|
|-------|
|	|

Split
```
^b + %
```
|	|	|
|-------|-------|
||x|



move pointer

______
^b + &#8592;

^b + &#8593;

^b + &#8594;

^b + &#8595;
______


kill pane 
```
^b + x
```

set option 
```
^b + :
synchronize-panes
set-option -g mouse on
```
