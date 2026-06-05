# artiste-raphael
this is the site name

## in bash  
$ where python  
C:\Users\rober\AppData\Local\Programs\Python\Python311\python.exe
C:\Users\rober\AppData\Local\Microsoft\WindowsApps\python.exe

## create a virtual environment  
rober@RobertPastor MINGW64 ~/git/artiste-raphael (master)
$ python -m venv virtualEnv

$ ls -al  
total 33  
drwxr-xr-x 1 rober 197609     0 Jun  4 12:53 ./  
drwxr-xr-x 1 rober 197609     0 Jun  4 12:42 ../  
drwxr-xr-x 1 rober 197609     0 Jun  4 12:42 .git/  
-rw-r--r-- 1 rober 197609  4846 Jun  4 12:42 .gitignore  
-rw-r--r-- 1 rober 197609 11558 Jun  4 12:42 LICENSE  
-rw-r--r-- 1 rober 197609    17 Jun  4 12:42 README.md  
drwxr-xr-x 1 rober 197609     0 Jun  4 12:53 virtualEnv/  


## activate the virtual environment  (on the PC in windows)
$ source virtualEnv/Scripts/activate  
(virtualEnv)  
rober@RobertPastor MINGW64 ~/git/artiste-raphael (master)  

## install flask  

$ pip install flask  
Collecting flask
  Downloading flask-3.1.3-py3-none-any.whl (103 kB)
     -------------------------------------- 103.4/103.4 kB 5.8 MB/s eta 0:00:00
Collecting blinker>=1.9.0
  Downloading blinker-1.9.0-py3-none-any.whl (8.5 kB)
Collecting click>=8.1.3
  Downloading click-8.4.1-py3-none-any.whl (116 kB)
     -------------------------------------- 116.6/116.6 kB 6.6 MB/s eta 0:00:00
Collecting itsdangerous>=2.2.0
  Downloading itsdangerous-2.2.0-py3-none-any.whl (16 kB)
Collecting jinja2>=3.1.2
  Downloading jinja2-3.1.6-py3-none-any.whl (134 kB)
     -------------------------------------- 134.9/134.9 kB 7.8 MB/s eta 0:00:00
Collecting markupsafe>=2.1.1
  Downloading markupsafe-3.0.3-cp311-cp311-win_amd64.whl (15 kB)
Collecting werkzeug>=3.1.0
  Downloading werkzeug-3.1.8-py3-none-any.whl (226 kB)
     ------------------------------------- 226.5/226.5 kB 14.4 MB/s eta 0:00:00
Collecting colorama
  Downloading colorama-0.4.6-py2.py3-none-any.whl (25 kB)
Installing collected packages: markupsafe, itsdangerous, colorama, blinker, werkzeug, jinja2, click, flask
Successfully installed blinker-1.9.0 click-8.4.1 colorama-0.4.6 flask-3.1.3 itsdangerous-2.2.0 jinja2-3.1.6 markupsafe-3.0.3 werkzeug-3.1.8

[notice] A new release of pip available: 22.3.1 -> 26.1.2
[notice] To update, run: python.exe -m pip install --upgrade pip
(virtualEnv)
rober@RobertPastor MINGW64 ~/git/artiste-raphael (master)
$

