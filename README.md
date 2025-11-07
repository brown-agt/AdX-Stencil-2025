# CS1440/2440 Final Project: AdX

## Introduction

The AdX Game: This final project is your chance to put everything we've learned into practice, especially the cool strategies from the last few labs. It's going to be remote and a lot more free-form than what we're used to, so there's plenty of room to experiment and find what works best for your agent. I hope you all have fun!

## Setup and Installation

Follow these steps to set up your environment for the AdX game.

### Step 1: Git Clone this Repository

Open your terminal and navigate to where you want to clone the repository

```bash
git clone https://github.com/brown-agt/AdX-Stencil-2025.git
```

### Step 2: Create a Virtual Environment (Optional)
If you plan to use any external packages, it's a good idea to do this

Please then navigate to your project directory. Run the following commands to create a Python virtual environment named `.venv`.

If you own a Mac

```bash
python3 -m venv .venv
source .venv/bin/activate
```

If you own a Windows

```bash
python3 -m venv .venv
.venv\Scripts\activate
```

### Step 3: Install the agt server package

```bash
pip install --upgrade pip
pip install --upgrade agt-server
```

## Notes about the python code

- Please refer to the [final project handout](https://cs.brown.edu/courses/csci1440/labs/fall-2025/AdX_Game_Final_Project_Spec.pdf) and read through it carefully! It contains a lot of information specific to this implementation of the spectrum auction and making sure your code works for submission.
- Implement your agent in the `my_agent.py` file. 
- Please let us know if you want to import any new packages and we will install it on our end after checking it so that the code can import it in the final submission. 
