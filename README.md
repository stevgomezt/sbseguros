Creamos un entorno con python 3.11.4, e instalamos las dependencias necesarias.

conda create -n SbsegurosEnv
conda activate SbsegurosEnv
conda install python=3.11.4
pip install -r requirements.txt
streamlit run app.py
