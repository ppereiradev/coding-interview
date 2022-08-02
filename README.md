# Coding Interview Prep

In this repository, there are several Jupyter Notebooks that I am using to prepare for my code interview in the Google. Feel free to clone and use these notebooks to prepare for your code interview.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packates to run the Jupyter Notebooks.

First, create a virtual environment to install the required packages.
```bash
python3 -m venv venv --prompt="interview-prep"
```

After that, we will have a venv folder in the directory. Activate the virtual environment.
```bash
source venv/bin/activate
```

Once we have the virtual environment activated, you have to make sure you update the pip package manager.
```bash
pip install --upgrade pip
```

Now, install the required packages.
```bash
pip install -r requirements.txt
```
Finally, we have our environment ready to run the Jupyter notebooks.

## Usage

Execute the jupyter notebook command.
```bash
jupyter notebook
```

If the browser doesn't open automatically, access http://localhost:8888.
