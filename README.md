# Instructions

Download workshop materials:

```bash
mkdir max_tree
cd max_tree
wget https://github.com/pbosilj/scikit-image-maxtree/raw/build/install.sh -O - | sh 
```

Install python3.7 if missing:

```bash
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.7
```

Create virtual environment:

```bash
python3.7 -m venv max_tree_venv --clear
source max_tree_venv/bin/activate
```

Install dependancies:

```bash
pip install scikit_image-0.17.dev0-cp37-cp37m-linux_x86_64.whl
pip install jupyterlab
```
