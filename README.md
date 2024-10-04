# Setup Environment - Anaconda
conda create --name Bikesharing-env python=3.9
conda activate Bikesharing-env
pip install -r requirements.txt

# Setup Environment - Shell/Terminal
mkdir Bikesharing
cd Bikesharing
pipenv install
pipenv shell
pip install -r requirements.txt

# Run streamlit app
streamlit run dashboard.py
