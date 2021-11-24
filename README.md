# Instructions to run the project
Create an anaconda environment with the command - `conda create -n "env_name" python==3.7.5`

activate the environment using the command - `conda activate env_name`

Install Tensorflow-1.14.0 package using the command - `conda install -c conda-forge tensorflow=1.14.0`

Install all the packages from 'requirements.txt' file using the command - `pip install -r requirements.txt`

Now, Navigate to Gen and Scale folder and run the command - `python main.py` to run the Joint-Learning generative model and Score-scaling model respectively.

Now, navigate to 'Data/ml1m' folder and run 'cold_bias_analysis_ColdRec.ipynb' and 'cold_bias_analysis_Debias.ipynb' files in Jupyter Notebook.
