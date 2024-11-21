# Automatización de pruebas de la aplicación web
> [!NOTE]
> Este aplicativo esta hecho para uso libre, acontinuación su función:

## Descripción
Para este proyecto, se probaron la funcionalidad web de forma automatizada por medio de pycharm de Urban Routes. Todo realizado en entornos Google Chrome
Ejecutado segun la parametrización de los requerimientos de la app, de acuerdo a la información de la prueba se debe ejecutar lo siguiente:

Ejercicio 1
1. Escribir varias pruebas para comprobar la funcionalidad de Urban Routes. Escribe tus pruebas en el archivo main.py. Define los localizadores y métodos necesarios en la clase UrbanRoutesPage y las pruebas en la clase TestUrbanRoutes.
2. Escribir pruebas automatizadas que cubran el proceso completo de pedir un taxi. Las pruebas deben cubrir estas acciones:
- Configurar la dirección.
- Seleccionar la tarifa Comfort.
- Rellenar el número de teléfono.
- Agregar una tarjeta de crédito. (Consejo: el botón 'link' (enlace) no se activa hasta que el campo CVV de la tarjeta en el modal 'Agregar una tarjeta', id="code" class="card-input", pierde el enfoque. Para cambiar el enfoque, puedes simular que el usuario o usuaria presiona TAB o hace clic en otro lugar de la pantalla).
- El repositorio tiene preparada la función retrieve_phone_code() que intercepta el código de confirmación requerido para agregar una tarjeta.
- Escribir un mensaje para el controlador.
- Pedir una manta y pañuelos.
- Pedir 2 helados.
- Aparece el modal para buscar un taxi.
- Esperar a que aparezca la información del conductor en el modal (opcional). Además de los pasos anteriores, hay un paso opcional que puedes comprobar; este es un poco más complicado que los demás, pero es una buena práctica, ya que es probable que en tu trayectoria profesional encuentres tareas más difíciles.
- Aparecerá el modal de búsqueda de conductor y habrá una cuenta regresiva mientras se asigna un conductor. El modal cambiará de mostrar la búsqueda de un taxi a mostrar la información del viaje, como se muestra a continuación:

> [!TIP]
> Estos son los requisitos para poder ejecutar las pruebas automatizadas

# Diseño de pruebas para la funcion "Crear un kit".
- Conecta tu GitHub
- Clona el repositorio en tu computadora
- Trabaja con el proyecto de forma local
- Generar el enlace con la url del servidor
- Se requiere tener instalado pycharm
- Instalar pytest en el proyecto
- Instalar pip en el proyecto
- Cambiar ulr en el archivo configuration.py
- Ejecutar los archivos create_kit_name_kit_test.py y sender_stand_request.py

# Tecnologias usadas:
- pycharm
- Libreria pytest
- Libreria pip
- Pruebas Manuales
- Pruebas funcionales
- Pruebas no funcionales

> [!IMPORTANT]
> Para validar la información contenida requieres leer esto:

## Ejecución de Pruebas 
1. Clona el repositorio localmente.
2. Ejecutar los archivos desde la aplicación de pytest.

> [!IMPORTANT]
> Estado del proyecto

## Estado:
- Completado

## Presentado por:
- Leonardo Lombana Contento

## Proyecto parte del sprint 8 - Automatización de pruebas de la aplicación web
## Grupo 12 bootcamp QA Engineer - Tripleten
