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

2. Paste in the file path of where you cloned your repository, ensure you follow this format: /path/Assignment_3_Code (DO NOT PASTE with raw hardrive paths like "C:/User/TrevorsPC/...", if it is in downloads it must be /Downloads/Assignment_3_Code)
<img width="353" height="228" alt="image" src="https://github.com/user-attachments/assets/e19e8bee-3f35-4547-8ccf-a6be3bbb0aaf" />

3. Happy Coding!! (NB!! Please note that jupyter lab does not support running python environments and source control, therefore how you push any code and handle for missmatching dependencies is your responsibility)

# Instructions on installing new packages
```
pip install {{package name}}
```
then,
```
pip freeze > requirements.txt
```
then push changes and sync local repository
