
Java Code Style
================

IntelliJ IDEA code style settings for Square's Java and Android projects.


Installation
------------

 * On Unix, run the `install.sh` script. Windows users should use `install.bat` instead.
 * Restart IntelliJ if it's running.
 * Open IntelliJ Project Settings -> Code Styles, change the code style for the
   project to the one you want.

集成Checkstyle到gradle中
---------

1. https://github.com/lizijin/java-code-style.git githook目录中的文件全部拷贝到项目的根目录中
2. 执行gradle clean test
3. 在app/build.gralde 末尾增加 apply from:rootProject.file('checkstyles.gradle')

License
-------

[![Public domain](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/legalcode)

