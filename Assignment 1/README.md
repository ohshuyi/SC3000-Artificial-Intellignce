# Assignment 1


## 📁 Folder Structure

```
~
├── video                   # Video folder for task 3
├── CartPole-v1.ipynb       # Notebook for Cartpole Assignment
├── README.md               
├── assignment1.docx        # Assignment 1 Description
└── requirements.txt        # Dependencies required
```


## 📌 To install the dependencies required for the project:
Run the following commands in terminal:

1. Install virtualenv:
```console
python -m pip install virtualenv
```

2. Create a virtual python environment
```console
python -m virtualenv venv --python=python3.10
```

3. Activate the virtual environment created

For MacOS:
```console
source venv/bin/activate
```

For Windows:
```console
venv/Scripts/activate
```

4. Install all dependencies on the requirements.txt file
```console
python -m pip install -r requirements.txt
```

5. Check if ffmpeg is installed on your virtual environment (required to record the video)
```console
ffmpeg -version
```
