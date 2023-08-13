# Requirement
* Python 3.7
* pygame==2.1.3.dev8

# How To Start Game
$ python main.py

# How to Play
* use LEFT/RIGHT/DOWN key to control player
* use key 'Space' to jump
* use key 's' to shoot firewall or run

# How Create the AI Model and Test

* Setup the environment

    # Create virtual environment
    python -m venv venv

    # Activate the virtual environment
    venv\Scripts\activate  # windows
    . venv\bin\activate    # Linux/Mac

    # Install dependencies
    pip install -r requirements.txt

* Open jupyter notebook

    jupyter notebook

* Select game ai.ipynb file and open it in Jupyter Notebook.
* Run all cells one by one, you will see a model is created automatically. Then test your own model with "Test Model" section below.
