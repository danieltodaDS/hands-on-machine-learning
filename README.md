# hands-on-machine-learning
estudo do livro hands-on-machine-learning

1. Clone o repositorio e o projeto do livro: 
```bash
git clone git@github.com:danieltodaDS/hands-on-machine-learning.git
cd ~/hands-on-machine-learning
git clone https://github.com/ageron/handson-ml2.git
``` 

2. Configure a versao correta do Python com `pyenv`: 
```bash
pyenv install 3.12.1
pyenv local 3.12.1
```

3. Instale as dependencias do projeto: 
```bash
python -m venv .venv
source .venv/bin/activate #Linux
source .venv\\Scripts\\Activate #Windows
pip install -r requirements.txt
```

----------------

- Para atualizar dependencias: 

```bash
pip list --not-required --format=freeze >> requirements.txt
```

