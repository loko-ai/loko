![logo_50](https://user-images.githubusercontent.com/78538303/180229383-b5b2d7cc-bee0-4688-9a8a-1c200976ad78.png)


LOKO AI is a **low-code platform** designed to easily and quickly create **artificial intelligence applications** to be implemented in business processes.


# :computer: Releases



[Latest release](https://github.com/loko-ai/loko/releases)


# How does it work?




In LOKO AI you have an entire suite of components containing **code and AI functionalities**: each component is a **block**, with its functionalities and its own code. To use the blocks in a workflow, you just have to **drag&drop** each one on the workspace and to configure them.

With LOKO AI you have **ML features** at your hands: it allows to measure **model performances** and create intelligible reports and, if you have specific needs, you can fine-tune your code with a low-code approach. Then, if necessary, you can **export** your ML model in any other platform.



![Screenshotworkflow](https://raw.githubusercontent.com/loko-ai/loko/development/immagini/Screenshot_workflow.png)


[Here](https://loko-ai.com) our website for more information.


## Technologies you'll find in LOKO AI

On LOKO AI you'll be able to carry out several task, using our **blocks**, which are based on the most common technologies used in the **AI** field, indepently of the type of data you have. 

### *Machine Learning and Deep Learning*

For the **ML** tasks, all the **Sklearn** regression and classification models are available and also other well known alghoritms such as **XGBoost**, **CatBoost** and **LightGBoost**. 

If you want to use a more elaborated model you can use a Neural Network model, some pre-defined version are available, which are based on **Tensorflow** and **PyTorch** technology. 

LOKO AI has an **AutoML** tool, which use **Optuna** to tune the hyper-parameter, and choose the model that performs better on your data.

### *Natural Language Processing*

If you have some files and you want to extract the text inside, you can use our **OCR blocks**, based on **Tesseract** framework.

If the data you have is textual, it is possible to apply some pre-processing through our **NLP blocks**, which use **NLTK** and **SPACY**, if needed, and extract entities using rules models or AI, through **Spacy** or **Hugging Face** frameworks, based on what fits you the best.


Finally, it's possible to manage your favourite database among the one supported, whether it is a **cloud database**, a **relational** or **non-relational** one. Currently supported database: **SQL**, **MongoDB**, **AWS**.


### Libraries


[![Python](https://img.shields.io/badge/Python-version%203.10-green)](https://www.python.org/downloads/release/python-3100/)
[![Sanic](https://badgen.net/badge/sanic/22.6.0/:yellow?icon=sanic)](https://sanic.readthedocs.io/en/stable/)[![SanicOpenAPI](https://img.shields.io/badge/Sanic%20OpenAPI-version%2021.12.0-brightgreen)](https://sanic-openapi.readthedocs.io/en/stable/)
[![HuggingFace](https://badgen.net/badge/huggingface/yes/?icon=github)](https://github.com/huggingface)[![PyTorch](https://badgen.net/badge/PyTorch/1.11.0/red)](https://pytorch.org/)
[![Keras](https://badgen.net/badge/Keras/nd/yellow?)](https://keras.io/)
[![Tensorflow](https://badgen.net/badge/Tensorflow/ND/blue?)](https://www.tensorflow.org/)
[![Pandas](https://badgen.net/badge/Pandas/loading/purple)](https://pandas.pydata.org/)
[![OpenCV](https://badgen.net/badge/OpenCV/loading/cyan)](https://opencv.org/)
[![Spacy](https://badgen.net/badge/Spacy/loading/grey)](https://spacy.io/)
[![NLTK](https://badgen.net/badge/NLTK/loading/green)](https://www.nltk.org/)
[![SKlearn](https://badgen.net/badge/SKlearn/loading/yellow)](https://scikit-learn.org/stable/)
[![Tesseract](https://badgen.net/badge/Tesseract/4.x.x/blue?icon=github)](https://github.com/tesseract-ocr/tesseract) 
[![React.js](https://badgen.net/badge/React.js/loading/pink)](https://reactjs.org/)
[![Flask](https://badgen.net/badge/Flask/loading/cyan)](https://flask.palletsprojects.com/en/2.2.x/)
[![Optuna](https://badgen.net/badge/Optuna/loading/pink)](https://optuna.org/)



# :heavy_exclamation_mark: Requirements

To install LOKO AI all you need is **Docker**.
You can install Docker on every principal OS, like **Windows, MacOS and Linux**.

**Debian/Ubuntu** based distros:
- sudo apt install -y docker.io
- sudo systemctl enable docker && sudo systemctl start docker
- sudo usermod -aG docker $USER && reboot

**RHEL/CentOS** based distros:
- sudo yum remove -y docker docker-client docker-client-latest docker-common docker-latest docker-latest-logrotate docker-logrotate docker-engine podman runc
- sudo yum install -y yum-utils
- sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
- sudo yum install -y docker-ce docker-ce-cli containerd.io docker-compose-plugin
- sudo systemctl enable docker && sudo systemctl start docker
- sudo usermod -aG docker $USER && reboot

**Fedora** based distros:
- sudo dnf remove -y docker docker-client docker-client-latest docker-common docker-latest docker-latest-logrotate docker-logrotate docker-selinux docker-engine-selinux docker-engine
- sudo dnf install -y dnf-plugins-core
- sudo dnf config-manager --add-repo https://download.docker.com/linux/fedora/docker-ce.repo
- sudo dnf install -y docker-ce docker-ce-cli containerd.io docker-compose-plugin
- sudo systemctl enable docker && sudo systemctl start docker
- sudo usermod -aG docker $USER && reboot

**Windows OS**:
- install Docker Desktop following this [link](https://docs.docker.com/desktop/install/windows-install/)

**Mac OS** (for Intel Chip and Apple Silicon):
- install Docker Desktop following this [link](https://docs.docker.com/desktop/install/mac-install/)

**Hardware minimum requirements:**
- HW Acceleration  
- GPU Drivers
- an Intel Pentium 4 processor or later that's SSE3 capable

**Recommended OS:**  
- 64-bit OS
- Ubuntu 18.04+  
- Debian 10+
- Rhel/CentOS 8+
- Fedora Linux 32+



# Installation

**Distribution** | **Status**
  -----------|------------|
[**Windows**](https://github.com/loko-ai/loko/releases/download/windows-0.0.1-alpha/LoKo-Windows-0.3.3-Setup.2.exe) | |                  
[**Linux**](https://github.com/loko-ai/loko/releases/download/linux-v0.0.1-alpha/LoKo-Linux-0.3.3.AppImage)
MacOS

## Windows

- Download LOKO AI self-extractable executable by following this link (link file .exe)

- install LOKO AI by double-clicking on the .exe file (fig1)

If a Windows Defender SmartScreen pop-up shows up, click on *More info* (fig2) and then on *Run anyway* (fig3)

- choose whether to install LOKO AI globally (for all users on your Windows PC) or only for the current user, then click *Next* (fig4)

- if *Anyone who uses this computer* is selected, the Windows UAC prompt will show up. To get Admin Privileges and allow LOKO AI to be installed globally, click *Yes* (fig5)

- choose the LOKO AI installation path: for a global installation the default path will be "C:\Program Files\LoKo", for a single user installation the default path will be "C:\Users\<USER>\AppData\Local\Programs\LoKo". The installation path can be changed by clicking on "Browse...". 

- once the desired path is selected, click *Install* (fig6)

- at the end of the installation, keep *Run LoKo* checked to run LOKO AI immediately after clicking *Finish* (fig7)


## Linux
- Download LOKO AI .AppImage executable [here](LINK FILE .AppImage)

- In order to run LOKO AI, the AppImage must be executed as a Program:

Open the terminal, browse to the directory which contains the **.AppImage file**, execute: **chmod +x loko-Linux-0.3.3.appimage**. 

Alternatively, right-click on the .AppImage file, *Properties*, go to the *Permissions* tab, make sure the *Allow executing file as a program* field is checked.

![linuxinstallation](https://raw.githubusercontent.com/loko-ai/loko/development/immagini/Linux_installation.png)


Run LOKO AI by double-clicking on the .AppImage file or by typing the .AppImage file
name in the terminal. 

![linuxappimage](https://raw.githubusercontent.com/loko-ai/loko/development/immagini/Linuxappimage.png)

## MacOS


### How to use LOKO AI?


If you're on the platform:
- in the welcome page, go to **Read the documentation** to open the user guide
- go to **Academy** section for videotutorials and lessons to learn how to use LOKO AI, and see specific use case.

Alternatively,

- go [here](https://livetech.gitbook.io/user-guide-loko-ai/) for the user guide
- visit our [YouTube channel](https://www.youtube.com/channel/UCCqqKo-f4RpRCf7rkXteKAg/featured) for our videotutorials.

# Troubleshooting

## Linux


• If there are some errors regarding FUSE in the terminal or the LOKO AI app doesn't run, try to install FUSE by following [these instructions](https://github.com/AppImage/AppImageKit/wiki/FUSE).

If FUSE is already installed, try to restart your PC:

• If in the terminal you see *Exiting GPU process due to errors during initialization*, it means that you don’t have any **HW Acceleration**, try to install or update your GPU Driver

• If in the terminal you see *libGL error: MESA-LOADER: failed to retrieve device information* it means that you are using an unsupported, unofficial or third-party **GPU Driver**, try to install a different GPU Driver or update your existing one

• During the first start of LOKO AI, the app will pull the required containers from a remote repository. If there are network **errors** or corrupted downloads, LOKO AI could **still run** but some functionalities could be **broken**, try to close and start again LOKO AI in order to **pull again** its containers 



## Ask

| What                            | Where                               |
| ------------------------------- | --------------------------------------- |
|**Bug Reports**              |     lokoai.support@ilivetech.it              |                        |
|**Discussion and usage question**        | [Telegram](https://t.me/+CapC4sNofCwzN2E0), private group |  |
|**Community collaboration session** |  |
