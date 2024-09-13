# Aim Trainer
Mouse-click aim trainer with `pygame`.


## Setup Instructions - Create a Virtual Environment
Use a virtual environment to install `pygame` and other packages without affecting the system Python installation.

#### Steps to Create and Use the Virtual Environment:

1. **Create a Virtual Environment**:
   Run the following command in your terminal to create a virtual environment:

   ```bash
   python3 -m venv ~/pygame_venv
   ```

2. **Activate the Virtual Environment:**
   Once the virtual environment is created, activate it:

   ```bash
   source ~/pygame_venv/bin/activate
   ```
   
After activation, your terminal prompt will change to indicate you're inside the virtual environment.

3. **Install Pygame:**
   With the virtual environment activated, install pygame by running the following command:

   ```bash
   pip install pygame

4.**Run Your Script:**
   Now, you can run the aim_game.py script inside the virtual environment:

   ```bash
   python aim_game.py
   ```
5. **Deactivate the Virtual Environment:**
   When you're done running the game, deactivate the virtual environment by using:

   ```bash
   deactivate

**Notes**
Ensure you have Python 3 installed on your system before creating the virtual environment.
The virtual environment isolates dependencies and packages, keeping your system Python installation clean and free from potential conflicts.
You can re-activate the virtual environment anytime by using source ~/pygame_venv/bin/activate.
