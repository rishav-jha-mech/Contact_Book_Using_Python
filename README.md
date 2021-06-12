# Contact_Book_Using_Python

## To run Contact Book you should have python installed on your pc.

### Step No. 1 - Install virtual environment on the project directory where requirements.txt is present (skip this step if you already have virtualenv installed)

```
pip install virtualenv
```
### Step No. 2 - Place the virtual environment using this command

```
virtualenv env
```

#### This will create an env folder.

### Step No. 3 - Activate virtual environment (you have to reach to the activate.bat file in env/Scripts/)

```
cd env
cd Scripts
activate (if using CMD) / . activate (if using GitBash)
```

#### Now the virtual environment is created. Now you can see (env) at the starting of your path (ex- "(env)C:Users/username/Desktop/ProjectFolder")

### Step No. 4 - Comeback to  the project folder

```
(env)projecrrootfolder/env/Scripts/ cd ..
(env)projecrrootfolder/env/ cd ..
(env)projecrrootfolder/
```
#### you just need to type cd .. and enter two times to get to the project root folder

### Step No. 5 - Install the requirements from requirements.txt file

```
python -m pip install -r requirements.txt
```

#### Now  all the necessary dependencies will be installed from requirements.txt file

### Step No.6 - Now its time to run our Contact Book application

```
python contacts.py
```

#### Now the app will launch and you can use it.



![thumbnail image](a-image.png)




# EDITS ARE WELCOME
