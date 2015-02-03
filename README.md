# Ligthweight Django Tutorial

Esse projeto tem como ideia divulgar uma ideologia, onde você não é obrigado, nem precisa se sentir 
flustrado em ter sempre que usar as ferramentas de geração de código do django, sendo que você pode ser 
livre para usar o modulo que precisar e escalar seu servidor enxudo, a partir de componentes do Django, 
sendo utilizados de forma mais limpa possivel e tudo criado a mão, sem geração de codigo `django-admin.py startproject`

###### criamos a pasta do projeto
`mkdir ligthweigth && cd ligthweigth`

###### criar uma virtualenv
`virtualenv -p /usr/bin/python3 venv ligthweigth`

### Ativando a virtualenv
`source venv/bin/activate`

### Instalamos o Django versão 1.7.2
`pip install django=1.7.2`

### Criamos o arquivo app.py
`touch app.py`

### Instalar o gunicorn usando pip 
`pip install gunicron`

### Rodar o gunicorn
`gunicorn app:application -b :3000 --log-file=-`

