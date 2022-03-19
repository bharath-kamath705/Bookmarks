# Bookmarks
Vim inspired bookmarks for terminal directory navigation

<img src="https://user-images.githubusercontent.com/49598128/159139772-6fda7de2-544b-4bec-8036-09c8df42efb1.gif" width="600" height="200">

## Usage
```
Usage:
  m MARK_NAME              set mark to present directory
  j MARK_NAME              jump to mark
  m [OPTION]

MARK_NAME
  [a-z]                    lower case alphabet

OPTIONS
  -ls [N]                  list N most recently set marks, defaults to 10
  -lsa                     list all marks
  --help                   show help page

Examples:
  m w        Set the mark 'w' to present working directory
  j w        Jump to mark 'w'
  m -ls      Show 10 most recently set marks
  ```
  
  ## Install
  ```
  /foo/Bookmarks/install
  source ~/.bashrc
  ```
