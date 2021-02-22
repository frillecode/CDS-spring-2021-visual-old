### Weekly assignments
Each week I will upload my answers to the given assignments here under the following names:
- W1: _basic\_image\_processing.ipynb_  
- W3: _image\_search.py_  

__Updating repo__  
To run the scripts, I recommend cloning this repository and installing relevant dependencies in a virtual ennvironment:

```bash
$ git clone https://github.com/frillecode/CDS-spring-2021-visual.git
$ cd CDS-spring-2021-visual
$ bash ./create_frille-visual_venv.sh
```
From then on, every time you use it, make sure to update the repository and install any new dependencies:
```bash
$ cd CDS-spring-2021-visual
$ git pull origin main
$ bash ./create_frille-visual_venv.sh
```
If you run into issues with pandas not being installed correctly when creating the virtual environment, install pandas manually by running the following:
```bash
cd CDS-spring-2021-visual
source frille-vis/bin/activate
pip install pandas
deactivate
```
__Running scripts__  
After updating the repo (see above), you can run the .py-files from the command-line by writing the following:
``` bash
$ cd CDS-spring-2021-visual/src
$ python3 {filename].py
```
