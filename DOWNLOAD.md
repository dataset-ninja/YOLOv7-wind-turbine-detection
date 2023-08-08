Dataset **Wind Turbine Detection (by Noah Vriese)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/b/p/k0/RcTlw8dvFfhHag8PFoDZGqADFg4HBlAg9Y00JuXIi8ss1jcnczQJRXbpqZ41z4cpnhb0c2L6UmXhcBF7fy2MqiRezEEGBQ8CdyWsUKokDvyeOkvfPaO3UGp24Od8.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbine Detection (by Noah Vriese)', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://github.com/nvriese1/WindTurbineDetection/archive/refs/heads/main.zip)