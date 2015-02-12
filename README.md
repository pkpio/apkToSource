# apkToSource
**NOTE:** This is no special creation. It uses tools developed by wonderful people on Web.

This exits because I want it. A quick set of instructions on how to decompile APK --> Java code.

# Instructions
1. Run  ```./dex2jar/d2j-dex2jar.sh sample/CrackMeApplication.apk```
2. That generates ```CrackMeApplication-dex2jar.jar``` in the current path
3. Now run ```./jd-gui/jd-gui``` and select above jar.

# Dependencies
1. On Ubuntu 14.04 64-bit for ```jd-gui```, run: ```sudo apt-get install libgtk2.0-0:i386```

# References & Credits
 - **dex2jar** https://code.google.com/p/dex2jar/w/list
 - **jd-jui** http://jd.benow.ca/
