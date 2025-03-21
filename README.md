# Algorithms-and-Data-Structures-Labs
work from labs


# sites to help learn and practice:
https://projecteuler.net/
https://codegolf.stackexchange.com/
http://codekata.com/
https://www.reddit.com/r/dailyprogrammer/?rdt=55046
https://programmingpraxis.com/
https://rosettacode.org/wiki/Main_Page

# Reading
https://link.springer.com/
Data Structures and Algorithms: A First Course
• Algorithms and Data structures: The Basic Toolbox
• An Introduction to Data Structures and Algorithms
• Data Structures and Algorithms with Python
• A Concise and Practical Introduction to Programming Algorithms in Java

# git learning
1. Github’s Learn Git 15 minute tutorial: https://try.github.io/levels/1/challenges/1
2. Learn Git Branching http://pcottle.github.io/learnGitBranching/
3. Git Immersion http://gitimmersion.com/lab_01.html


## initial dir structure

ai_project/  
├── data/  # Store datasets (raw, processed, and external)
│   ├── raw/  
│   ├── processed/  
│   ├── external/  
│   └── README.md  
├── notebooks/  # Jupyter notebooks for experimentation
│   ├── 01_data_exploration.ipynb  
│   ├── 02_model_training.ipynb  
│   ├── 03_evaluation.ipynb  
│   └── README.md  
├── models/  # Save trained models and weights
│   ├── checkpoints/  
│   ├── final_model.pth  
│   └── README.md  
├── src/  # Source code for the project
│   ├── data_processing.py  
│   ├── model.py  
│   ├── train.py  
│   ├── evaluate.py  
│   ├── predict.py  
│   └── __init__.py  
├── tests/  # Unit and integration tests
│   ├── test_data_processing.py  
│   ├── test_model.py  
│   ├── test_train.py  
│   ├── test_evaluate.py  
│   └── README.md  
├── configs/  # Configurations for hyperparameters, paths, etc.
│   ├── config.yaml  
│   ├── model_config.json  
│   └── README.md  
├── logs/  # Logs for debugging and performance tracking
│   ├── training.log  
│   ├── evaluation.log  
│   └── README.md  
├── docs/  # Documentation (setup guides, project reports, etc.)
│   ├── setup.md  
│   ├── usage.md  
│   ├── api_reference.md  
│   ├── architecture.md  
│   └── README.md  
├── scripts/  # Utility scripts for automation
│   ├── preprocess.sh  
│   ├── train.sh  
│   ├── evaluate.sh  
│   ├── predict.sh  
│   └── README.md  
├── requirements.txt  # Dependencies
├── environment.yml  # Conda environment file (optional)
├── setup.py  # Setup script for packaging (optional)
├── README.md  # Project overview
├── .gitignore  # Ignore unnecessary files
└── LICENSE  # License information
