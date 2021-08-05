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
In order to download the .zip of the repository, navigate to the top of the repository and click the green code button as seen below. <br />

<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/repo%20download%20step%201.png" alt="alt text" width="1000" height="600"> <br />
Then click the Download ZIP button, highlighted below. <br />

<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/repo%20download%20step%202(zip).png" alt="alt text" width="600" height="400"> <br />

If you decide to download the .zip file, it will be renamed to: <br />
<br />
**L2RPN_submission_simple-master.zip** <br />
<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/zip%20before.png" alt="alt text" width="200" height="200"> <br />
<br />
and will unzip to: <br />
<br />
**L2RPN_submission_simple-master** <br />

<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/folder%20before.png" alt="alt text" width="200" height="200"> <br />
<br />
<br />
**PLEASE DO THE FOLLOWING:** <br /> 
* Once unzipped, delete the .zip file (it is unnecessary and may add to confusion later.)
* Rename the unzipped folder to **L2RPN_submission_simple.** <br />

 Before: <br />

<img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/folder%20before.png" alt="alt text" width="200" height="200"> <br />

 After: <br />
 
 <img src="https://github.com/eh-tien/L2RPN_submission_simple/blob/master/images/folder%20after.png" alt="alt text" width="200" height="200"> <br />


The code will still run, however where things are saved to will not be intuitively obvious and as such will lead to unnecessary confusion. 
<br />

**NOTE:** On some machines, the above steps may not be sufficient. A situation could arise where the unzipped folder contains an internal folder with the same name as the parent. For example, the folder **L2RPN_submission_simple-master** will contain a folder of the same name. The internal folder needs to be taken out of the parent folder and placed either in the same directory (E.g Downloads) or moved to the Desktop or anywhere else. It just needs to be moved from the parent folder. After this, the parent folder can be deleted and you can proceed as though you had just unzipped the initial file.

This is why it is recommended to clone the repository.
# -------------------------------------------------------------------
# 2. Launching Jupyter Notebook
In order to launch Jupyter Notebook, go to the Terminal / Command Prompt and enter the following: <br />
<br />
* `cd /Users/USER/Downloads/L2RPN_submission_simple` (for Terminal) <br />
* `cd \Users\USER\Downloads\L2RPN_submission_simple` (for Command Prompt) <br />
or change directory to wherever your designated directory is located. <br /> 


Then run the following: <br />
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

# -------------------------------------------------------------------
# 3. Submitting to CodaLab
Now that you have successfully created a working agent, the process for submitting to CodaLab is relatively straight forward. 
After the model was tested in the Jupyter Notebook, a .zip file containing the model was created in the **L2RPN_submission_simple** folder.
To submit to CodaLab do the following: (If you already have a CodaLab account, skip steps A. and B.)
# -------------------------------------------------------------------
A. Go to this URL: https://competitions.codalab.org/accounts/signup/?next=/
B. Create a CodaLab account if you have not done so already.
# -------------------------------------------------------------------
1. Go to this URL: https://competitions.codalab.org/competitions/33121#participate-submit_results 
2. Click the Submit button **insert photo**
3. Navigate to the location of your .zip file **insert photo**
4. Click open **insert photo**
5. Now you're done! The model will be scored and the result will be made available to you on the public leaderboard in a few minutes. Good luck!
