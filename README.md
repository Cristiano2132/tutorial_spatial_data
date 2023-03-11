To run the tutorial in your machine, follow the next steps. 

  

1. Open the terminal and go to the directory where you want to keep the repository. 

  

2. Clone the Directory typing: `git clone git@github.com:Cristiano2132/tutorial_spatial_data.git`

 

3. Install Python 3.10 on your computer if it is not installed. 

 

4. Find python 3.10 path. Type the command: `where python3`

Output Example: `/Library/frameworks/python.framework/versions/3.10/bin/python3`

  

5. Create a virtual environment 

	5.1. go to the project directory, type: `cd tutorial_spatial_data`

	5.2. create the venv, type: `python3 -m virtualenv -p /Library/Frameworks/Python.framework/Versions/3.10/bin/python3 .venv`

Remember,  `/Library/Frameworks/Python.framework/Versions/3.10/bin/python3` is the python 3.10 path found in step 4. 

6. Activate the virtual environment, type: `source .venv/bin/activate`

 

7. Install the dependencies: `pip install -r requirements.txt`

 

8. Congratulations, now you are able to run the tutorial. 
