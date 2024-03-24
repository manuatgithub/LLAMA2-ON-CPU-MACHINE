# LLAMA2-ON-CPU-MACHINE


### Step 1:

clone the repository

git clone Path from github

create virtual environement

### Step 2:

create virtual environement

conda create -n cpullama python =3.8 -y

conda activate cpullama

install requirements

pip install -r requirements.txt


### ERROR :
ERROR: Could not build wheels for greenlet, which is required to install pyproject.toml-based projects
(cpullama) manu@Manoharans-MacBook-Air LLAMA2-ON-CPU-MACHINE % pip list

### Solution:
pip install --only-binary :all: greenlet
pip install --only-binary :all: Flask-SQLAlchemy


