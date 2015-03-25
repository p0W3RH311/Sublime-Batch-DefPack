# Sublime-Batch-DefPack
This package replaces the default Sublime Batch file package

 ... provides extensive support for Batch file, including:

  *  Full syntax highlighting for cmdfile source (.cmd files)
  *  Many snippets to reduce typing
  *  support new syntax for Cmd macro-module..

```Batch
 %calllib% MyStr=:Reverse(Str) 
 echo %MyStr%
```

## Snippets

**forindo**

| Trigger  | Name |
| -------  | :-----|
| for      | for %%x in (..) .. |
| forf     | for /f ".." %%x in (..) ..  |
| forr     | for /r ".." %%x in (..) .. |
| ford     | for /d %%x in (..) .. |
| forl     | for /l %%x in (..) .. |
| fordr    | for /d /r %%x in (..) .. |

**if statement**

| Trigger  | Name |
| -------  | :-----|
| if       | if /i "%var1%"=="%var2%" () |
| else     | else ( ... ) |
| ifelse   | if /i "%var1%"=="%var2%" ( ... ) else ...  |
| elseif   | else if /i "%var1%"=="%var2%" (...) |
| ifelseif | if /i (...) else if /i (...) else (...) |

**Miscellaneous**

| Trigger | Name |
| ------- | :---- |
| macro   | macro module |
| sub     | subroutine |
| setl    | setlocal enable.... |





**NOTE:** This version is for [Sublime Text 3](http://sublimetext.com/3)


## DEMO

[![Demo de Sublime-Batch-DefPack](http://img.youtube.com/vi/os_OAK8BnXo/0.jpg)](https://www.youtube.com/watch?v=os_OAK8BnXo)


