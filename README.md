# SAS Computer Vision

## Overview

This repository highlights computer vision capabilities in SAS Viya.
The included Jupyter notebooks demonstrate image analysis pipelines created from the image and biomedimage action set.

## Prerequisites

- Python version 3 or greater is required
- Install SAS Scripting Wrapper for Analytics Transfer (SWAT) for Python using 
```bash
pip install swat 
```
or 
```bash
conda install -c sas-institute swat
```
- Access to a SAS Viya 3.5 environment with Visual Data Mining and Machine Learning (VDMML) is required
- A user login to your SAS Viya back-end is required. See your system administrator for details if you do not have a SAS Viya account.

## CVPy

CVPy, a high-level Python library that provides helpful visualization APIs, is required for some notebooks. To install CVPy, through PyPI, use the following command:

```bash
pip install sas-cvpy
```

To install the latest version of CVPy through Github, use the following command:

```bash
pip install git+https://github.com/sassoftware/python-cvpy.git
```

For more information on CVPy, see the Github page https://github.com/sassoftware/python-cvpy. 

## Contributing
We welcome your contributions! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit contributions to this project.

## License
This project is licensed under the [Apache 2.0 License](LICENSE).

## Additional Resources

- [Image action set](https://go.documentation.sas.com/doc/en/pgmsascdc/default/casactml/casactml_image_toc.htm)
- [Biomedimage action set](https://go.documentation.sas.com/doc/en/pgmsascdc/default/casactml/casactml_biomedimage_toc.htm)

