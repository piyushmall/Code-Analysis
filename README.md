# Code-Analysis
Source Code analysis

# STEP 01- Create a conda environment after opening the repository

conda create -n llmapp python=3.10 -y
conda activate llmapp

# STEP 02- install the requirements

pip install -r requirements.txt

# Create a .env file in the root directory and add your OPENAI_API_KEY credentials as follows:

OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
# Finally run the following command
python app.py