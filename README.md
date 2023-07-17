# README


## Requirements

### Hardware

Google Colaboratory

* CPU: Intel(R) Xeon(R) CPU @ 2.20GHz
* RAM: 26,687,680[KB]
* GPU: Nvidia Tesla V100-SXM2


### OS

20.04.6 LTS (Focal Fossa)


### Third party software

To use GPU, following packages are required.

* CUDA 11.8.89
* cuDNN 8.9.0

Above packages are pre-installed in Google Colaboratory.
And following python packages are needed.

* transformers 4.30.2
* xformers 0.0.20
* langchain 0.0.234


## How to run

Since the following files are in jupyter notebook format and can be run in Google Colaboratory or equivalent environment.

* `notebook/text_generation_01.ipynb`: Text generation by Transformers pipeline.
* `notebook/text_generation_02.ipynb`: Text generation by Transformers pipeline and LangChain.
* `notebook/text_generation_03_A.ipynb`: Text generation by Transformers pipeline, LangChain and Chroma (using LangChain's  Chroma wrapper interface).
* `notebook/text_generation_03_B.ipynb`: Text generation by Transformers pipeline, LangChain and Chroma (using original Chroma interface).
