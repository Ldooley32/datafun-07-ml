# datafun-07-ml
### Project 7 Machine learning
## Introduction:
    Following a guided project to get an introduction into machine learning. Using a supervised learning type catagory and incorprateing a simple linear regression, to train a model. The model will result in making predictions by identifing a "best-fit" line in the date. 

## Project Start
1. Create a new repository in GitHub name it : datafun-07-ml
2. Make public, and add a README.md fi
3. clone repository in VS Code
4. Add .gitignore with:
   
    ```
        # Ignore project virtual environment in the .venv folder
        .venv/
    
       # Ignore Visual Studio Code settings in the .vscode folder```

       .vscode/

       # Ignore macOS specific files
         .DS_Store

       # If the project uses Jupyter Notebooks include the following

          .ipynb_checkpoints/
    ```
   
6. Add a requirements.txt file with 

```
jupyterlab
numpy
pandas
pyarrow
matplotlib
seaborn
scipy
```

7. To update local machine with changes to repo made in GitHub

    ```git pull```

8. To updat GitHub with changes to rep made locally.

    ```
    git add .
    git commit -m "msg"
    git push origin main
    ```


## Create a Virtual Environment 
Creat a virtual environment to be ablle to install dependencies that will not interfere with my machine. 

1. create a virtual environment
   
```
python3 -m venv .venv
```

2. activate virtual environment
   
```
source .venv/bin/activate
```

3. Install requirement
   
```
python3 -m pip install -r requirements.txt
```


