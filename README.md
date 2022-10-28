# epiclite-airtable-sync

## Python Setup

```
$ brew install python3
```

Update .zshrc by adding following line

```
alias python=/opt/homebrew/bin/python3
```

Install packages using pip3 which will install to `/opt/homebrew/lib/python3.10/site-packages` directory.

```
$ python3.10 -m pip install --upgrade pip
$ pip3 install virtualenv

# creates venv virtualenv in project directory
$ cd project_dir
$ virtualenv venv

# for making sure you can also install from source archives
$ python3 -m pip install --upgrade pip setuptools wheel
```

Freeze Requirements
```
$ pip freeze > requirements.txt
```
