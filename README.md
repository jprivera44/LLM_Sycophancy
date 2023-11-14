# LLM_Sycophancy
This project focuses on the work of understanding sycophantic behavior within LLMs.


## Description
This repository, contaiins the code for a series of experiments that have been formed to better understand sycophancy within LLMs. The specific models that are a portion of focus are listed below:
- Llama2-7B
- Mistral-7B
- MPT-7B



This repository contains the Jupyter notebook Graph_llama2_model_geometry_sycophancy_v4.ipynb which is part of a larger project aimed at analyzing sycophantic behavior using geometric modeling on the LLAMA2 language model outputs. The notebook includes processes to define what constitutes sycophantic versus non-sycophantic responses, a class definition for managing the model input, as well as evaluation and graphing code to visualize the results.

## Installation
To use the code from this repository, clone it to your local machine and install the required dependencies, which are listed in the requirements.txt file.

```
git clone https://github.com/jpriivera44/LLM_Sycophancy.git
cd LLM_Sycophancy
pip install -r requirements.txt
```

## Usage
After installation, the notebook can be run in a Jupyter environment. It walks through the data preprocessing steps, model evaluation, and result visualization.

To open the notebook, use:

jupyter notebook Graph_llama2_model_geometry_sycophancy_* the experiment number you would like to run.

Contributing
We welcome contributions from the community. If you wish to contribute to this project, please follow the guidelines in the CONTRIBUTING.md file.

License
This project is licensed under the MIT License - see the LICENSE.md file for details.

Authors
Juan-Pablo Rivera

Special thanks:
Nina Rimsky for her work on LLM sycophancy

## Initial results:

Experiments that have been conducted have mainly been focused on establishing a hihgly repeatable baseline for activating sycophancy, and performing visualizations on various activations of sycophancy based off input datasets from Anthropic[1]. I perform a forward pass 

Geometry figure 1:
![Screen Shot 2023-11-03 at 4 40 54 PM](https://github.com/jprivera44/LLM_Sycophancy/assets/9093934/839f7a70-b475-4231-a002-a9c3e094810b)



Geometry figure 2:
![tsne_syco_plot](https://github.com/jprivera44/LLM_Sycophancy/assets/9093934/d0342082-95b9-4421-a8b4-1be26c191afa)


### References:
[1]: https://huggingface.co/datasets/Anthropic/model-written-evals/tree/main/sycophancy 



