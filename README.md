Sample for automation api with postman and newman report

*URL have been changed a little bit for data secure for my client

Install Newman for windows

Install NodeJS – https://nodejs.org/download/. Click on the 32-bit or 64-bit Windows Installer package, depending on your machine configuration.
Add the Node executable to your system path. Go to the Control Panel > System and Security > System > Advanced System Settings > Environment variables. Append this to the end of the PATH variable: ;C:\Program Files\Nodejs
If you installed Node in a different location, you’ll need to set the PATH accordingly.
Install Python 2.x. The latest 2.x release available is 2.7.9 (https://www.python.org/downloads/release/python-279/). Get the Windows x86-64 MSI installer or Windows x86 MSI installer, and follow the instructions.
Open a command prompt, and type “node”. The node environment should start. Press Ctrl-C to exit.
You’ll need to install the Visual Studio runtime for some Newman dependencies to be installed. The quickest way to do this is to install Visual Studio Express – http://go.microsoft.com/?linkid=9816758. To check for any additional requirements for your system, check https://github.com/TooTallNate/node-gyp (Windows).
Type “npm install -g newman”. It should take a few minutes to install. If all goes well, this is what you should see
