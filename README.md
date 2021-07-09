# Project_02 
### Daniel Dickey - A02263117


## Welcome
* Read ___Report.pdf___ for info about the project, results, and my conclusion. 
* Read ___Files___ below for information on what is contained in each file in this project.
* Read ___Set-Up___ below for instructions on how to install the required software to run this project on _Windows 10_.


## Files
* __Report.pdf__ - contains a description, tables, and info about this project.
* __README.md__ - should be read before attempting to run any files.
* __main.py__ - _run_ this file to produce a report of each type of net run against each dataset.
* __utils.py__ - contains all the functions required to
  validate, train, test, predict, save nets, load nets, create and load ensembles.
* __load_nets.py__ - contains all the loader functions required load the three CNNs.
* __buzz1_cnn.py__ - used to train, save, rename a CNN on the buzz1 dataset.
* __buzz1_cnn.py__ - used to train, save, rename a CNN on the buzz2 dataset.
* __buzz1_cnn.py__ - used to train, save, rename a CNN on the buzz3 dataset.
* __single_cnn.py__ - used to train, save, rename a CNN on all 3 datasets.
* __rf.py__ - used to train, save, load, and validate the random forest. 
* __/nets__ - folder containing the .tfl files that make up the trained CNNs used in this project. 
    Each net has three files associated with it. 
    This folder also contains a single .pck file with the random forest saved in it.


## Set-up
* The curated and labeled "audio clips" used for training, testing, and validating is available at:
  https://usu.app.box.com/s/2awuc4l9xqui2ea4u6p5p1gmp2advc1z 
  
* This project utilized:
  * ___Anaconda Prompt 3 (conda 4.8.5)___
  * ___Python 3.7.4___
  * ___pip 20.2.3___
  * ___numpy 1.19.2___
  * ___Tensor Flow v1.4.0___
  * ___TF Learn 0.3.2___
  * ___pickle 4.0___
    
* I ran this project on ___Windows 10___ using ___Anaconda Prompt 3 (conda 4.8.5)___
  
* To install Anaconda Prompt 3:
    * Download the Anaconda installer at https://www.anaconda.com/download/#windows 
    * Double click the installer to launch.
    * Click Next.
    * Read the licensing terms and click “I Agree”.
    * Select an install for “Just Me” unless you’re installing for all users (which requires Windows Administrator privileges) and click Next.
    * Select a destination folder to install Anaconda and click the Next button.
        * Install Anaconda to a directory path that does not contain spaces or unicode characters.
        * Do not install as Administrator unless admin privileges are required.
    * Choose whether to add Anaconda to your PATH environment variable. We recommend not adding Anaconda to the PATH environment variable, since this can interfere with other software. Instead, use Anaconda software by opening Anaconda Navigator or the Anaconda Prompt from the Start Menu.
    * Choose whether to register Anaconda as your default Python. Unless you plan on installing and running multiple versions of Anaconda or multiple versions of Python, accept the default and leave this box checked.
    * Click the Install button. If you want to watch the packages Anaconda is installing, click Show Details.
    * Click the Next button.
    * Optional: To install PyCharm for Anaconda. Or to install Anaconda without PyCharm, click the Next button.
    * After a successful installation you will see the “Thanks for installing Anaconda” dialog box.
    * If you wish to read more about Anaconda.org and how to get started with Anaconda, check the boxes “Anaconda Individual Edition Tutorial” and “Learn more about Anaconda”. Click the Finish button.
    
__The Follow Commands are all run from the _Anaconda Prompt_:__

* To install ___Python 3.7.4___:
    *       conda install python=3.7.4
    
* To install ___pip___:
    *       python -m pip install --upgrade pip
    or 
    *       conda install pip
    *       conda update pip  
    
* To install ___NumPy___:
    *       pip install numpy
    *       pip install --upgrade numpy
    
* To install ___Tensor Flow v1.4.0___:
    *       conda install -c conda-forge tensorflow=1.14
    or 
    *       conda install tensorflow=1.14
    
* To install ___TF Learn___:
    *       conda install -c derickl tflearn
    or 
    *       conda install tflearn
    
* To install ___pickle___:
    *       pip install pickle-mixin
    or
    *       conda install pickle   
    # BeeAI
