Netflix Movie Recommender 
A movie recommendation system built in Jupyter Notebook that suggests Netflix movies based on your input.


Step 1: Download Dataset
		First, download the dataset (netflix_titles.csv) from Kaggle. Here’s how:

		1.Go to this Kaggle dataset link(https://www.kaggle.com/datasets/shivamb/netflix-shows)
		2.Download the dataset and save the file netflix_titles.csv on your computer.
	
Step 2: Create a New Environment
		We will create a new virtual environment for this project. You can use either Anaconda or Python's built-in venv tool.

		 1.Create a New Environment
			a. Open a terminal (or Anaconda Prompt on Windows):   IF first  download and install python "https://www.python.org/downloads/"
			b. Now verify  python and pip version with these two commands
				python --version
				pip --version

			c.Run the below command to install jupyter notebook
				pip install notebook

			d.Now run the below comand to create new environment
				python -m venv hasham          #  hasham is the name of env  , you can use any name like lumma for this project
			e.Activate the env 
				hasham\Scripts\activate       # use your env name 
			f. Run  requirements.txt  for necessary libraries  
				 pip install -r .\requirements.txt

				and verfify the installation with the command
				pip list		

Step 3. Running the System

	a. Open the Notebook   and	Open the recommendation_system.ipynb
	Step 2: Run All Cells
	Step 3: Provide Your Input
	Step 4: Get Recommendations

3.Example: How It Works
		Input Cell Example:
		user_input = "I love action movies with superheroes"
		get_recommendations(user_input)

Recommended Movies:
--------------------------------------------------

Avengers: Infinity War
Similarity: 92.1%
Genre: Action, Adventure, Superhero
--------------------------------------------------

# Note make sure all files (netflix_titles.csv,recommendation_system.ipynb,readme.md,requirements)  are in same folder






