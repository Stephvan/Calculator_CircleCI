# Calculator_CircleCI

 This project is to demostrate CI/CD using **CircleCI**

## Steps
 
  ###   Environment Set Up
 1. Create your repo on GitHub or your prefered version control system
 
 2. Set up the working environment by creating a virtual python environment. See steps below to create a virtual environment:
  
    ####   On Windows:
    
    - Open the Windows Command Prompt (show path via Start menu and keyboard shortcuts)
    

    ####   Mac OS / Linux
    - Open the Terminal program. This is usually found under Utilities or Accessories.
  

 3. Setup the pip package manager
 Check to see if your Python installation has pip. Enter the following in your terminal:
  
        pip -h
   

 4. Install the virtualenv package
 The virtualenv package is required to create virtual environments. You can install it with pip:

        pip install virtualenv


5. Create the virtual environment

    To create a virtual environment, you must specify a path. For example to create one in the local directory called ‘mypython’, type the following:

       virtualenv mypython

6. Activate the virtual environment

    You can activate the python environment by running the following command:
    
#### Mac OS / Linux

     source mypython/bin/activate

#### Windows

    mypthon\Scripts\activate

You should see the name of your virtual environment in brackets on your terminal line e.g. (mypython).

Any python commands you use will now work with your virtual environment
Deactivate the virtual environment

To decativate the virtual environment and use your original Python environment, simply type ‘deactivate’.

    deactivate
