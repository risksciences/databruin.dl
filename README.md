Select the correct branch for your operating system.

## MacOS
```sh
conda activate base && yes y | conda remove --name databruindl --all && yes y | conda create --name databruindl && conda activate databruindl && yes y | conda install pip && yes y | pip install -r https://raw.githubusercontent.com/risksciences/databruin.dlstudio/main/requirements.txt
```
