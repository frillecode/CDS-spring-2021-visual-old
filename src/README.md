## Weekly assignments
Each week I will upload my answers to the given assignments here under the following names:
- __Assignment 1:__   
  - Code: _basic\_image\_processing.ipynb_  
- __Assignment 2:__ 
  - Code: _image\_search.py_   
  - Results: _out/distances.csv_
- __Assignment 3:__ 
  - Code: _edge\_detection.py_
  - Results: _out/image\_ROI.jpg_ , _out/image\_cropped.jpg_ , _out/image\_letters.jpg_


__Updating repo__  
To run the scripts, I recommend cloning this repository and installing relevant dependencies in a virtual ennvironment:

```bash
$ git clone https://github.com/frillecode/CDS-spring-2021-visual.git
$ cd CDS-spring-2021-visual
$ bash ./create_venv.sh
```
From then on, every time you use it, make sure to update the repository and install any new dependencies:
```bash
$ cd CDS-spring-2021-visual
$ git pull origin main
$ bash ./create_venv.sh
```
If you run into issues with some libraries/modules not being installed correctly when creating the virtual environment, install these manually by running the following:
```bash
$ cd CDS-spring-2021-visual
$ source frille-vis/bin/activate
$ pip install {module_name}
$ deactivate
```

__Running scripts__  
After updating the repo (see above), you can run the .py-files from the command-line by writing the following:
``` bash
$ cd CDS-spring-2021-visual 
$ source frille-vis/bin/activate
$ cd src
$ python3 {filename].py
```
