Dataset **Wind Turbine Detection (by Noah Vriese)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/P/k/pl/HQpYdyn35fC1klC1PC90bXIpnXF99YmDJ8BnxPSmbij2PXWSYWZqdMj9jRcgnhbo6wIB76PnIHrTJ2A1qXo2V5k5L0DpgYxf8432E9TFZ365jRHtkQkBWcGZZyEW.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbine Detection (by Noah Vriese)', dst_path='~/dtools/datasets/Wind Turbine Detection (by Noah Vriese).tar')
```
The data in original format can be 🔗[downloaded here](https://github.com/nvriese1/WindTurbineDetection/archive/refs/heads/main.zip)