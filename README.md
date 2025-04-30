# # Documentación del Sistema - Prueba3-main

## 1. Diagrama de Arquitectura
![image](https://github.com/user-attachments/assets/13e175a6-9f54-4547-812e-626968e3edaf)

## 2. Diagrama de Clases
![image](https://github.com/user-attachments/assets/64136fd7-f4c0-40b7-a2c2-981a6ff57b6a)

## 3. Diagrama de flujo de datos

1.Diagrama de Flujo de Datos - Menú Principal

![image](https://github.com/user-attachments/assets/0e0ff9c0-c100-484b-aa41-a25a1eba0877)

2. Diagrama de Flujo de Datos - Formulario Empleado
![image](https://github.com/user-attachments/assets/f811bb82-3ceb-47e3-91b4-4926810a94e9)

3. Diagrama de Flujo de Datos - Conexión a la Base de Datos

![image](https://github.com/user-attachments/assets/4613aa48-e86f-4299-82d6-87fada9a3984)

4. Diagrama de Flujo de Datos - Selección de Operación en Formularios

![image](https://github.com/user-attachments/assets/9d8fd3a6-a4f5-47a2-8a5b-3c48c623e1d2)

5. Diagrama de Flujo de Datos - Formulario Salon
   
![image](https://github.com/user-attachments/assets/ebbcaef2-d94b-48e3-8ad9-76d577dfeb25)

6. Diagrama de Flujo de Datos - Formulario Tutor
    
![image](https://github.com/user-attachments/assets/943df477-5114-4b15-aee2-27137eb98cd3)

7. Diagrama de Flujo de Datos - Opción Salir
    
![image](https://github.com/user-attachments/assets/6858925b-3d91-461b-b402-6a4a0693a484)

## 4. Manual de Usuario 

## 1. Introducción

Bienvenido al sistema **Prueba3**, una aplicación web desarrollada con el framework **Django**, cuyo objetivo es permitir la **creación** y **visualización** de publicaciones o "posts" de forma sencilla y eficiente.

Este manual está diseñado para guiar al usuario desde la instalación inicial hasta el uso completo de la plataforma, proporcionando además soluciones a problemas comunes.

---

## 2. Requisitos del Sistema

### Requisitos de Software:
- **Sistema operativo**: Windows 10/11, macOS 10.13+ o cualquier distribución Linux.
- **Python**: Versión 3.8 o superior.
- **Pip**: Gestor de paquetes de Python.
- **Virtualenv**: (Opcional, recomendado para manejo de entornos virtuales).

### Hardware recomendado:
- Procesador: Dual-Core 2GHz o superior.
- Memoria RAM: 4 GB mínimo.
- Espacio en disco: 500 MB libres.

---

## 3. Instalación

### Paso 1: Clonar el proyecto

```bash
git clone <URL-del-repositorio>
```

### Paso 2: Crear y activar un entorno virtual (opcional, pero recomendado)

**En Windows:**
```bash
python -m venv env
env\Scripts\activate
```

**En macOS/Linux:**
```bash
python3 -m venv env
source env/bin/activate
```

### Paso 3: Instalar las dependencias

```bash
pip install django
```

*Nota:* Si el proyecto incluye un `requirements.txt`, utilícelo:

```bash
pip install -r requirements.txt
```

### Paso 4: Configurar la base de datos

```bash
python manage.py migrate
```

### Paso 5: Ejecutar el servidor de desarrollo

```bash
python manage.py runserver
```

Acceda a la aplicación en su navegador:

```
http://127.0.0.1:8000/
```

---

## 4. Uso del Sistema

### 4.1 Crear una Publicación

1. Dirígete a:
   ```
   http://127.0.0.1:8000/crear/
   ```
2. Complete los campos del formulario:
   - **Título**: Nombre de la publicación.
   - **Contenido**: Texto o cuerpo de la publicación.
3. Presione el botón **Crear Post**.
4. Será redirigido a la página de listado de publicaciones.

### 4.2 Visualizar Publicaciones Existentes

1. Acceda a:
   ```
   http://127.0.0.1:8000/
   ```
2. Visualizará una lista de todas las publicaciones creadas con:
   - Título
   - Contenido
   - Fecha de creación
---

Manual de instalación
Descargar la carpeta .zip 

![image](https://github.com/user-attachments/assets/cf6ded2e-8d0d-4ce1-996c-180748438dc1)

Descomprimir la carpeta .zip, en tu compuradora

![image](https://github.com/user-attachments/assets/4f618c11-cf10-4cf3-bd0c-71bc45b49987)

Ingresar a la carpeta de “GUARDERÍA”

![image](https://github.com/user-attachments/assets/7ded4dbb-3e28-4e22-ba35-427e4c1c2a2f)

Dar click en el archivo “GUARDERÍA” para comenzar con la instalacion

![image](https://github.com/user-attachments/assets/7da20e63-2b3b-4c52-b5f2-296860924668)

Permitir la instalación, dando en el botón de “Instalar”

![image](https://github.com/user-attachments/assets/2db5a776-d113-4bfb-8a9e-722c2bd2476b)

La aplicación comenzará a instalarse, terminando el proceso ya podrás utilizarla

![image](https://github.com/user-attachments/assets/f9372a84-717a-431f-871d-0f8453aba9b8)

Manula de usuario
Abre tu aplicación de guardería

![image](https://github.com/user-attachments/assets/9f565d7d-5e34-4d2f-8562-8dd85527ce65)

Pantalla principal 
Tendras las opciones de dar de alta a un Empleado, Salon Tutor y expediente

![image](https://github.com/user-attachments/assets/db321a1d-e5aa-4583-a3cc-46de05321cd3)

En todos los módulos tendrás estas opciones
Primer botón: Guardar información
Segundo botón: Editar información guardada
Tercer botón: Buscar información
Cuarto botón: Eliminar información guardada
Quinto botón: ir a menú principal 

![image](https://github.com/user-attachments/assets/bc54c1d7-a156-4c9c-98e9-f1fd6cd25ad5)

EMPLEADO
Alta de empleado
Llena todos los campos y presiona el primero boton, recuerda no repetir los códigos ya qué generará un error de registro, te saldra una confirmación qué se registró correctamente la información, das en el botón de “aceptar” y podrás ver qué en la parte de abajo se refleja la información subida.

![image](https://github.com/user-attachments/assets/00361bfc-d78f-44fa-8b1f-f55820a41305)

![image](https://github.com/user-attachments/assets/9da1c4c1-6495-42a2-8e70-78cac6370efa)

Consulta de empleado
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar

![image](https://github.com/user-attachments/assets/9136756e-3276-4940-a942-c14713affb75)

Actualización de empleado
Paso 1:
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar
Paso 2: 
Procedemos a editar los campos qué quieres editar, presionas el segundo botón y te aparecerá una ventana donde te dirá qué se realizó la actualización correctamente, presionas  “aceptar” para continuar y quedarán guardados los cambios.

![image](https://github.com/user-attachments/assets/eae7e6fd-c819-4e18-9fec-65108d407c8e)

![image](https://github.com/user-attachments/assets/3061d85a-63f0-4f2e-a11c-e8cce79fb054)

Eliminación de empleado
Ingresa el código del cual quieres eliminarla información, presionas el cuarto botón,te aparecerá una ventana donde te dirá qué se realizó la eliminación correctamente, presionas  “aceptar” para continuar y quedará eliminada la información.

![image](https://github.com/user-attachments/assets/a7b7002f-4ec8-48db-a61a-a975bd60748d)


Salon
Alta de salon
Llena todos los campos y presiona el primero boton, recuerda no repetir los códigos ya qué generará un error de registro, te saldra una confirmación qué se registró correctamente la información, das en el botón de “aceptar” y podrás ver qué en la parte de abajo se refleja la información subida.

![image](https://github.com/user-attachments/assets/86f36d66-937f-489a-b1d2-b16d2b77b613)

![image](https://github.com/user-attachments/assets/bddfe246-abb2-46ef-9b84-eabe5bb8a4c6)

Consulta de salon
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar

![image](https://github.com/user-attachments/assets/8fe6d25b-ef04-42df-8e88-5c9586a97ec9)


Actualización de salon
Paso 1:
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar
Paso 2: 
Procedemos a editar los campos qué quieres editar, presionas el segundo botón y te aparecerá una ventana donde te dirá qué se realizó la actualización correctamente, presionas  “aceptar” para continuar y quedarán guardados los cambios.

![image](https://github.com/user-attachments/assets/994ab199-ee8e-4147-bbd7-15f4b46da799)

Eliminación de salon
Ingresa el código del cual quieres eliminarla información, presionas el cuarto botón,te aparecerá una ventana donde te dirá qué se realizó la eliminación correctamente, presionas  “aceptar” para continuar y quedará eliminada la información.

![image](https://github.com/user-attachments/assets/755ca783-a12b-4ccc-91eb-7457d210d520)


Tutor
Alta de tutor
Llena todos los campos y presiona el primero boton, recuerda no repetir los códigos ya qué generará un error de registro, te saldra una confirmación qué se registró correctamente la información, das en el botón de “aceptar” y podrás ver qué en la parte de abajo se refleja la información subida.

![image](https://github.com/user-attachments/assets/acfca88b-fb51-4cc7-87ac-741bf103796a)




Consulta de tutor
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar

![image](https://github.com/user-attachments/assets/b56e89a2-63d4-4c32-b80b-8cd979f22088)

Actualización de tutor
Paso 1:
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar
Paso 2: 
Procedemos a editar los campos qué quieres editar, presionas el segundo botón y te aparecerá una ventana donde te dirá qué se realizó la actualización correctamente, presionas  “aceptar” para continuar y quedarán guardados los cambios.

![image](https://github.com/user-attachments/assets/9865fd64-1419-46e8-a288-7a97635e6fed)

Eliminación de tutor
Ingresa el código del cual quieres eliminarla información, presionas el cuarto botón,te aparecerá una ventana donde te dirá qué se realizó la eliminación correctamente, presionas  “aceptar” para continuar y quedará eliminada la información.

![image](https://github.com/user-attachments/assets/c1e2debe-19f6-4aa6-bbb4-0b017dc0fcf8)

Expediente
Alta de expediente
Llena todos los campos y presiona el primero boton, recuerda no repetir los códigos ya qué generará un error de registro, te saldra una confirmación qué se registró correctamente la información, das en el botón de “aceptar” y podrás ver qué en la parte de abajo se refleja la información subida.

![image](https://github.com/user-attachments/assets/5b29fb29-6d5a-430f-991c-f6a1a6257021)


Consulta de expediente
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar

![image](https://github.com/user-attachments/assets/445f8386-99c1-4e35-ae7c-1a59e1e341a1)

Actualización de empleado
Paso 1:
Ingresa el código del cual quieres consultar la información, presionas el tercer botón y te mostrará la información en los campos, te aparecerá una ventana donde te dirá qué se realizó la consulta correctamente, presionas  “aceptar” para continuar
Paso 2: 
Procedemos a editar los campos qué quieres editar, presionas el segundo botón y te aparecerá una ventana donde te dirá qué se realizó la actualización correctamente, presionas  “aceptar” para continuar y quedarán guardados los cambios.
![image](https://github.com/user-attachments/assets/80b08d03-7bd9-49d4-bb4c-688ff5f197c2)

Eliminación de expediente
Ingresa el código del cual quieres eliminarla información, presionas el cuarto botón,te aparecerá una ventana donde te dirá qué se realizó la eliminación correctamente, presionas  “aceptar” para continuar y quedará eliminada la información.
![image](https://github.com/user-attachments/assets/22697522-838d-4b66-8559-9f06354a3597)

