# Making Your Repository Jupyter4NFDI-Ready


This is a template repository for learning how to make a repository ready for launching it in Jupyter4NFDI using repo2docker option.  

Use this template to learn how to prepare contents with Jupyter Notebook to be Jupyter4NFDI ready (using repo2docker). You can follow the training materials that can be found here https://nfdi-jupyter.github.io/learn-jupyter4nfdi-ready/
Alternatively you can follow these steps:

1. Create your own copy of the repository using this template: <img width="1315" height="211" alt="image" src="https://github.com/user-attachments/assets/c6ad8c80-c9ee-43fa-8f8e-84a9f56c2c20" />
2. Working in your own copy of the repository add  a `requirements.txt` file which specifies the Python packages needed to run the code in the [sample Jupyter Notebook](dining_out_survey_analysis.ipynb) in this repository.
3. The contents of the `requirements.txt` should be
```
pandas==3.0.5
altair==6.2.2
```
4. Once you added the `requirements.txt` file, log into Jupyter4NFDI and in the Dashboard select `repo2docker` option.
<img width="1412" height="335" alt="image" src="https://github.com/user-attachments/assets/f0a18232-b230-4c41-8a2a-775473968ab8" />


## Licensing

- **Content**: CC BY 4.0
This license covers any non-code contents, such as tutorials.

- **Code**: [Apache License 2.0](LICENSE)
This license covers any code included in this repository.

## Acknowledgements
This work is supported by Jupyter4NFDI as part of **Base4NFDI (DFG project no.521453681).**


