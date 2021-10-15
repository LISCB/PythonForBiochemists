# PythonForBiochemists
Programming skills for biochemists, in Python
This repository is a collection of coding 'notebooks' that you can use to learn general aspects of Python (tutorials), as well as skills specific to Biochemists (topics).  

If you know what you're doing with Python and git, you should be able to use this repository already.  Otherwise, please follow the instructions in the next section to get you going.

## If you're completely new to Python, start here
The first step is to get a working Python environment setup.  We won't use your system's default setup, as it's best not to mess with that.  
After that, we'll use a tool called *Git* to download this *repository*.  Git is a program for doing *version control*, a way of keeping track of changes to our work so we can go back to any point at any time.  Git is also good for integrating changes from lots of people, so a whole team can work on the code at the same time and not destroy eachother's work.  
Finally, we'll do most of our coding in *Jupyter Lab*, a browser based coding environemnt that lets you mix text, pictures, live code and more together.  

These instructions require you to have administrator access to your computer.  If your computer is managed by your organization, use the relevant program installer to setup Anaconda.
1.  Go to https://www.anaconda.com/products/individual and download the Anaconda installer.
2.  Install Anaconda on your system.
3.  Once Anaconda is installed, install *Git* either by using the command line: `conda install git`, or the Anaconda GUI:  
4.  **PUT SCREENSHOT HERE**

Now we create a new Anaconda *environment*, which will let us isolate our Python setup from the rest of the system.  Having a separate environemnt for each project lets us play around without fear of messing up something else that's already working.  We'll see what each of the tools we're installing are for in due course.  One thing to note here: we don't explicitely install Python - you'll see that it gets installed as a dependency of all the tools we actually ask to install.
*  Commandline:
    ```
    conda create -n pythonforbiochemists
    conda activate pythonforbiochemists
    conda install numpy matplotlib scipy pandas jupyterlab
    ```
*  GUI:
    1. XXX
    2. XXX

Choose a download location (here, we'll use a folder called 'Documents',) and download this repository using Git (you can get the URL for a repository by clicking on the green box labeled 'Code'.)
*  Commandline:
    ```
    cd Documents`
    git clone https://github.com/LISCB/PythonForBiochemists.git`
    cd PythonForBiochemists
    ```
*  GUI:
    1. XXX
    2. XXX

Finally, we can start with tutorial 1
*  Commandline:
    1. `jupyter-lab`
    2. XXX
*  GUI:
    1. XXX
    2. XXX
