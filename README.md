# dim0040
Repositório para a disciplina DIM0040 - Cálculo Numérico
## Configuração do ambiente virtual
### Instale o miniconda para o seu sistema operacional
https://docs.conda.io/en/latest/miniconda.html

#### Para os usuários de Windows:
https://repo.anaconda.com/miniconda/Miniconda3-py39_23.1.0-1-Windows-x86_64.exe

#### Para os usuários de MacOS:
https://repo.anaconda.com/miniconda/Miniconda3-py39_23.1.0-1-MacOSX-x86_64.sh

#### Para os usuários de Linux:
https://repo.anaconda.com/miniconda/Miniconda3-py39_23.1.0-1-Linux-x86_64.sh

#### Instalação no Linux:
```shell
bash ~/Downloads/Miniconda3-py39_23.1.0-1-Linux-x86_64.sh
```
```shell
. ~/.bashrc
```

### Criação do embiente
```shell
conda create -n dim0040 python=3.9
```
### Entrar no ambiente
```shell
conda activate dim0040
```
### Instalar pacotes necessários
```shell
python -m pip install sympy matplotlib jupyter
```
## Execução do jupyter
```shell
mkdir -p notebooks
cd notebooks
jupyter notebook
```
