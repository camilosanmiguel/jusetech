# JuseTech

proyecto de ventas online
# Pasos 


Probado en Ubuntu 19.04

Instalar los siguientes programas

    ~# apt install git python3-pip mariadb-server mariadb-client python3.6-dev libmysqlclient-dev
    ~# pip3 install virtualenv

Clonar el repositorio

        con SSH
    ~$ git clone git@gitlab.com:nopailas/jusetech.git

        con HTTPS
    ~$ git clone https://gitlab.com/nopailas/jusetech.git

crear entorno virtual

    ~$ cd jusetech
    ~$ virtualenv -p python3 venv
	
        para iniciar el entorno virtual
		
	~$ source venv/bin/activate
	
		para desactivar el entorno virtual
		
	(venv) ~$ deactivate
	
Configurar entorno desarrollo
		
	~# pip install -r requirements.txt
	
		Crear variable de entorno para iniciar servidor Flask
		
    ~$ export FLASK_APP=main.py
    ~$ export FLASK_DEBUG=1
	
Iniciar servidor
	
	 ~$ flask run
	 
Documentacion	 
https://flask-mysqldb.readthedocs.io/en/latest/