# Aequilibrae demo

This is a simple AequilibraE demo project suitable for teaching AequilibraE to new audiences. It was originally developed to be presented at the 2023 TRB Innovations in Travel Modelling conference in Indianapolis, Indiana USA between June 3rd and June 6th.

It consists of few examples:

1. An example of path finding, skimming and traffic assignment using the 
   [Gold Coast model](https://github.com/outerl/AequilibraE-demo/releases/download/Freeworld/LongAn_base_model.zip) 
   which was imported from [TNTP networks] (https://github.com/bstabler/TransportationNetworks).

2. An example of multi-class traffic assignment using the
   [LongAn model](https://github.com/outerl/AequilibraE-demo/releases/download/Freeworld/LongAn_base_model.zip) 
   with a network imported from OSM and synthetic demand data.


It has been tested with Python 3.12 running on Windows 11

## Running on Windows

The setup below assumes you have Python and Windows Terminal installed.

On Windows terminal:

    git clone https://github.com/outerl/AequilibraE-demo.git
    cd AequilibraE-demo

    pip install uv
    uv virtualenv .venv
    .\.venv\Scripts\activate.ps1

    uv pip install -r requirements.txt


## Running on Google Colab

You can just jump straight into Google Colab to run this tutorial notebook in the cloud.

<a href="https://colab.research.google.com/github/outerl/AequilibraE-demo/blob/main/basic_aequilibrae_demo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Baic example on Colab"/></a>

<a href="https://colab.research.google.com/github/outerl/AequilibraE-demo/blob/main/multi_class_traffic_assignment.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Multi-Class exmaple on Colab"/></a>

Please note that, when using the free version of Google Colab, you are not guaranteed to run an entire notebook before it shuts down.

## Versions

Specific versions of this tutorial can be found using tags in this repository

https://github.com/outerl/AequilibraE-demo/tags

Existing tags are:

* itm_2023 - Original version of this repository, presented at the 2023 TRB Innovations in Travel Modelling conference in Indianapolis, Indiana USA between June 3rd and June 6th
  Our webpage for this conference(http://itm2023.outerloop.io) has more information 

* poli_2026 - Presented at the Escola Politécnica da Universidade de São Paulo, Brasil

