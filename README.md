# sublime-config
Config sublime 3

Add build command to open index.html in browser:<br/>
[Tools]->[Build System]->[New Build System]<br/>
and paste<br/>
```
"cmd": ["C:\\Program Files\\Mozilla Firefox\\firefox.exe", "-jsdebugger", "-new-window", "${project_path}\\index.html"]
```
