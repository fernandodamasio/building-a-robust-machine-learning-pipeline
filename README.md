# Building a Robust Machine Learning Pipeline

## Download and Install Anaconda

The open source Anaconda Distribution is the fastest and easiest way to do Python, data science and machine learning on Linux, Windows, and Mac OS X. It's the industry standard for developing, testing, and training on a single machine.

Download and install the latest version: [https://www.anaconda.com/download/](https://www.anaconda.com/download/)

VIDEO TUTORIAL: [Python - Install Anaconda, Jupyter Notebook, Spyder on Windows 10](https://www.youtube.com/watch?v=Q0jGAZAdZqM)

## Create a Conda Environment

1. To create a new environment, type:

```
conda create -n ml27 python=2.7
```

2. When conda asks you to proceed, type y:

```
proceed ([y]/n)?
```

3. After this process, check if the environment was created. To see a list of all of your environments, run:

```
conda info --envs
```

4. Activate the Environment. In your Anaconda Prompt, run:

```
(source) activate ml27
```

Use source if you are working on iOS or Linux, only.

## Install Aditional Packages:

In the Anaconda Prompt, run:
```
conda install pandas
```
```
conda install numpy
```
```
conda install time
```
```
conda install scipy
```
```
conda install scikit-learn
```
```
conda install jupyter notebook
```
```
conda install seaborn
```

## Open the Notebook

In the Anaconda Prompt, run:

```
jupyter notebook
``` 
And navigate to the .ipynb file
