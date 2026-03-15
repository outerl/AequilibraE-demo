# Aequilibrae demo

This is a simple AequilibraE demo project suitable for teaching AequilibraE to new audiences. It was originally developed to be presented at the 2023 TRB Innovations in Travel Modelling conference in Indianapolis, Indiana USA between June 3rd and June 6th.

It consists of a few examples:

1. Path finding and graph manipulation using the Gold Coast Model 
   
2. Skimming and traffic assignment using the Gold Coast Model 

3. Multi-class traffic assignment using the LongAn model

4. Route choice using the Coquimbo model
   

Models used in these examples

* [Gold Coast model](https://github.com/outerl/AequilibraE-demo/releases/download/poli_2026/LongAn_base_model.zip) 
   which was imported from [TNTP networks] (https://github.com/bstabler/TransportationNetworks).

* [LongAn model](https://github.com/outerl/AequilibraE-demo/releases/download/poli_2026/LongAn_base_model.zip) 
   with a network imported from OSM and synthetic demand data

* The Coquimbo model is shipped with AequilibraE as one of its examples 


## Running on Windows

It has been tested with Python 3.12 running on Windows 11

The setup below assumes you have Python installed.

We recommend using VSCode or other good IDE.

**DO NOT INSTALL WINDOWS FROM THE MICROSOFT APP STORE**

On Windows terminal:

    git clone https://github.com/outerl/AequilibraE-demo.git
    cd AequilibraE-demo

    pip install uv
    uv virtualenv .venv
    .\.venv\Scripts\activate.ps1

    uv pip install -r requirements.txt


## Running on Google Colab

You can just jump straight into Google Colab to run this tutorial notebook in the cloud.

<a href="https://colab.research.google.com/github/outerl/AequilibraE-demo/blob/main/path_finding_demo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Path finding demo on Colab"/></a>

<a href="https://colab.research.google.com/github/outerl/AequilibraE-demo/blob/main/traffic_assignment_demo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Traffic assignment demo on Colab"/></a>

<a href="https://colab.research.google.com/github/outerl/AequilibraE-demo/blob/main/multi_class_traffic_assignment.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Multi-Class example on Colab"/></a>

<a href="https://colab.research.google.com/github/outerl/AequilibraE-demo/blob/main/route_choice_basics.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Route choice example on Colab"/></a>

Please note that, when using the free version of Google Colab, you are not guaranteed to run an entire notebook before it shuts down.

## Versions

Specific versions of this tutorial can be found using tags in this repository

https://github.com/outerl/AequilibraE-demo/tags

Existing tags are:

* Freeworld - Original version of this repository, presented at the 2023 TRB Innovations in Travel Modelling conference in Indianapolis, Indiana USA between June 3rd and June 6th
  Our webpage for this conference(http://itm2023.outerloop.io) has more information 

* poli_2026 - Presented at the Escola Politécnica da Universidade de São Paulo, Brasil