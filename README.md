<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/default-credential/main/content/default-credential.svg"></p>

Manufacturers or developers typically set default credentials, such as username and password combinations, for devices, software, and systems. These credentials are intended for initial access. A threat actor may exploit default credentials to gain unauthorized access to the system or data.

## Example

Clone this current repo recursively
```sh
git clone --recurse-submodules https://github.com/qeeqbox/default-credential
```
Run the webapp using Python
```sh
python3 default-credential/vulnerable-web-app/webapp.py
```
Open the webapp in your browser 127.0.0.1:5142
<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/default-credential/main/content/1.png"></p>
Use the default credentials (username: admin and password: admin) to login
<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/default-credential/main/content/2.png"></p>
You have full control over the web app interface
<p align="center"> <img src="https://raw.githubusercontent.com/qeeqbox/default-credential/main/content/3.png"></p>

