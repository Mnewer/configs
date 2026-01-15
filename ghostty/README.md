## Add startup command in default mac terminal

1. Edit shell config:

```shell
nano ~/.zshrc
```

3. Add this to the bottom of the file:
When a terminal window is opened it shows the content of this directory 
```shell
# Auto-list directory contents on terminal launch
if [[ -o interactive ]]; then
  ls
fi
```

3. Save and restart terminal
