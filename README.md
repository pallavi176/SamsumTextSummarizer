# SamsumTextSummarizer

python template.py
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/pallavi176/SamsumTextSummarizer.git
git push -u origin main

conda create -n textSum python=3.8 -y
conda activate textSum
pip install -r requirements.txt

pip install --upgrade accelerate
pip uninstall -y transformers accelerate
pip install transformers accelerate

logging
utils/common

pip install ipykernel

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. update the conponents
6. update the pipeline
7. update the main.py
8. update the app.py

