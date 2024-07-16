Select the correct branch for your operating system.

## MacOS
```sh
conda activate base && yes y | conda remove --name databruin-dlstudio --all && yes y | conda create --name databruin-dlstudio && conda activate databruin-dlstudio && yes y | conda install pip && yes y | pip install -r https://raw.githubusercontent.com/risksciences/databruin.dlstudio/main/requirements.txt
```
