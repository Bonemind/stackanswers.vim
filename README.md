stackanswers.vim
================

Vim plugin to get answers from [Stack Overflow](https://stackoverflow.com/). Inspired by [SO-Eclipse-Plugin](https://github.com/MarounMaroun/SO-Eclipse-Plugin).

`:StackAnswers`
--------------------------
Anything inputted after the command becomes the 'question' that will be answered from Stack Overflow, provided
that answers exist.
Answers will be shown in a separate buffer

Ex:

`:StackAnswers what is object oriented programming`

![Gif](/screenshots/example.gif)

Dependencies
------------
```
pip install requests
pip install beautifulsoup4
pip install lxml
```

TODO
----
- Handle if no valid responses
- Answer filters
- Fix bugs
- Documentation
