# JuseTech

Descripcion del proyecto

# Pasos 


Probado en Ubuntu 19.04

Instalar los siguientes programas

    ~# apt install python3-pip git
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