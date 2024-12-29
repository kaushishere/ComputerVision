# ComputerVision
Each project folder includes a Jupyter Notebook which I developed with the help of Andrew Ng's Machine Learning Course. These notebooks will showcase how simple digit recognition can be with very few lines of code.

| Project                         | Description                 |
|--------------                   |-----------------------------|
| Digit Recognition - Binary      |    Build & train a neural network to classify handwritten digit drawings as either 0s or 1s       |
| Digit Recognition - Multiclass  |    Build & train a neural network to classify handwritten digit drawings as any number from 0-9 | 

# Install
## 1. Clone repository
I recommend clone all repositories into a folder called 'Git' in your C drive. If you don't like the CLI (Command Line Interface), GitHub Desktop is a much friendlier option.

## 2. Setup a virtual environment
These notebooks are not the heaviest in the world, but to be safe, always create a `venv`. Ensure you are in the cloned repository's directory, and then in the CLI:
```
python -m venv [name_of_venv]
```
Activate `venv`:
```
[name_of_venv]\Scripts\activate
```

## 3. Install dependencies
```
pip install -r requirements.txt
```
This will take 10-15 minutes so have a cuppa in the meantime.

## 4. Open notebook.ipynb file in VSCode 
Open VSCode. Open your project folder. Start a new terminal. Activate your `venv` by typing in the terminal at the bottom of the screen:
```
[name_of_venv]\Scripts\activate
```
If this throws an error like `UnauthorisedAccess`, run:
```
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
```
and try activating `venv` again.

You are ready to run the notebook!

