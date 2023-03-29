# Getting Ready for the First Workshop

During the workshops, we will work with Jupyter notebooks. We strongly advise you to complete the following steps **before** the first workshop session. We will discuss the intuition behind every step during Workshop 1. 

## 1. Git and GitHub

If you read this, you managed to find our GitHub repository for DSML - good job! Git is an open-source distributed version-control system. This repository hosted on GitHub allows us to share code, small data snippets, course information etc. with you. For each workshop there will be a so-called Juypter notebook, which you can find in the [02_Workshops](../02_Workshops) folder. You can either **download this repository by clicking on the green Code button on the main page** or, for more advanced users, clone it onto your local machine.

## 2. Anaconda or Miniconda

We will be using the open-source Python programming language. We recommend using the Anaconda or Miniconda distribution of Python. You can choose one of two options:
- Option 1 (probably the easiest): Install the full Anaconda version, which comes with a lot of pre-installed packages (incl. Jupyter Notebook) and a package manager graphical user interface (GUI). **It is available for download [here](https://www.anaconda.com/distribution/).**
- Option 2 (for slightly more advanced users and if you are short on disk space): Install the much lighter Miniconda distribution which essentially is just the Conda package manager and Python. From there your can simply install Python packages as required via the Terminal (Mac) or the Command Prompt (Windows). **Miniconda is available for download [here](https://docs.conda.io/en/latest/miniconda.html).**

## 3. Installing Required Packages

After installing either Anaconda or Miniconda, let's take care of downloading some packages you will need. First, open up a terminal:
- If you are on a **Windows** computer, use the "Anaconda Prompt" from the Start menu. 
- On a **Mac**, start up the "Terminal". 
- In **Linux**, use any of the terminals available.

### 3.1 In case you installed Anaconda
If you have installed the full Anaconda distribution, to ensure all your packages are up to date, run the following two commands consecutively:
```
conda update -n base conda
conda update jupyter numpy scipy matplotlib pandas
```

### 3.2 In case you installed Miniconda
If you have installed the Miniconda distribution, which comes without any pre-installed packages, run the following commands consecutively:
```
conda update -n base conda
conda install jupyter
conda install jupyter lab
conda install numpy scipy matplotlib pandas
```
You might be asked to confirm before installing a package (y/n?). Confirm by typing y and hit enter.

You can easily check which packages are installed by executing the following command in your terminal:
`conda list`

## 4. Launch Jupyter Notebook

As mentioned before, we will be using Jupyter Notebooks throughout the workshops. Notebooks are a convenient way to thread text, code and the output it produces in a simple file that you can then share, edit and modify. You can think of notebooks as the **Word document of Data Scientists**. Jupyter is a browser-based coding environment. If you managed to complete all previous steps successfully, you should be able to launch Jupyter by doing the following:
1. Start up a terminal (as described above).
2. Type the following command:
`conda activate base`
3. Launch Jupyter by typing:
`jupyter notebook`

This should bring up a browser window with a homepage showing all your folders and files. As mentioned earlier, we will upload a Jupyter Notebook file (.ipynb) shortly before the start of every workshop. Make sure to download it. Once you have the notebook file downloaded, you can navigate to it and open it up within the Jupyter Notebook server you just launched.


## 5. Final Remarks

If you worked through the steps and were able to launch the Jupyter Notebook server you are ready to go for the first workshop! If you got stuck somewhere, don't worry! We will shortly go over the process once again during Workshop 1. Additionally, you can find an abundance of information and support on the internet.

See you on Wednesday!
