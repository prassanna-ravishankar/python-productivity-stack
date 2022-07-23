# Python Productivity Stack



This is a simple meta-package that does nothing except indexing and grouping other packages. This is just something I'm doing to make life easy for me



## The Stack and Installation

Most of the "code" of this repository lives in [setup.cfg](./setup.cfg). The stack has been broken down into the following parts

### Project

|     |   |
|--------------|---|
| Libraries                |  [black](https://black.readthedocs.io/en/stable/), [pyscaffold](https://pyscaffold.org/en/stable/), [pre-commit](https://pre-commit.com/)  |
| Install Step             | `pip install productivity-stack[project]` |

### ML

|     |   |
|--------------|---|
| Libraries                |  [Scikit-Learn](https://scikit-learn.org/stable/), [PyTorch](https://pytorch.org/), [NumPy](https://numpy.org/), [PyTorch Lightning](https://www.pytorchlightning.ai/), [Pandas](https://pandas.pydata.org/), [Notebook](https://jupyter.org/)   |
| Install Step             | `pip install productivity-stack[ml]` |

### (Computer) Vision 

|     |   |
|--------------|---|
| Libraries                |  [Scikit-Image](https://scikit-image.org/), [Kornia](https://kornia.readthedocs.io/en/latest/)  |
| Install Step             | `pip install productivity-stack[vision]` |

### Web

|     |   |
|--------------|---|
| Libraries                |  [FastAPI](https://fastapi.tiangolo.com/), [Streamlit](https://streamlit.io/), [AIOHTTP](https://docs.aiohttp.org/en/stable/), [Dash](https://plotly.com/dash/) |
| Install Step             | `pip install productivity-stack[web]` |


### Software development

|     |   |
|--------------|---|
| Libraries                | [Box](https://pypi.org/project/python-box/), [aiomultiprocess](https://aiomultiprocess.omnilib.dev/en/stable/), [Dask](https://www.dask.org/), [rootpath](https://pypi.org/project/rootpath/), [tqdm](https://tqdm.github.io/), [Rich](https://rich.readthedocs.io/en/latest/)  |
| Install Step             | `pip install productivity-stack[sdev]` |

### MLOps

|     |   |
|--------------|---|
| Libraries                |  [Boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html), [Sagemaker](https://sagemaker.readthedocs.io/en/stable/), [MLflow](https://mlflow.org/), [python-terraform](https://github.com/beelit94/python-terraform), [Prefect](https://www.prefect.io/), [s3fs](https://github.com/fsspec/s3fs/)  |
| Install Step             | `pip install productivity-stack[mlops]` |

### Documentation tooling

|     |   |
|--------------|---|
| Libraries                |  [Sphinx](https://www.sphinx-doc.org/en/master/), [Graphviz](https://graphviz.org/), [MkDocs](https://www.mkdocs.org/)  |
| Install Step             | `pip install productivity-stack[docs]` |


### General Ops

|     |   |
|--------------|---|
| Libraries                |  [Bandit](https://bandit.readthedocs.io/en/latest/), [Radon](https://radon.readthedocs.io/en/latest/)  |
| Install Step             | `pip install productivity-stack[ops]` |


## Contribution Guidelines

Check [CONTRIBUTING.rst](./CONTRIBUTING.rst). tl;dr - Always super happy to accept contributions!

<!-- pyscaffold-notes -->

## Note

This project has been set up using PyScaffold 4.2.2. For details and usage
information on PyScaffold see https://pyscaffold.org/.
