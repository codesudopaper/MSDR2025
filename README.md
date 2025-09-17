This repository contains the code, data, experiments, and evaluation of the proposed method for imitation learning (IL) methods. The project is organized into four main folders:

1. Demo_utility/
This folder contains the core Jupyter notebook, demo_utility.ipynb , for :

  Data Utility Scoring: Evaluation of different datasets.

  Data Cleaning: Implements the proposed data cleaning pipeline

2. Picknplace/
  This folder focuses on the pick-and-place task, containing all the necessary        components for data, models, and evaluation.

  data/: Contains the datasets used for training and testing.

  models/: Contains Jupyter notebooks for training various IL models and generating   rollouts for different methods.

  scoring/: Contains Jupyter notebook for calculating the value map and              evaluating the performance of different IL methods.

3. Weaving/
  This folder is dedicated to the weaving task, with a structure identical to the     Picknplace/ folder.
  
  data/: Stores the datasets specific to the weaving task.
  
  models/: Contains Jupyter notebooks for training and generating rollouts for IL         models.
  
  scoring/: Contains the notebook for scoring and evaluating the performance of IL     methods on this task.

4. Wiping/
  This folder contains all the materials for the wiping task, following the same       organized structure.
  
  data/: Stores the datasets for the wiping task.
  
  models/: Contains Jupyter notebooks for training and generating rollouts for IL     models.
  
  scoring/: Contains the notebook for scoring and evaluating the performance of       different IL methods for this task.

