# first_web_crawler

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
The News-Archive of the previews from the url: https://www.spiegel.de/international/ 
* Title 
* Sub-Title
* Abstract
* Download-time
	
## Technologies
Project is created with:
* Docker with Python as image
* Local: Anaconda3 -> Python 3.8.8 
* Jupyter Notebook
	
## Setup
To run this project, using Docker (Desktop Version) link: https://www.docker.com/products/docker-desktop/
1. Dowload or Pull my Jupyter Notebook file (Web_Crawler.ipynb)
2. Run the cmd 
3. Get the Python image
```
docker pull python
```
4. Open the Container in the desktop app and run the Container
5. Install JupyterLab with pip using cmd in desktop app
```
pip install jupyterlab
```
6. Run the Jupyter Notebook
```
jupyter notebook --ip='0.0.0.0' --port=8888
```
7. Open [local](http://localhost:8888/) in any browser
8. Run the Jupyter file (Web_Crawler.ipynb)

For extra docker command link: https://github.com/misohu/python_in_docker/blob/master/commands.md
