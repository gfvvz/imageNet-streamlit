# imageNet-streamlit
[![built with Python3](https://img.shields.io/badge/built%20with-Python3.x-red.svg)](https://www.python.org/)
[![built with Streamlit](https://img.shields.io/badge/built%20with-Streamlit-blue.svg)](https://streamlit.io/)

![point table](https://github.com/iamatulsingh/imageNet-streamlit/blob/master/screen_shots/1.png)

## Install related library in conda environment
It must use below tensorflow and keras version, otherwise it will report error 'thread._local' object has no attribute 'value'

    conda create --name clone_test --clone base
    conda activate clone_test

    pip install tensorflow==1.14
    pip install keras==2.2.5

## Install Streamlit
    pip3 install streamlit --update

## How to run?
    streamlit run ui.py
