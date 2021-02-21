# MAYA-Xtractor
MAYA-Xtractor is a script to extract all the timetables and tabulate them in CSV files.

## Prerequisite
- Python 3: [Download](https://www.python.org/downloads/)
- pip: [Download](https://pip.pypa.io/en/stable/installing/)
- git: [Download](https://git-scm.com/download/)
- Google Chrome: [Download](https://www.google.com/chrome/)
- ChromeDriver: [Download](https://chromedriver.chromium.org/downloads)

## Initialize
To begin, clone this repository in your local environment.

```$ git clone https://github.com/chenghui-lee/MAYA-Xtractor/```

And cd into the cloned directory

```$ cd MAYA-Xtractor/```

Install the required packages

```$ pip install -r requirements.txt```

Change the environment attributes in ```env.py``` according to your needs.

This including your Maya username, password and path to your ChromeDriver.

```python
os.environ['USERNAME'] = '175598874' # Your new Maya ID here
os.environ['PASSWORD'] = 'password12345' # Your Maya Password
os.environ['PATH'] = 'E:\Selenium\ChromeDriver' # Path to your ChromeDriver
os.environ.get("HEADLESS") == 'True' # Change to 'False' if you like to visualise it
```

## Run
To run the program

```$ python maya-xtractor.py```

```CTRL+C``` to terminate the program during the runtime.

