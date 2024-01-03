# Vs-code-for-termux
how to install vscode on Android
## requirements
•[termux][1]
## how to install
first download [termux][1] 
then type this commands
```
  apt update
```
```
  apt upgrade 
```
```
  pkg install proot-distro
```
```
  proot-distro install ubuntu
```
```
  proot-distro login ubuntu
```
```
   apt update
```
```
   apt upgrade
```
```
   apt install wget
```
```
   wget https://github.com/coder/code-server/releases/download/v4.16.1/code-server-4.16.1-linux-arm64.tar.gz
```
```
  tar -xvf ./code-server-4.16.1-linux-arm64.tar.gz
```
```
  cd code-server-4.16.1-linux-arm64
cd bin
```
## how to activate
now type this command``` export PASSWORD="write your password here" ``` and ``` ./code-server```
now open any browser and search [localhost:8080][2]
enter the password
and boom 💥 your vs code is successfully installed 



[1]:https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://f-droid.org/en/packages/com.termux/&ved=2ahUKEwiwyrX23MCDAxW2yqACHX2XD4YQFnoECBAQAQ&usg=AOvVaw1bf8L0u2w5XLk0EKlMVFHy
[2]:localhost:8080
