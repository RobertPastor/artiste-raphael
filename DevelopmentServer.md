## activate the virtual environment

rober@RobertPastor MINGW64 ~/git/artiste-raphael (master)
$  source virtualEnv/Scripts/activate
(virtualEnv)
rober@RobertPastor MINGW64 ~/git/artiste-raphael (master)



## run the development server on the local PC

$ python app.py
 * Serving Flask app 'app'
 * Debug mode: on
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 141-515-527
127.0.0.1 - - [04/Jun/2026 13:21:37] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [04/Jun/2026 13:21:37] "GET /favicon.ico HTTP/1.1" 404 -


## open a browser and paste http://127.0.0.1:5000/
should be running and showing "Hello, World"