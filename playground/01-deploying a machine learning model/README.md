# Deploying a Deep Learning model

A rapid guide to deploying a computer vision model trained to identify common objects in images, utilizing the YOLOv3 model and FastAPI.

## Setup

The `cd` command allows you to change directories. Assuming you are at the directory where you issued the cloning command, type the following on your terminal.

```bash
cd playground/01-deploying a machine learning model
```

This will bring you to the `01-deploying a machine learning model` directory. The `ls` command allows you to list the files and directories.
Type `ls` and let's take a quick look at the content inside `01-deploying a machine learning model` directory:

```
.
└── 01-deploying a machine learning model (this directory)
    ├── images (includes some images from ImageNet)
    ├── server.ipynb (Part 1 of the ungraded lab)
    ├── client.ipynb (Part 2 of the ungraded lab)
    └── requirements.txt (python dependencies)
```

## Python Virtual Environment with Conda

### Prerequisites: Have [conda](https://docs.conda.io/en/latest/) installed on your local machine.

You will use Conda as an environment management system so that all the dependencies you need for this ungraded lab are stored in an isolated environment.

Conda includes a lot of libraries so if you are only installing it to complete this lab , we suggest using [miniconda](https://docs.conda.io/en/latest/miniconda.html), which is a minimal version of conda.

### 1. Creating a virtual Environment

Now we assume that you either successfully installed conda or that it was previously available in your system. The first step is creating a new developing environment. Let's set a new environment with python 3.8 with this command:

```bash
conda create --name mlep-w1-lab python=3.8
```

After successfully creating the environment, you need to activate it by issuing this command:

```bash
conda activate mlep-w1-lab
```

At this point, you will do all your libraries installation and work in this environment. So, whenever working on this ungraded lab, check the mlep-w1-lab environment is active.

### 2. Installing dependencies using PIP

Before proceeding, double check that you are currently on the `01-deploying a machine learning model` directory, which includes the `requirements.txt` file. This file lists all the required dependencies and their respective versions.

Now use the following command to install the required dependencies:

```bash
pip install -r requirements.txt
```

This command can take a while to run depending on the speed of your internet connection. Once this step completes you should be ready to spin up jupyter lab and begin working on the ungraded lab.

### 3. Launching Jupyter Lab

Jupyter lab was installed during the previous step so you can launch it with this command:

```bash
jupyter lab
```

After execution, you will see some information printed on the terminal. Usually you will need to authenticate to use Jupyter lab. For this, copy the token that appears on your terminal, head over to [http://localhost:8888/lab](http://localhost:8888/lab) and paste it there. Your terminal's output should look very similar to the next image, in which the token has been highlighted for reference:

![Token in terminal](./assets/token.png)

### 4. Running the notebook

Within Jupyter lab you should be in the same directory where you used the `jupyter lab` command.

Look for the `server.ipynb` file and open it to begin the ungraded lab.

To stop jupyter lab once you are done with the lab just press `Ctrl + C` twice.

### And... that's it! Have fun deploying a Deep Learning model! :)

Based on [Machine Learning Engineering for Production (MLOps) Specialization](https://www.deeplearning.ai/courses/machine-learning-engineering-for-production-mlops/) by Andrew Ng, Laurence Moroney, and Robert Crowe (2023).
