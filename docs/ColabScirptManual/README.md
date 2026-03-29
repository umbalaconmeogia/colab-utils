# Running Colab script

## Overview

This document describes how to run the Colab script [src/DownloadFileToGoogleDrive.ipynb](../../src/DownloadFileToGoogleDrive.ipynb) on your Google Colab.

The steps are as follows:

1. Preparation
2. Open the script in Colab.
3. Specify folder to store the downloaded files.
4. Run all
5. Upload the download file list (CSV).
6. Wait until all files are downloaded.

## Steps

### Preparation

* Create a CSV file with the following format, that contain the source URL and the FileName.
   You can see the sample [DownloadFileList.csv](../../../test/FileToDownload/DownloadFileList.csv)
* Download the file [DownloadFileToGoogleDrive.ipynb](../../src/DownloadFileToGoogleDrive.ipynb).

### Open the script in Colab

* Open https://colab.research.google.com/ on your web browser.
  Upload the file *DownloadFileToGoogleDrive.ipynb* or open it from Google Drive.
   ![New Notebook](images/00_NewNotebook.png)
* The script is opened.
   ![Open the script in Colab](images/01_OpenTheScriptInColab.png)

### Specify folder to store the downloaded files

* In the first cell, specify the folder to store the downloaded files.
   * In STORAGE_TYPE, select "MyDrive" to save to your own Google Drive, or "Shared drivers" to save to a shared drive.
   * In FOLDER_INPUT, specify the path of the folder or folder ID
   ![Specify folder to store the downloaded files](images/02_SpecifyFolderToStoreTheDownloadedFiles.png)
      * Example of path: /Temp/TestColabDownload/DownloadByFolder
      * Example of folder ID: 1GSeaPJsi0GJtel1l1te7blVBqTEe-DLu

### Run all

* Click "Run all" button to run all the cells.
* Depend on your session status, it may ask to authenticate to Google Drive. See [Authenticate to Google Drive](#authenticate-to-google-drive) at *Preferences*.
* It will show the path of the folder
   ![Run all](images/03_RunAll.png)

### Upload the download file list (CSV)

* In the second cell, click *Choose File* button and select the download file list (CSV).
   ![Upload the download file list (CSV)](images/04_SelectDownloadFileList.png)

### Wait until all files are downloaded

* Wait until all files are downloaded.
   ![File downloaded](images/05_FileDownloaded.png)
* It will take several hours to download large files.
   ![Long download](images/06_LongDownload.png)

## Preferences

### Authenticate to Google Drive

There are two kind of authentication to Google Drive.
1. Connect to Google Drive.
   * Permit notebook to access your Google Drive.
      ![Permit Connect GDrive](images/10_01_PermitConnectGDrive.png)
   * Login to Google Drive.
      ![Login to Google Drive](images/10_02_LoginGoogle.png)
   * Set access right.
      ![Access right](images/10_03_SetAccessRight.png)
2. Allow Colab to access Google Drive.
   * Permit notebook to access your Google credentials.
      ![Permit access Google credentials](images/11_01_PermitConnectGDrive.png)
   * Login to Google Drive.
      ![Login to Google Drive](images/11_02_LoginGoogle.png)
      ![Password](images/11_03_Password.png)
   * Set access right.
      ![Access right](images/11_04_AccessRight.png)
