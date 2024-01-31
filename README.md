# PyBubbles
Requirements for running NFT Bubbles.

Installing Python and specified packages. This guide assumes you are starting from scratch and does not have Python installed.

### Step 1: Install Python

#### Windows:

1. **Download Python**: Go to the official Python website ([python.org](https://python.org)) and download the latest version of Python. Ensure it is Python 3, as Python 2 is outdated.
2. **Run the Installer**: Open the downloaded file to start the installation. **Important**: Check the box that says **"Add Python 3.x to PATH"** before clicking "Install Now."
3. **Verify Installation**: Open Command Prompt and type `python --version`. You should see the Python version you installed.

#### macOS/Linux:

- **macOS**:
  1. You can install Python using Homebrew (a package manager for macOS). If you don't have Homebrew installed, you can install it by pasting the following in a terminal: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`.
  2. Then, install Python by running `brew install python`.
- **Linux**:
  1. Most Linux distributions come with Python pre-installed. You can check by typing `python3 --version` in your terminal.
  2. If it's not installed, you can install Python using your distribution's package manager, for example, `sudo apt-get install python3` (for Ubuntu/Debian).

### Step 2: Install `pip`

`pip` is the Python package installer. It should come with Python 3.4 and above. To check if you have `pip` installed, type `pip --version` in your command line (Windows) or terminal (macOS/Linux).

If it's not installed, download `get-pip.py` by navigating to https://bootstrap.pypa.io/get-pip.py, then run `python get-pip.py`.

### Step 3: Install the Required Packages

Now, let's install the packages you've listed. The most straightforward method is to create a `requirements.txt` file containing all the packages and their versions, then use `pip` to install them.

1. **Create a `requirements.txt` File**: Open your text editor and paste the list of packages and their versions you provided. Save the file as `requirements.txt` in your project directory or any convenient location.

2. **Install Packages**: Open your command line or terminal, navigate to the directory where your `requirements.txt` file is saved, then run the following command:

```bash
pip install -r requirements.txt
```

This command tells `pip` to read the `requirements.txt` file and install all the packages listed in it along with their specified versions.

### Troubleshooting

- If you encounter any installation errors, they are often due to missing system dependencies or conflicts between packages. Read the error messages carefully for hints on what went wrong.
- Ensure your `pip` is up to date by running `pip install --upgrade pip`.
- Some packages may require development tools to be installed on your system. For example, on Linux, you might need to install `build-essential`, `python3-dev`, or similar packages.

### Final Check

After the installation is complete, you can verify that the packages are installed correctly by using `pip list`. This command will show you all the installed Python packages and their versions.


