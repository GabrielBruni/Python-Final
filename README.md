**Clase 11 Actividad en Python**
*Abrió: Lunes 24 de Junio de 2024, 17:00*

Aquí esta el video desde el canal de YouTube en vivo:
                                                      Clase en Vivo

# Hoy vamos a hacer actividad en Python en un día como programadores:

01. Abrir la terminal de Git Bash o terminal en Linux, debe ser como administrador en Window.
02. Creamos una carpeta o directorio:
```sh 
mkdir python-final
```
03. Entramos en ella:
```sh 
cd python-final
```
04. Iniciamos el repositorio:
```sh
git init
```
05. Creamos un archivo:
```sh
touch finales.py
```
06. Abrimos VSC:
```sh
code .
```
07. En terminal ingresamos el comando para saber la versión de Python que tenemos instalada:
```sh
python -V
python3 -V
```
08. Creamos el entorno virtual en Python:
```sh
python -m venv venv   #Creamos el entorno virtual
python3 -m venv venv  #Creamos el entorno virtual
```
09. Activamos el entorno virtual:
```sh
venv/scripts/activate      #En windows
source venv/bin/activate   #Activamos el entorno virtual en Linux
```
10. Hacemos actualización del pip de Python:
```sh
python -m pip install --upgrade pip    #Actualizamos el pip
python3 -m pip install --upgrade pip   #Actualizamos el pip
```
11. Investigar: ¿Qué es el pip y porque lo actualizamos?

### ¿Qué es `pip`?
`pip` es el sistema de gestión de paquetes utilizado para instalar y gestionar paquetes de software escritos en Python. Es una herramienta que permite instalar y actualizar librerías y aplicaciones desarrolladas en Python desde el Python Package Index (PyPI) y otros índices de paquetes.

#### Funciones principales de `pip`:
- **Instalar paquetes**: Puedes instalar paquetes nuevos desde PyPI.
- **Actualizar paquetes**: Puedes actualizar los paquetes instalados a versiones más recientes.
- **Desinstalar paquetes**: Permite desinstalar paquetes instalados previamente.
- **Listar paquetes instalados**: Muestra una lista de los paquetes instalados en tu entorno.

### ¿Por qué actualizamos `pip`?
Actualizar `pip` es importante por varias razones:
1. **Mejoras y nuevas funcionalidades**: Las actualizaciones de `pip` a menudo incluyen nuevas características que pueden mejorar la funcionalidad y la facilidad de uso.
2. **Corrección de errores**: Como cualquier software, `pip` puede tener errores que se solucionan en versiones posteriores. Mantener `pip` actualizado ayuda a evitar problemas conocidos.
3. **Seguridad**: Las actualizaciones pueden incluir parches de seguridad que protegen tu entorno de desarrollo de vulnerabilidades conocidas.
4. **Compatibilidad**: Las versiones más recientes de `pip` pueden ser necesarias para instalar ciertos paquetes o versiones de paquetes que requieren funcionalidades específicas o actualizadas de `pip`.

### ¿Qué es Git Bash?
Git Bash es una aplicación que proporciona una capa de emulación para Git command line en Windows. Ofrece un entorno similar a Unix y permite ejecutar comandos de Git en Windows.

### ¿Qué es GitHub?
GitHub es una plataforma de desarrollo colaborativo basada en Git. Permite a los desarrolladores alojar proyectos, colaborar con otros, hacer seguimiento de versiones y manejar el código fuente.

### Relación entre `pip`, Git Bash y GitHub
- **`pip` y Git Bash**: Puedes usar `pip` dentro de Git Bash para instalar y gestionar paquetes de Python. Git Bash facilita el uso de `pip` en entornos Windows, proporcionando una experiencia similar a la de una terminal Unix.

- **`pip` y GitHub**: Puedes usar `pip` para instalar paquetes directamente desde repositorios de GitHub. Esto es útil cuando necesitas una versión específica de un paquete que aún no está disponible en PyPI.

### Cómo actualizar `pip`
Puedes actualizar `pip` usando el siguiente comando en tu terminal o en Git Bash:
```sh
pip install --upgrade pip       #Este comando descarga e instala la última versión de `pip`.
```

12. Hacer al primer commit de este trabajo y unirlo al repositorio remoto.
13. Enviar el enlace del repositorio remoto donde tiene que tener un README.md con todos los detalles de lo que les fui mostrando en comandos, y las respuesta del punto 11 de más arriba.
