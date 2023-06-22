Please visit dataset [homepage](https://github.com/nvriese1/WindTurbineDetection) to download the data. 

Afterward, you have the option to download it in the universal supervisely format by utilizing the *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbines 8', dst_path='~/dtools/datasets/Wind Turbines 8.tar')
```
