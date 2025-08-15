Dataset **Wind Turbine Detection (by Noah Vriese)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMTQ5M19XaW5kIFR1cmJpbmUgRGV0ZWN0aW9uIChieSBOb2FoIFZyaWVzZSkvd2luZC10dXJiaW5lLWRldGVjdGlvbi0oYnktbm9haC12cmllc2UpLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIktuK0IzOENXYXpSdjJNVDN0SXd5SkxqTy9qdmdCUU0vOStaV2FUNVl2NlU9In0=?response-content-disposition=attachment%3B%20filename%3D%22wind-turbine-detection-%28by-noah-vriese%29-DatasetNinja.tar%22)

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

The data in original format can be [downloaded here](https://github.com/nvriese1/WindTurbineDetection/archive/refs/heads/main.zip).