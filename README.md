## End to End Machine Learning Project to predict Student score

Steps to run,

	1. Activate venv. Recommend installing Anaconda to manage virtual environment
 
	2. Run pip install -r requirements.txt
 
	3. Run python -m src.components.data_ingestion - this ingests the data and transforms under artifacts folder
 
	4. Run python -m src.components.model_trainer - this creates prediction model file under artifacts folder
 
	5. Run python app.py
		- GO to http://localhost:5000/predictdata
  
	6. Enjoy!!!

Key folders,

	- 'artifacts' folder for input data, model file and train/test files
 
	- 'src' folder has all model training and ingestion code
