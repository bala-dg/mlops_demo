create env 

'''
conda create -n wineq python=3.8 -y
'''

activate env

'''
conda activate wineq
'''

create a requirements.txt file

'''
touch  requirements.txt
'''

add required lib and in requirements.txt and install that.

'''
pip install -r requirements.txt
'''

create template.py file and add a project structure 

'''
touch template.py
'''

create a project structure by running

'''
python template.py
'''

download dataset from udc website

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

tox command -
""" tox"""

to rebuild tox -
""" tox -r """

pytest command -
""" pytest -v"""

setup commands - 
""" pip install -e ."""

build your own package command - 
""" python setup.py sdist bdist wheel"""

