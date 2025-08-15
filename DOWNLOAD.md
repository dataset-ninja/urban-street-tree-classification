Dataset **Urban Street: Tree Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjcyNV9VcmJhbiBTdHJlZXQ6IFRyZWUgQ2xhc3NpZmljYXRpb24vdXJiYW4tc3RyZWV0Oi10cmVlLWNsYXNzaWZpY2F0aW9uLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIkJBV2svVjhwQlY4WWdEVXgxVFp0TFU1eUpkLzlxZTFNYWFReVJ6Mlo3REU9In0=?response-content-disposition=attachment%3B%20filename%3D%22urban-street%3A-tree-classification-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Urban Street: Tree Classification', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

