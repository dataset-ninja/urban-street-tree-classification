Dataset **Urban Street: Tree Classification** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI3MjVfVXJiYW4gU3RyZWV0OiBUcmVlIENsYXNzaWZpY2F0aW9uL3VyYmFuLXN0cmVldDotdHJlZS1jbGFzc2lmaWNhdGlvbi1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJwUkhtYnhRSkQwY2VSSTRUdFdrMjltTC9ac0VjZ3FqTDN6eTB6N0swMHRrPSJ9)

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

