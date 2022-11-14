# Running Jupyter Notebooks Locally - Lab

## Introduction
Now that we have had an introduction to the command line, have seen how to clone GitHub repos to our local machine (our computer), and have seen some common Jupyter Notebook operations, it's time to put our skills to the test!

## Objectives
You will be able to:
* Use basic commands to navigate the command line
* Use bash commands to create new files and folders
* Use `git clone` to clone a repository
* Perform cell operations within Jupyter Notebooks

## Setup

Remember from the last lesson, you need to:
1. Click on the "GitHub" logo in the top right of the Canvas Assignment (go back to the previous page if you already loaded the Lab in SaturnCloud!)
2. Fork the repository on GitHub so you have your own copy there
3. Copy the URL of your repository
4. Open a terminal window (terminal on a Mac, Git Bash on Windows)
5. Make sure to activate your conda virtual environment so you have the right version of Python and all of the necessary packages. On a mac or in Git Bash on Windows, type `source activate learn-env`. (If you *have* to use the conda shell on windows, type `activate learn-env` instead).
6. Clone (download) the files to your hard drive by typing `git clone ` and then pasting the URL of your repo you saved in step 3.
7. Type `cd ` followed by the name of the directory you just created (running the `ls` command will show you the name of the directory you downloaded) 
7. Run the `jupyter notebook` command to start up Jupyter, and in the browser window that opens, navigate to and click on the `index.ipynb` notebook.

## Instructions

Assign the below variable `number` to the number `42` by replacing `None` with `42`.


```python
number = None
number
```

Next, like the above, reassign the `flatiron_mantra` variable with the string `"Change Things"` (make sure to include the double quotes!) 


```python
flatiron_mantra = None
flatiron_mantra
```

Add a new markdown cell below this one and type `### This is a new header`

Now add a new code cell below this one and write whatever code you want to write.

As you can see, this works just the same as editing Jupyter notebooks using cloud tools, only now it's on your computer.

## Summary
Great work! We are well on our way to mastering Jupyter notebooks! We reviewed using the command line and `git clone`, running cells, and checking our outputs.
