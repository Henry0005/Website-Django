# Meu Site em Django

## Descrição
Um site exemplo criado com Django que possui funcionalidades como seções de serviços, uma galeria e um formulário de contato

## Tecnologias
- Django
- SQLite
- HTML/CSS

## Instalação
```bash
git clone <url-do-repositorio>
cd <nome-do-projeto>
python -m venv venv
source venv/bin/activate  # Para Linux/Mac
venv\Scripts\activate  # Para Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

## Uso
Acesse http://127.0.0.1:8000/
