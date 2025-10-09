# Instructions to run on VScode! (Ensure Jupyter extension is installed)
1. First install environments
```
py -m venv venv
```
No venv package?
Run this before installing environments.
```
py -m pip install venv
```
2. Activate your environment

using git bash
```
source venv/Scripts/activate
```
using cmd
```
venv/Scripts/activate
```
3. Install all dependencies for project
```
pip freeze requirements.txt
```
then,
```
pip install -r requirements.txt
```
4. Happy Coding!!

# Instructions on running python environments on jupyter lab
1. Click on file then open from path
<img width="394" height="63" alt="image" src="https://github.com/user-attachments/assets/bc0a2757-0c49-417d-8ed1-0998bf49fdad" />

2. Paste in the file path 

# Instructions on installing new packages
```
pip install {{package name}}
```
then,
```
pip freeze > requirements.txt
```
then push changes and sync local repository
