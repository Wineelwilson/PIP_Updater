# PipUpdater - Automate the Update of Python Packages

PIPUpdater is a **Py Packages' Updater** *AKA* **PYTHON (SMT) System Maintenance Tool**.  It is a Python script that automates updating pip and all installed packages in a Python environment.  It simplifies keeping your Python packages up-to-date, ensuring you have the latest versions of all dependencies.

## Table of Contents

  - [Installation](#Installation)
  - [Download](#Download)
  - [Usage](#Usage)
      - [Global Python Environment](#Global-Python-Environment)
      - [Virtual Python Environment](#Virtual-Python-Environment-venv)
  - [License](#License)
  - [Contact](#Contact) 
  - [Future Plans](#Future-Plans)
  
## Installation

No installation is required for the `PIPUpdater.exe` file.  You can directly download and run it on your Windows.

## Download

You can download the latest version of the `PIPUpdater` executable for Windows from the [Releases]() page.

## Usage

### Global Python Environment

1. Download the `PIPUpdater` executable from the Releases page.
2. Place the `PIP_Updater.exe` file in any directory of your choice.
3. Double-click the `PIPUpdate.exe` where you want to update your Python packages.

The script will update pip to the latest version and automatically update all installed packages in your global Python environment.

### Virtual Python Environment (venv)

1. Create and activate your virtual environment using your preferred method.
2. Download the `PIPUpdater` executable from the Releases page.
3. Place the `PIP_Updater.exe` file in your virtual environment directory.
4. Open the Command Prompt within the virtual environment:
     - Press `Windows Key + R`, type `cmd`, and press Enter.
5. Navigate to the directory containing your virtual environment.
6. Activate the virtual environment by running the appropriate command:
     - `path_to_venv\Scripts\Activate`
     - Replace `path_to_venv` with your actual virtual environment directory.
7. Run the `.exe` file, type the following command and press Enter:
     - `PIP_Updater.exe`
     - The script will update pip to the latest version and automatically update all installed packages in your virtual Python environment (venv).

## License

The `PIP_Updater` script is distributed under the [MIT License](LICENSE).  See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, please reach out to me at [email](mailto:wineel10wilson@gmail.com).

## Future Plans

We have plans to expand PIP_Updater's support to other platforms in future releases. Stay tuned for updates!
