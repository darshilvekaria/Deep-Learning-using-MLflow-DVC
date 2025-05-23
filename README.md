# Deep-Learning-using-MLflow-DVC

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml



## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtube.com/playlist?list=PLkz_y24mlSJZrqiZ4_cLUiP0CBN5wFmTb&si=zEp_C8zLHt1DzWKK)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=uri link \
MLFLOW_TRACKING_USERNAME=username \
MLFLOW_TRACKING_PASSWORD=token \
python script.py

Run this to export as env variables:

```powershell

$env:MLFLOW_TRACKING_URI = "link"
$env:MLFLOW_TRACKING_USERNAME = "username"
$env:MLFLOW_TRACKING_PASSWORD = "token"

```
dvc commands:
    dvc init
    dvc repro
    dvc dag

reference links:
    for html template:
        https://getbootstrap.com/

    for image conversion:
        https://base64.guru/
            image to base64: https://base64.guru/converter/encode/image
            base64 to image: https://base64.guru/converter/decode/image
        
