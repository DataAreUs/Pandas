# Pandas

Virtual environment for pandas in VS Code, using miniconda
---------------------------------------------------------------------

Use the terminal or an Anaconda Prompt for the following steps:
<br> To create an environment: <br>
- To create an environment with a specific version of Python(I suggest installing python version similar to base environment in this case python :-3.9): <br><br>
 - conda create -n myenv python=3.9
   
<br> <br>

- Note:  Replace myenv with the environment name.  


- When conda asks you to proceed, type y: 
- proceed ([y]/n)?   <br><br>This creates the myenv environment in /envs/. No packages will be installed in this environment.

After creating this enviornment use this command

- conda activate myenv
 
install pandas for this specific environment

- pip install pandas

Now after this, install packages with **requirements.txt**,
in homework(**Workspace**) folder, make a new **.txt** file using **"textEdit"** or any text editor,
file should be containing these following lines

ipykernel<br>
numpy<br>
matplotlib<br>
seaborn<br>
scikit-learn<br>
scipy<br>
plotly<br>
pandas_profiling==3.1.0 

after saving the **requirements.txt** file run this command in terminal

- pip install -r requirements.txt







# for 
# ImportError: No module named pandas
# ModuleNotFoundError: No module named 'pandas'"
