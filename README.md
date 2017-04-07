# Applied Data Science
This repo accompanies the coourse "Applied Data Science", given by Dr. Omri Allouche in Bar Ilan University during Spring 2017.
The notebooks were created by the course teacher or taken from various sources on the web, including:
- [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) (Book, Paid)
- [Complete Python Bootcamp](https://www.udemy.com/complete-python-bootcamp/?couponCode=PY20) on Udemy (Video course, Paid). The course's Jupyter Notebooks are [here](https://github.com/jmportilla/Complete-Python-Bootcamp)
- [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/python-for-data-science-and-machine-learning-bootcamp/learn/v4/overview) on Udemy

I strongly recommend that you review these resources. The course slides include recommendations to additional resources on various course topics.


## Setup Anaconda
Download [Anaconda](https://www.continuum.io/downloads) for your operating system. Make sure you select the Python 3.6 version, and complete the installation.

### Adding Python 3 to Anaconda installed with Python 2
If you've installed Anaconda with Python 2, you can create a new virtual environment with Python 3 with the following steps. 
1. Open the Anaconda Prompt command, and type:
```
$ conda create -n py35 python=3.5 anaconda
$ conda update python
```
Note that the `$` sign is used to indicate the command prompt, and shouldn't be typed.

1. Make sure that you have python installed:
```
$ python --version
```
The python program should be recognized and you should see Version 3 returned for Python.

1. Make sure the Jupyter Notebook Server runs properly:
```
jupyter notebook
```

Your browser should open with the Jupyter notebook server. The server starts at your current directory. You should first change directory to your course's git folder and then run `$ jupyter notebook`.  
See below on how to clone the course repository to your local computer.

2. You can now switch between versions of Python by typing:
```
activate py35
```

In Jupyter notebook, you should have Python 3 available as one of the kernels.

## Setup Git
You'll need to have an account on GitHub to use this course.

Git allows you to manage your work in versions, thereby comparing versions, reverting to previous versions, pulling latest changes from the remote repo, and pushing your changes to the repo (e.g. for submitting your homework).  
If you're not comfortable working with Git using the command line, I suggest you use the GitHub Desktop tool.
You can view a video on setting up the repo locally [here](https://youtu.be/ywCaMLo2VLc) (apologies for the low sound quality). 

### Recommended resources for Git
- [DataQuest Guide](https://www.dataquest.io/course/git-and-vcs)
- Data School’s [Version control with Git and GitHub](https://www.youtube.com/playlist?list=PL5-da3qGB5IBLMp7LtN8Nc3Efd4hJq0kD) YouTube Playlist
- Data School's [Simple Guide to Forks in GitHub and Git](http://www.dataschool.io/simple-guide-to-forks-in-github-and-git/)
- [GitHub guide on forking a repo](https://help.github.com/articles/fork-a-repo/)
- [Atlassian Guide](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)


