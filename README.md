# IEEE Quantum Week 2024 Mitiq Tutorial

The readme of this repo contains instructions for how to setup your code environment. The slides for both parts of the tutorial
are available [here](https://docs.google.com/presentation/d/1atekUqvwuAlgUWPjn9lxY3Z_ykdrwSTPjGuGP0CDhYA/edit?usp=sharing).

## Setup

To set up the environment for the Jupyter notebooks, please choose from one of the following options:

### Locally
1. Clone this repository to your local machine.
   ```
   git clone https://github.com/unitaryfund/qce24-tutorial.git
   cd qce24-tutorial
   ```

2. Install the necessary requirements into an existing Python environment or create a new Python environment and then install the requirements.
   ```
   pip install mitiq
   ```

### Virtually
To run the notebooks virtually, you can  use [Codespaces](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository): 
   *To use Codespaces, an active Github account is required.*

1. In the repository, select the green Code button, switch to the Codespaces tab, and click the `Create codespace on main` button.

![image](https://github.com/user-attachments/assets/23d1004b-fc28-4717-a9e2-39e579fa2d35)

3. When Codespaces has loaded, select the first Jupyter notebook, part1_zne.ipynb from the repository files on the left.

4. At the bottom of the screen a pop-up will recommend installing Python. Click the `Install` button.

5. When python has finished installing, close the `Extension: Python` tab to return to the `part1_zne.ipynb` notebook.

![image](https://github.com/user-attachments/assets/0b1eec4e-70c6-4165-aae5-595d9bfd3c89)


7. On the right side of the notebook, click `Select Kernel` and then choose `Install/Enable suggested extensions Python + Jupyter`
![image](https://github.com/user-attachments/assets/6426f336-3fa9-4400-b7cc-db8e3c722e99)


8. After the extensions finish installing, select `Python Environments...` and then `Python 3.12.1 ~/.python/current/bin/python` from the `Select Another Kernel` window.

9. With the Python environment setup, run the `%pip install mitiq` code block to install Mitiq into the Python environment.


## Resources

- [Mitiq documentation](https://mitiq.readthedocs.io/en/stable/)
- [ZNE user guide](https://mitiq.readthedocs.io/en/stable/guide/zne.html)
- [Pauli Twirling user guide](https://mitiq.readthedocs.io/en/stable/guide/pt.html)
- [Calibration user guide](https://mitiq.readthedocs.io/en/stable/guide/calibrators.html)
- [Mitiq Examples](https://mitiq.readthedocs.io/en/stable/examples/examples.html)

