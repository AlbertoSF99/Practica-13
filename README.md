# Práctica 13 - Creación de una base de datos con Cosmos DB

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 2 - Sesión 6

En esta práctica se creó una base de datos por medio de Cosmos DB desde el portal de Azure.

--------------------------------------------------------------

#### Requerimientos

- Cuenta de Azure con suscripción.

---------------------------------------------------------------

#### Pasos a seguir

1. En portal.azure.com buscamos ‘Cosmos DB’ y le damos en ‘Crear’ y entre las opciones que mostrará en pantalla le damos en ‘Nucleo (SQL)’ para crearlo. Llenamos los campos necesarios para crear dicho servicio y dejamos todo lo demás como está, para después darle en ‘Crear’.

![P13I1](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2001.PNG)

![P13I2](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2002.PNG)

2. Una vez creado el recurso, accedemos a él y en elegir una plataforma escogemos el que queramos (para este caso, Node.js) y creamos el contenedor. Una vez creado, se puede descargar la aplicación de .NET.

![P13I3](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2003.PNG)

3. Entramos a la opción ‘Abrir el Explorador de datos’ y le damos en la pestaña de ‘New Item’.

![P13I4](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2004.PNG)

4. En el apartado de código, podemos poner una lista, como, por ejemplo: “id”: 1, “nombre”: “Alberto”, “apellido”: “Salgado”. Para guardar estos cambios, le damos en la opción de ‘Guardar’. Podemos realizar una nuevo item, y escribir otros elementos.

![P13I5](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2005.PNG)

![P13I6](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2006.PNG)

5. Una vez capturado los ítems que se necesiten, le damos en ‘New SQL Query’ y ‘Execute Query’ y escribimos `SELECT * FROM C where c.id=1` y le damos en ‘Save Query’.

![P13I7](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2007.PNG)

![P13I8](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2008.PNG)

6. Habiendo seguido los pasos posteriores a ‘Save Query’ le damos a la pestaña ‘Execute Query’ y nos mostrará el dato solicitado del paso 5.

![P13I9](https://github.com/AlbertoSF99/Practica-13/blob/main/Images/Sesi%C3%B3n%206%20-%20P13%2009.PNG)

***Información Adicional:*** Cada que se quiera escribir un nuevo elemento en un nuevo item, debe ir separado por una coma y después un enter.
