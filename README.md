# excel-file-merge-app

# Watch the tutorial video

[How to build an app for combining the contents of multiple spreadsheet files | Streamlit #23](https://youtu.be/xt4hrtG4t3s)

<a href="https://youtu.be/xt4hrtG4t3s"><img src="http://img.youtube.com/vi/xt4hrtG4t3s/0.jpg" alt="How to build an app for combining the contents of multiple spreadsheet files | Streamlit #23" title="How to build an app for combining the contents of multiple spreadsheet files | Streamlit #23" width="400" /></a>

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/excel-file-merge-app/main/app.py)

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *excel*
```
conda create -n excel python=3.7.9
```
Secondly, we will login to the *excel* environement
```
conda activate excel
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/excel-file-merge-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/excel-file-merge-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
