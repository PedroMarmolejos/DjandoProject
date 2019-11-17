# Uapa
Comandos básicos para inicializar el proyecto:

Clonar proyecto

SSH:
>```$ git clone git@bitbucket.org:rodolfotorres02/uapa.git```

HTTPS:
>```$ git clone https://rodolfotorres02@bitbucket.org/rodolfotorres02/uapa.git```

---
Crear entorno virtual utilizando virtualenv

>```$ virtualenv venv -p python3.7```

Activar entorno virtual

>```$ source venv/bin/activate```

Instalar los requerimientos

>```$ pip install -r requirements.txt```

Correr las migraciones

>```$ python manage.py migrate```

Crear super usuario

>```$ python manage.py createsuperuser```

Correr el proyecto
>```$ python manage.py runserver```