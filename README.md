[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16851390&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## **How to Run Your Program**

To run this project on a fresh Ubuntu 22.04 installation, follow these steps to set up the required environment and dependencies.

1. **Install Python 3.8+ and pip**:
   Ubuntu 22.04 typically includes Python 3.10 by default. Ensure `pip` is installed:
   ```bash
   sudo apt update
   sudo apt install -y python3 python3-pip python3-venv
   ```

2. **Set up a Virtual Environment**:
   Using a virtual environment keeps dependencies isolated and prevents conflicts.
   ```bash
   python3 -m venv cg-booting-env
   source cg-booting-env/bin/activate
   ```

3. **Install Project Dependencies**:
   With the virtual environment activated, install required libraries:
   ```bash
   pip install moderngl pygame pillow PyGLM numpy
   ```

4. **Clone the Repository**:
   Retrieve the project code from the repository:
   ```bash
   git clone https://github.com/user/cg-booting-up-ivmg57.git
   cd cg-booting-up-ivmg57
   ```

5. **Run Example Scripts**:
   After setup, you can execute any of the example scripts. For instance:
   ```bash
   python 01_hello_world.py
   ```

6. **Deactivate the Virtual Environment (Optional)**:
   To deactivate the environment when done:
   ```bash
   deactivate
   ```

These steps will enable you to run the program on a new Ubuntu 22.04 system with all dependencies correctly configured.

## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs