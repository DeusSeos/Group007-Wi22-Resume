## VSCODE

Open powershell and cd into the directory you want to create the virtual environment in.

Then run ```python -m venv venv```
This should create a new folder called venv in your current directory.

This should create a prompt and make sure to hit yes.

Run ```.\venv\Scripts\activate```  This is an actiavte script for the venv

Powershell terminal should now lead with ```(venv)```

Looks like this ```(venv) PS C:\Users\UserName\FolderName\FolderName2\FolderName3>```

Now you can run pip install "package-name" and it should install locally to the venv environment insted of globally.




