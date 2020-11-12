# datascience-courses

Hello everybody !   
Welcome to your first Data Science lecture !

In this course, you will discover an overview of our job content. You will find educational supports inside the `resources/courses/` folder, with the theoretical part in `slides/` subfolder, and the applied part in the `notebooks/`
subfolder.

This lecture will be focused on Data Science basics using [Python](https://www.python.org/), with a focus on data analysis and manipulation with [pandas](https://pandas.pydata.org/)  and [numpy](https://numpy.org/) and supervised learning with [scikit-learn](https://scikit-learn.org/stable/). You will also discover some visualizations with [matplotlib](https://matplotlib.org/) and [seaborn](https://seaborn.pydata.org/).

This course will be delivered by Yannick & Paul, data scientists at Betclic group.

## 🛠 Installation

All the 0. steps are optional, if you have already done them, go directly on the first step.

### 0.1 Install Python 
Download Python depending on your Operating System, on the following [webpage](https://www.python.org/downloads/). Please, choose a release with a **security** Maintenance status (3.6.x or 3.7.x) to avoid compatibility issues.
### 0.2 Install Git
Everything is explained on this [webpage](https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git).
### 0.3 Create a Kaggle account & join the Titanic competition
Register on [Kaggle](https://www.kaggle.com/). Then, join the [Titanic compete](https://www.kaggle.com/c/titanic)

### 1. Clone the course repository
Open a terminal, and run the following command.

```sh
git clone https://github.com/paulsteffen-lab/datascience-courses.git
```

### 2. Install requirements.txt
In the same terminal, change directory in the new folder downloaded with the previous command, and install all dependencies specified in the `requirements.txt` file with `pip`.

```sh
cd datascience-courses/
pip install -r requirements.txt
```

### 2. Download Titanic data
First, get a `kaggle.json` containing Kaggle username and key by following the procedure in **API credentials** in the following [webpage](https://github.com/Kaggle/kaggle-api#api-credentials) and place this file as described.  
Then, change directory in the data subfolder, and download titanic data with the following command.

```sh
cd resources/data/
kaggle competitions download -c titanic
```

Finally, unzip `titanic.zip`.
```sh
unzip titanic.zip -d titanic
```




