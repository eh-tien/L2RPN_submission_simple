This repository is designed to minimise the amount of time needed to create a working agent for the L2RPN challenge. 
---------------------------
This README is designed to walk through the process.


# **The first two steps deal with necessary installations, most users can skip these steps.**
# -------------------------------------------------------------------
## A. Jupyter Notebook installation
Please install Jupyter Notebook in order to use the `.ipynb` file which is the file that will create the model.
In order to do this, you must have Python installed (https://www.python.org/downloads/) so that you can install Jupyter.
For Mac/Linux and Windows, the installation is the same. Simply go to either the terminal or command prompt and enter `pip install notebook`.

## B. Git installation
In order to clone the repository (recommended), you will need to install Git. This can be downloaded from https://git-scm.com/downloads. After this, you should have `git` commands available to you.

# -------------------------------------------------------------------

## 1. Downloading the repository
### 1.1 Cloning the repository (Recommended)
In order to clone the repository, navigate to the top of the repository and click the green code button as seen below. <br />


<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/repo%20download%20step%201.png" alt="alt text" width="1000" height="600"> <br />

After this, click the save button as seen below. <br />
<br />
<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/repo%20download%20step%202(clone).png" alt="alt text" width="600" height="400"> <br />
<br />
This will copy the HTTPS link to the repository. You will need to paste this later.

Now, open up the Terminal (if you're on Mac/Linux) or Command Prompt (if you're on Windows).
For ease of access to the file, change your working directory to wherever is convenient to store the repository.
For demonstration, I will change my working directory to 'Desktop'.<br /> 

**THE FOLLOWING CODE DOES NOT CONTAIN ANY SPECIFIC USER AND MUST BE ENTERED BY YOU PERSONALLY.**

**Mac/Linux**: 
* `cd /Users/USER/Desktop`

**Windows**: 
* `cd \Users\USER\Desktop`

Now that you are in your preferred directory, enter `git clone` followed by the paste of what you copied above. It should look like this: <br />
`git clone https://github.com/eh-tien/L2RPN_submission_simple.git` <br />
If you didn't get this it is not a problem, simply copy the above line of code into Terminal / Command Prompt.

This should start a download and create the repository locally in your designated directory.

#### 1.1.1 Updating the repository
In order to have the latest version of the repository:
* Change directory to wherever the clone is. For example, if the clone was located on your desktop, you would enter the following command into Terminal or Command Prompt respectively: <br />
`cd /Users/USER/Desktop/L2RPN_submission_simple` <br />
`cd \Users\USER\Desktop\L2RPN_submission_simple` <br />

* Now that you're in the correct directory, enter the following command in Terminal / Command Prompt: <br />
`git pull` <br/>

This will start the updating process and you will have the latest version of the repository.
 

# -------------------------------------------------------------------


### 1.2 Downloading the .zip file
In order to clone the repository, navigate to the top of the repository and click the green code button as seen below. <br />

<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/repo%20download%20step%201.png" alt="alt text" width="1000" height="600"> <br />
Then click the Download ZIP button, highlighted below. <br />

<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/repo%20download%20step%202(zip).png" alt="alt text" width="600" height="400"> <br />

**Please note that in order to avoid errors down the line, the file should be saved as:** <br /> 
<br />
**L2RPN_submission_simple.zip** <br /> 
<br />
and unzipped to be <br />
<br />
**L2RPN_submission_simple** <br />
<br />
This is why it is recommended to clone the repository. <br />
# -------------------------------------------------------------------
# 2. Launching Jupyter Notebook
In order to launch Jupyter Notebook, go to the Terminal / Command Prompt and enter the following: <br />
`cd /Users/USER/Desktop/L2RPN_submission_simple` or wherever your designated directory is located. <br /> 
Then run the following:
`jupyter notebook` <br />
If this does not work, enter: <br />
`python -m notebook` or <br />
`python3 -m notebook` <br />.
<br />
You should be presented with the following page: <br /> 
**NOTE: The page you are presented with may look slightly different due to updates, however this is nothing to worry about.** <br />
<br />
<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/jupyter%20landing%20screen.png" alt="alt text" width="1000" height="400"> <br />
<br />
After this, click on **start-to-end-notebook.ipynb** and you will be brought to the main notebook. <br />
<br />

<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/notebook.png" alt="alt text" width="1000" height="600"> <br />
<br />
Now you are in the main notebook and there are more instructions on how to proceed there.
