# Instalar requirements.txt puxando as bibliotecas presente no código
pip freeze > requirements.txt

# Criar o "venv" (ambiente virtual, importante para garantir que o site não terá erros/crash/bugs) - venv é uma pasta com inúmeros arquivos com diversar dependencias e etc.
python -m venv venv

# Rodar o código no ambiente virtual do venv
venv\Scripts\activate

# Instala as dependências
pip install -r requirements.txt
