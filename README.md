# PythonForBiochemists
Programming skills for biochemists, in Python
This repository is a collection of coding 'notebooks' that you can use to learn general aspects of Python (tutorials), as well as skills specific to Biochemists (topics).  

If you know what you're doing with Python and git, you should be able to use this repository already.  Otherwise, please follow the instructions in the next section to get you going.

## If you're completely new to Python, start here.
The first step is to get a working Python environment setup.  We won't use your system's default setup, as it's best not to mess with that.  
After that, we'll use a tool called *Git* to download this *repository*.  Git is a program for doing *version control*, a way of keeping track of changes to our work so we can go back to any point at any time.  Git is also good for integrating changes from lots of people, so a whole team can work on the code at the same time and not destroy each other's work.  
Finally, we'll do most of our coding in *Jupyter Lab*, a browser based coding environemnt that lets you mix text, pictures, live code and more together.  

These instructions require you to have administrator access to your computer.  If your computer is managed by your organization, use the relevant program installer to setup Anaconda rather than these instructions.
1.  Go to https://www.anaconda.com/products/individual and download the Anaconda installer.
2.  Install Anaconda on your system.
3.  MACs: open a terminal and run `xcode-select --install` to install some additional required libraries.

Now we create a new Anaconda *environment*, which will let us isolate our Python setup from the rest of the system.  Having a separate environment for each project lets us play around without fear of messing up something else that's already working.  We'll see what each of the tools we're installing are for in due course.  One thing to note here: we don't explicitely install Python - you'll see that it gets installed as a dependency of all the tools we actually ask to install.
*  Command line:
    ```
    conda create -n pythonforbiochemists
    conda activate pythonforbiochemists
    conda install -y numpy matplotlib scipy pandas jupyterlab
    ```
*  GUI:
    1. Open the Anaconda Navigator app SS
    2. Click on "Environments" SS
    3. Create a new environment called 'pythonforbiochemists' SS
    4. Click on 'update index' SS
    5. Select these packages for install: numpy, matplotlib, scipy, pandas, jupyterlab SS
    6. Click on 'apply' and accept that ~100 packages will actually be installed.

Now, we'll choose a download location for the tutorial (here, we'll use a folder called 'Documents',) and download this repository using Git (you can get the URL for a repository by clicking on the green box labeled 'Code'. SS)  *There are only command-line instructions for now:*
*  Command line:
    ```
    cd Documents
    git clone https://github.com/LISCB/PythonForBiochemists.git
    cd PythonForBiochemists
    ```

Finally, we can start open *Jupyter Lab*
*  Command line:
    1. `conda activate pythonforbiochemists` (You've already done this, but you'll need to do it anytime you want to use this environment.  Running it multiple times doesn't hurt.)
    2. `jupyter-lab`
*  GUI:
    1. Go back to the home screen. SS
    2. Make sure you select the 'pythonforbiochemists' environment. SS
    3. Run Jupyter Lab. SS
    4. On the left-hand side, navigate to where you cloned this repo. SS

Because this repository will continue to be updated, it's best for you to copy notebooks before working on them.  Otherwise you'll have to merge your changes if you want to stay up-to-date.

1. Navigate into the `tutorials` folder. SS
2. Right click on notebook 1 and duplicate it. SS
3. Double click on the new copy. SS
4. Follow the directions to complete Tutorial 1. SS

## Continuing updates
This repository will continue to be updated with new tutorials and topics as the Python community within LISCB grows.  In order to the latest updates, just go into the `PythonForBiochemists` directory and run `git pull`.
