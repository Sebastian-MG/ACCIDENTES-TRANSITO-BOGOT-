### Guía de Uso
A continuación, se detalla cómo instalar y utilizar la aplicación.

### Requisitos Previos 📋
Es necesario tener instalado Python 3.7 o superior en el sistema y configurado en las variables de entorno (aquí).

### Proceso de Instalación 🔧
Para la instalación, primero debemos descargar esta carpeta del repositorio PaginaWeb. Una vez descargada, abrimos una línea de comandos (CMD, PowerShell, etc.) y nos ubicamos sobre el directorio de la carpeta descargada.

Comenzaremos creando un entorno virtual para la aplicación, de esta manera no afectaremos nuestro sistema. Para ello, en la consola ejecutamos el siguiente comando, eligiendo el nombre_entorno_virtual que prefiramos (venv generalmente):

```
python -m venv nombre_entorno_virtual
```

Esperamos a que se complete la instalación, y cuando termine, activamos el entorno virtual:

```
.\nombre_entorno_virtual\Scripts\activate
```

Veremos el nombre del entorno virtual al inicio de la línea de comando. Por ejemplo, en este caso llamamos al entorno virtual test:

```
(test) PS C:\PaginaWeb> 
```

Finalmente, instalamos los requisitos necesarios con el comando:

```
pip install -r requirements.txt
```

### Puesta en Marcha 🚀
Ahora, ejecutaremos Flask para poder acceder a la página. Así que, con el entorno virtual activado y los requerimientos instalados, procedemos a escribir lo siguiente:

```
flask run 
```

Si todo es correcto, veremos que podemos acceder a nuestro desarrollo a través de localhost:

```
* Running on http://127.0.0.1:5000/
```

### Realización de Pruebas ⚙️
Ahora, accederemos al navegador web y escribiremos la dirección de arriba en la barra de direcciones:

```
http://localhost:5000/home
```

### Herramientas Utilizadas 📌
Las siguientes herramientas fueron usadas en el proyecto:

| Biblioteca | Descripción |
| --- | --- |
| **Pandas** | Una biblioteca de manipulación y análisis de datos. |
| **Numpy** | Una biblioteca para el manejo de matrices y operaciones matemáticas de alto nivel. |
| **Geopandas** | Una biblioteca para trabajar con datos geoespaciales. |
| **Matplotlib** | Una biblioteca para la creación de gráficos estáticos, animados e interactivos en Python. |
| **Flask** | Un microframework para desarrollar aplicaciones web en Python. |
| **Seaborn** | Una biblioteca de visualización de datos basada en Matplotlib. |
| **datetime** | Un módulo para manipular fechas y tiempos. |


### Autores ✒️
Sebastian Mancera

