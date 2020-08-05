# Git basic

Open terminal: <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>T</kbd> or Press Windows (Super) keys and search for **Terminal**

1) Clone (download):
```sh
cd ~
git clone https://github.com/sun7pro/robotframework-begin.git
```

2) Working on new task:
```sh
cd ~/robotframework-begin
git checkout -b branch-name-of-new-task-here
```

3) Complete task:
```sh
git status
git add list-of-files-you-are-editing
git commit -m 'This is message, for example: Complete docs for install'
git push origin branch-name-of-new-task-here
```

4) After task was *merged* on Github:
```sh
cd ~/robotframework-begin
git checkout main
git pull origin main
```

5) Work on another new task or fix something => Return to step 2
