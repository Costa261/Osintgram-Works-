

    Fork/Clone/Download this repo

    git clone https://github.com/Datalux/Osintgram.git

    Navigate to the directory

    cd Osintgram

    Create a virtual environment for this project

    python3 -m venv venv

    Load the virtual environment
        On Windows Powershell: .\venv\Scripts\activate.ps1
        On Linux and Git Bash: source venv/bin/activate

    Run pip install -r requirements.txt

    Open the credentials.ini file in the config folder and write your Instagram account username and password in the corresponding fields

    Alternatively, you can run the make setup command to populate this file for you.

    Run the main.py script in one of two ways
        As an interactive prompt python3 main.py <target username>
        Or execute your command straight away python3 main.py <target username> --command <command>
