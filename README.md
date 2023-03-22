# Equipoo 2
Codigo de python para utilizar prolgo para calcular la distancia mas corta

 ## Version de python
  3.7.3
  ## Version de PROLOG
  8.0.2

 # Instalación local  

## 1. Crear un entorno virtual para la instalación de las librerias

~~~bash  
   python -m venv venv
~~~
o bien  

~~~bash  
   python3 -m venv venv
~~~

    
## 2. Ingresar al enntorno virtual:

#### Linux:

~~~bash 
    source venv/bin/activate
~~~

#### Windows:

~~~bash  
    .\venv\Scripts\activate.bat
~~~
 o bien 

~~~bash  
    .\venv\Scripts\activate  
~~~

## 3. Instalar prolog 


#### Linux:

1) Instala SWI-Prolog:
    ```
    sudo apt install swi-prolog 8.0.2
    ```
    If you don't want the X bindings, just use the `swi-prolog-nox` package.

2

3) Instala pyswip del paquete de Python usando:
    ```
    pip install pyswip
    ```

## 4. Instalar las librerias necesarias que se encuentran en el archivo "requirements.txt"

~~~bash  
     pip install -r requirements.txt
~~~

o bien 

~~~bash  
    pip3 install -r requirements.txt
~~~

 
