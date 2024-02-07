# Web Server

The [Web Server for Chrome App](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) used at the time of recording is no longer supported in most operating systems (now only runs on Chrome OS). But don't worry! You can use these alternatives instead:

**Option 1**: The [Simple Webserver](https://simplewebserver.org/) is a standalone application that is a [continuation of the Chrome App](https://simplewebserver.org/docs/wsc.html) used in this course. The interface is the same so you should be able to follow the videos easily. You can download it [here]() and install on your computer.

**Option 2**: If you already have [Python](https://www.python.org/) installed on your computer, you can use its bundled [http.server](https://docs.python.org/3/library/http.server.html#module-http.server) module to run a basic web server. Here are the steps to use it:

From your Terminal/PowerShell/Command Prompt, navigate to the folder of an ungraded lab/assignment.

From there, type: **python3 -m http.server**. You should see an output like: **Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...**

Open your web browser and type: **0.0.0.0:8000/<filename of the HTML file>** in the address bar (or whatever IP address was printed out in step 2). For example: **0.0.0.0:8000/C1_W1_assignment.html**.