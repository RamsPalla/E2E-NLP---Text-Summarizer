# End-to-end-Text-Summarizer


## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py

## Steps to create virtual environment, activate it and run the project in case we are running project from folder.
1. conda create -n <projectname> pythin=3.8 -y
2. conda activate <projectname>
3. pip install -r requirements.txt
4. pip install --upgrade accelerate (this project specific)
5. pip uninstall -y transformers accelerate (this project specific)
6. pip install transformers accelerate (this project specific)
