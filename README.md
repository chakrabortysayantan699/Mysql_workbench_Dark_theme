# Mysql_workbench_Dark_theme

**For windows 💻 :**

**Step 1**: just go to  the installed location of workbench  then go to the data folder
```
C:\Program Files\MySQL\MySQL Workbench 8.0 CE\data
```
there we can find **code_editor.xml** 

then just replace this **repo's code_editor.xml** with your machine's **code_editor.xml** 

**OR🚀**
you can just add 

``` xml
<style id="32" fore-color-light="#ABB2BF" back-color-light="#232729" fore-color-dark="#ABB2BF" back-color-dark="#232729" /> <!-- OVERALL BACKGROUND -->
<style id="33" fore-color-light="#ABB2BF" back-color-light="#21252b" fore-color-dark="#ABB2BF" back-color-dark="#21252b" /> <!-- LINE NUMBER BACKGROUND -->
```
these two line after 
``` xml
<style id="18" fore-color-light="#98c379" fore-color-dark="#98c379" bold="yes"/> <!-- SCE_MYSQL_USER1 -->
```
now save it 
**Restart your work bench💥**
