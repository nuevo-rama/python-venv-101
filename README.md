# python-venv-101
Python Virtual Enviroment 101

#### Guía para utilizar 'venv'

- ```venv``` Crea un entorno virtual de desarrollo para python
- El entorno virtual permite tener los paquetes de ese proyecto aislados del resto de proyectos.

- Instalamos virtualenv
```bash
pip install virtualenv
```
- Definimos el nombre del entorno virtual independiente
```bash
virtualenv my_env
```
- Activamos el entorno virtual (para linux)
```bash
source my_env/bin/activate
```
- Desactivar el entorno virtual
```bash
deactivate
```
- Con el entorno virtual activado (my_env)
- Instalar un paquete dentro del entorno virtual
```bash
pip install nombre_paquete
```
- Desinstalar un paquete dentro del entorno virtual
```bash
pip uninstall nombre_paquete
```
- Listar todos los paquetes del entorno virtual
```bash
pip list
```
- Crear un archivo de texto que contenga todos los requisitos del entorno virtual
```bash
pip freeze > requirements.txt
```
- Instalar paquetes desde un archivo de requerimientos
```bash
pip install -r requirements.txt
```






