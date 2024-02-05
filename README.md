# Digital Humanities - JupyterLab Notebooks

## Anaconda Installation Guide
### Windows 10/11 Installation Guide

1. Navigate to [https://www.anaconda.com/download](https://www.anaconda.com/download) and click **Download**.

2. Locate the downloaded installer file and double-click on it to start the installation process.

3. During the installation process, select the following options:
During the installation, make sure to check the following options:

- Create start menu shortcuts (supported packages only).
- Register Anaconda3 as my default Python 3.11.
- Clear the package cache upon completion.

4. The installation may take a few minutes. Once it is complete, you may click **Next**.

5. Click **Finish** to close the installer.

6. After installation, you may update Anaconda to the latest version if you are prompted to do so.

### Anaconda – macOS Installation Guide

1. Navigate to [https://www.anaconda.com/download](https://www.anaconda.com/download) and click **Download**.

2. In order to determine which option to download for Mac (Intel) or (M1/M2/M3), follow these steps:

    a. Click the Apple Logo on the top left corner of the screen.
    
    b. Click “About This Mac”. The line that states “Chip” will indicate the manufacturer (e.g. Apple M2 … or Intel i7 .. ).

3. Open the downloaded installer.

4. Leave all settings on their default values and proceed with the installation.

5. Click close once the installation is complete.

6. If prompted, you may update to the latest version.

#### Removing Anaconda from your computer
If you would like to permanently uninstall and delete Anaconda, you may follow this guide: [https://docs.anaconda.com/free/anaconda/install/uninstall/](https://docs.anaconda.com/free/anaconda/install/uninstall/)

## Anaconda – Running your first JupyterLab notebook locally

Now that we have gotten Anaconda installed, we will need to download the repository from GitHub so that we can use the code and the accompanying books to run a few analyses.

1. At the top of the [GitHub Page](https://github.com/alex-krtt/kitmarlowe-jupyter/tree/main) click "Code".
2. Click "Download ZIP".

### For macOS Users

- Double click the downloaded .zip archive. This should create a folder which is what we need.

### For Windows 10/11 Users

- Right click the downloaded zip folder and click “Extract All”.

You may leave this in the default location which will be your “Downloads” folder or you may choose to extract the files somewhere else but be sure to make note where it is located.

### Launching JupyterLab

1. If you have not done so already, launch Anaconda Navigator and find JupyterLab. We will click “Install”. If it already says “Launch” you may skip to the next step.
2. Click Launch under JupyterLab.
3. Your browser (Chrome/Safari/etc) will open and you will see the homepage of JupyterLab.

Before we begin running the jupyterlab scripts, I recommend making the following adjustments to the user interface:
- Resize the left window so that it has more space by dragging the grey bar.
- Enable “Simple” mode on the bottom left corner which will simplify the user interface a bit.

### Running the Jupyter Notebook

1. Navigate to where you downloaded the GitHub repository. In my case I downloaded my scripts to my “Downloads” folder. macOS may ask for permission to access “Downloads” or the folder you have it under, so you may have to click Allow.
2. Click the folder with the dark grey icon as that indicates a folder. JupyterLab is not able to open zip files for us which is why we extracted them a few steps ago.
3. Click the wordcloud.ipynb as example notebook to run. After you click or double click it you should seen a few code blocks on the right part of your screen.
4. To execute all code blocks, go to Run and “Run All Cells”.
5. Some of these scripts depend on external tools that JupyterLab will install for us. I have already include Python code that will download these packages. After the script stops running you will see “you may need to restart the kernel to use updated packages”.
6. Click “Run” then “Restart Kernel and Run All Cells…” You only have to restart once per new installation.

Congratulations you just run your first Jupyter Notebook!

## Google Colab – Running your first JupyterLab notebook on the cloud

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alex-krtt/kitmarlowe-jupyter/blob/master/)


## License
The corpora used in this project are licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0). To view a copy of this license, visit [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/).

Original data provided with permission by Kit Marlowe Project and Folger.