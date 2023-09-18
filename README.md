<!-- image banner -->
<center>
<img src="documentation/md_imgs/banner.png" alt="drawing" height="200"/>
</center>


 For NMSU CS 488 Fall 2023 with Instructor: Dr. Tuan Le

## Setup Instructions

### Linux

1.  Clone the repository to a machine which has a local display (Does not work on a remote server headlessesly)
```bash
git clone https://github.com/JiveyGuy/Metorite_Data_Mine.git
```
2. cd into the directory
```bash
cd Metorite_Data_Mine
```
3. Setup a python virtual env
```bash
python3 -m venv .venv
```
4. Activate the environment
```bash
source .venv/bin/activate
```
5. Install dependencies
```bash
pip install -r requirements_linux.txt
```
6. Open the notebook in Visual Studio Code or in a Jupyter notebook. 
    * How to open in a Jupyter Notebook
        1. From terminal: 
        ```bash
        jupyter-lab
        ```

        3. Navigate to "[http://localhost:8888/](http://localhost:8888/)" in a web browser. 

        4. After it logs you in select `project.ipynb` on the left file menu.

## Other Documents

There are other doucemnt to help you get started with this repostiory:

* [Guide on contributing](CONTRIBUTING.md)
