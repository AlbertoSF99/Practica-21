# Práctica 21 - Creación de un bot con QnA Maker

## Innovaccion Virtual (VII Edición) #IAWizards

### Semana 3 - Sesión 8

En esta práctica se realizó un bot que contesta preguntas con respuestas pre-entrenadas.

------------------------------------------------------

#### Requerimientos
- Cuenta de Azure con suscripción. 

-------------------------------------------------------

#### Pasos a seguir

1. Accedemos a la siguiente página: [https://www.qnamaker.ai/Home/MyServices](https://www.qnamaker.ai/Home/MyServices) y nos logueamos con la nuestra cuenta. Una vez habiendo ingresado, le damos en ‘Create a knowledge base’ y le damos en ‘Create a QnA Service’. Inmediatamente nos redirigirá a una nueva pestaña de Porta Azure donde tendremos que llenar los datos solicitados para la creación del QnA Maker.

![P21I1](https://github.com/AlbertoSF99/Practica-21/blob/main/Images/Sesi%C3%B3n%208%20-%20P21%2001.PNG)

2. Una vez creado el recurso, esperamos un rato para poder agregarlo en la pestaña de QnA Maker. En todo caso, podremos dar ‘Refresh’ e intentar de nuevo. Para los demás campos, los llenamos, como, por ejemplo, el apartado de ‘Language’ escogemos ‘Spanish’. Habiendo configurado todo como queramos, le damos en ‘Create your KB’.

3. Una vez creado el KB, le damos en ‘Add QnA pair’ y en la entrada de la izquierda agregamos la pregunta, mientras que en la entrada de la derecha donde dice ‘Enter an answer’ se introducen la respuesta a la pregunta. Podremos agregar tantas preguntas y respuesta como queramos, en los que también podremos agregar imagen. En el apartado de ‘Add aternative phrasing’ podremos agregar preguntas similares a las cuales el bot contestará con una misma respuesta.

![P21I2](https://github.com/AlbertoSF99/Practica-21/blob/main/Images/Sesi%C3%B3n%208%20-%20P21%2002.PNG)

4. Ya habiendo agregado todas las preguntas y respuesta que se requieran, le damos en ‘Save and train’ y en la opción de ‘Test’ podremos probar el desempeño del bot. Podremos darle en ‘Publish’ y te mostrará en pantalla un link, el cual lo puedes incorporar en alguna aplicación o servidor para implementar ese bot, o lo puedes implementar directamente en Azure dándole a la opción de ‘Create Bot’, esta opción nos redirigirá a una pestaña de Azure Portal donde le podremos modificar algunas opciones y finalmente, crearla.

![P21I3](https://github.com/AlbertoSF99/Practica-21/blob/main/Images/Sesi%C3%B3n%208%20-%20P21%2003.PNG)

![P21I4](https://github.com/AlbertoSF99/Practica-21/blob/main/Images/Sesi%C3%B3n%208%20-%20P21%2004.PNG)

![P21I5](https://github.com/AlbertoSF99/Practica-21/blob/main/Images/Sesi%C3%B3n%208%20-%20P21%2005.PNG)

![P21I6](https://github.com/AlbertoSF99/Practica-21/blob/main/Images/Sesi%C3%B3n%208%20-%20P21%2006.PNG)

5. Para agregarla a un servicio como Teams, vamos al apartado de ‘Canales’ y le damos en Microsoft Teams para después darle en ‘Aplicar’. Regresamos a ‘Canales’ y al canal de Teams le damos en ‘Open in Teams’ y ya se podrá usar.

![P21I7](https://github.com/AlbertoSF99/Practica-21/blob/main/Images/Sesi%C3%B3n%208%20-%20P21%2007.PNG)
