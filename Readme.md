Growth Challenge

Using this course: https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp

1/1/2021

Setup this repo

Watched course intro

Installed Anaconda - sort of - no icons but command line works

1/2/2021

Ran Jupyter via:
> jupyter notebook
(from home directory)

Downloaded the course materials
Opened the first example notebook.
Watched the environment setup video

1/4/2021

Watched the Jupyter Notebooks video and tried out JN

1/5/2021

Watched the Python Crash Course lectures (very quickly)
Created ssh key for github via ssh-keygen
Started ssh agent:
eval "$(ssh-agent -s)"
Added key:
ssh-add ~/.ssh/id_github
Copied public key to clipboard:
xclip -selection clipboard < ~/.ssh/id_github.pub
In GitHub, Profile, Settings, I added this ^ key
Then I reconfigured this repo to use ssh:
git remote set-url origin git@github.com:andythummel/python-for-data-science-bootcamp-udemy.git




TODO:

Setup ssh key for easier github interaction

Setup git command line aliases

