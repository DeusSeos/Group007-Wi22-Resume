## VSCODE

Open powershell and cd into the directory you want to create the virtual environment in.

Then run ```python -m venv venv```
This should create a new folder called venv in your current directory.

This should create a prompt and make sure to hit yes.

Run ```.\venv\Scripts\activate```  This is an actiavte script for the venv

You may have to run this ```Set-ExecutionPolicy Unrestricted -Scope Process``` IDK what it does I don't have time to research and understand this rn :'(

Powershell terminal should now lead with ```(venv)```

Looks like this ```(venv) PS C:\Users\UserName\FolderName\FolderName2\FolderName3>```

Now you can run pip install "package-name" and it should install locally to the venv environment insted of globally.

## Pip package installing
Using pipreqs should make installing all the requirements for this project easier.

Make sure that you have the package ```pipreqs``` installed
After adding a new package run ```pipreqs .```

This should generate a ```requirements.txt``` file

Running ```pip install -r requirements.txt``` should install everything. Hopefully...

Sources: [Install pip fast lol](https://stackoverflow.com/questions/46419607/how-to-automatically-install-required-packages-from-a-python-script-as-necessary)





