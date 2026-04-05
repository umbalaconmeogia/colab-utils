# Colab Utilities

## Overview

This is a collection of script to run on Google Colab. For example
* Download large files from the internet to Google Drive.
* Unzip a large files on Google Drive.

Nowaday, we should process large data (for example whole genome sequencing data, large dataset for machine learning, etc. that are several gigabytes or more).
We also need to process WGS analysis or machine learning analysis, that need strong computer to run.

Our local PC may not have enough resources to invoke this processing.
A solution is using Google Colab.
Google Colab is a free service provided by Google that allows us to run Python code in the cloud.
It provides free access to computing resources, including GPUs and TPUs, and also Google Drive for storage.

* Normal way of downloading to a local computer then uploading to Google Drive (slow)
  ![Download normal](docs/materials/download_pc.png)
* Speedy way: using Colab for direct download (faster)
  ![Download colab](docs/materials/download_colab.png)

## Tools provided

* [Download large files from the internet to Google Drive](docs/DownloadFileToGoogleDrive/README.md)
* [Unzip a large files on Google Drive](docs/UnzipFileOnGoogleDrive/README.md)
