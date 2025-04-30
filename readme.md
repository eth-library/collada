# Data Stories

## Create a virtual environment
### Windows
#### Install Python
Download your version of Python here:
https://www.python.org/downloads/release/python-3133/
#### Set up env
1. Open a terminal in the folder of this repo, select "command prompt" and enter this:
```
py -3.13 -m venv "env_datastories"
```
2. Now you activate said environment by copy and pasting this into the terminal:
```
.\env_datastories\Scripts\activate.bat
```
3. Download all the necessary libraries. Copy and paste this into the terminal:
```
pip install wheel==0.45.1
```
that helps us with the installation of the other packages.

4. Then copy and paste this into the terminal:
```
pip install -r requirements.txt
```
### MacOS
#### Install Homebrew
Open a terminal in the folder of this repo. Now go to <i>[Homebrew](https://brew.sh)</i> webpage and copy the command and paste it into terminal.

While installing Homebrew it can ask you about your password, and will inform you what it will download and install - please press `Enter`. Once Homebrew is installed, follow the `==> Next steps:` printed in the output, and copy-paste the commands it provides to the terminal.
Now copy-paste the command:
```
brew list | grep python
```
There should be python@3.12 and python@3.13 listed. When installing Homebrew, Python was automatically installed.
#### Set up env
1. Then you create an environment by the name of "env_datastories" with that specific Python version by copy and pasting this into the terminal:
```
python3.13 -m venv "env_datastories"
```
2. Now you activate said environment by copy and pasting this into the terminal:
```
source ./env_ds4glam/bin/activate
```
3. Download all the necessary libraries. Copy and paste this into the terminal:
```
pip install wheel==0.45.1
```
that helps us with the installation of the other packages.
4. Then copy and paste this into the terminal:
```
pip install -r requirements.txt
```