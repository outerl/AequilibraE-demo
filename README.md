# Aequilibrae demo

This is a simple Tradesman demo project presented at the 2023 TRB Innovations in Travel Modelling conference in Indianapolis, Indiana USA between June 3rd and June 6th.

It consists of a single Jupyter notebook around an [example model](https://github.com/outerl/AequilibraE-demo/releases/download/Freeworld/LongAn_base_model.zip) for the Vietnamese province of LongAn, with a network imported from OSM and synthetic demand data.

It has been tested with Python 3.10 running on Windows 11

Our [webpage for this conference(http://itm2023.outerloop.io) contains references to all resources presented at ITM 2023.

## Running on Windows

The setup below assumes you have Python and Windows Terminal installed.

On windows terminal:

    git clone https://github.com/outerl/AequilibraE-demo.git
    cd tradesman-demo

    python -m pip install virtualenv

    python -m virtualenv .venv
    .\.venv\Scripts\activate.ps1

    python -m install -r requirements.txt
    jupyter lab



## Running on Google Colab

You can just jump straight into Google Colab to run this tutorial notebook in the cloud.

<a href="https://colab.research.google.com/github/outerl/AequilibraE-demo/blob/main/basic_aequilibrae_demo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/></a>

Please note that, when using the free version of Google Colab, you are not guaranteed to run the entire notebook before shutting down.