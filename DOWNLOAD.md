Dataset **DeepGlobe 2018 Road Extraction** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/Z/C/1K/W5nyxIARtmYttR9RGpdFsLlbR57CO2aTOGiUy5Y6nrd0yWWMImgzQYeS92WEvzPgVsLY7opfNMZbYbDfs23gz902P0EczwNl0NUaHxRaAD9ik8EZxq2NeCAeJ1rj.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='DeepGlobe 2018 Road Extraction', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

