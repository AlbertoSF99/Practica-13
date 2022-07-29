# Práctica 12 - Creación de una base de datos con Cosmos DB

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 2 - Sesión 6

En esta práctica se creó una base de datos por medio de Cosmos DB desde el portal de Azure.

--------------------------------------------------------------

#### Requerimientos

- Cuenta de Azure con suscripción.

---------------------------------------------------------------

#### Pasos a seguir

1. En portal.azure.com buscamos ‘Cosmos DB’ y le damos en ‘Crear’ y entre las opciones que mostrará en pantalla le damos en ‘Nucleo (SQL)’ para crearlo. Llenamos los campos necesarios para crear dicho servicio y dejamos todo lo demás como está, para después darle en ‘Crear’.

![P13I1](Images\Sesión 6 - P13 01.PNG)

![P13I2](Images\Sesión 6 - P13 02.PNG)

2. Una vez creado el recurso, accedemos a él y en elegir una plataforma escogemos el que queramos (para este caso, Node.js) y creamos el contenedor. Una vez creado, se puede descargar la aplicación de .NET.

![P13I3](Images\Sesión 6 - P13 03.PNG)

3. Entramos a la opción ‘Abrir el Explorador de datos’ y le damos en la pestaña de ‘New Item’.

![P13I4](Images\Sesión 6 - P13 04.PNG)

4. En el apartado de código, podemos poner una lista, como, por ejemplo: “id”: 1, “nombre”: “Alberto”, “apellido”: “Salgado”. Para guardar estos cambios, le damos en la opción de ‘Guardar’. Podemos realizar una nuevo item, y escribir otros elementos.

![P13I5](Images\Sesión 6 - P13 05.PNG)

![P13I6](Images\Sesión 6 - P13 06.PNG)

5. Una vez capturado los ítems que se necesiten, le damos en ‘New SQL Query’ y ‘Execute Query’ y escribimos `SELECT * FROM C where c.id=1` y le damos en ‘Save Query’.

![P13I7](Images\Sesión 6 - P13 07.PNG)

![P13I8](Images\Sesión 6 - P13 08.PNG)

6. Habiendo seguido los pasos posteriores a ‘Save Query’ le damos a la pestaña ‘Execute Query’ y nos mostrará el dato solicitado del paso 5.

![P13I9](Images\Sesión 6 - P13 09.PNG)

***Información Adicional:*** Cada que se quiera escribir un nuevo elemento en un nuevo item, debe ir separado por una coma y después un enter.