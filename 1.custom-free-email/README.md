
<h1 align="center"> Cómo enviar correos desde tu dominio totalmente GRATIS?</h1>

<hr/>

<figure>
	<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/cover.png" width="100%" alt="portada del blog"/>
</figure>

  

### Introducción

Muchas startups, compañias reclutadoras, emprendimientos y hasta programadores cuentan con un dominio propio para su página web, pero siguen haciendo uso de correos informales (e.g. gabriel.recruitments@gmail.com, johan.dev@gmail.com, entre otros), hecho que en muchas ocasionas no brinda la confianza suficiente a los clientes o personas que quieran contactarlos.

Si bien se sabe que algunas compañías prestan el servicio de correos personalizados por un pago mensual, en muchos casos no nos podemos permitir un gasto adicional y por ello propongo una alternativa para poder tener un correo corporativo totalmente **GRATIS**.

  

### Requisitos

- Un dominio propio.

- Una cuenta de GMAIL.

  

### Pasos

Para poder llevar a cabo la configuración es necesario realizar 2 grandes pasos:

  

1. Redireccionar mensajes recibidos a través del dominio (e.g. webmaster@johanaltamar.com) al correo de Gmail.

2. Configurar correo de Gmail para que los mensajes enviados parezcan enviados desde el correo personalizado (contacto@johanaltamar.com), y a esto se le conoce con el nombre de ***alias***.

  

### 1. Redireccionar los mensajes recibidos

Para esto va a ser necesario una herramienta externa totalmente gratuita que pueden encontrar en [improvmx.com](improvmx.com), ésta nos permite redireccionar los mensajes que recibamos para webmaster@johanaltamar.com en la dirección johan@gmail.com, por citar un ejemplo.

  

 1. Es necesario ingresar el dominio y dirección de correo electrónico, luego hacer click en <b><em>Create a free alias</em></b>, Figura 1.
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-1.png" width="100%"/>
		<figcaption align="center">
		Figura 1. Ingresa dominio y correo electrónico.
		</figcaption>
	</figure>

 2. Configura las direcciones de correo habilitadas para recibirlos (e.g. webmaster@johanaltamar.com, rrhh@johanaltamar.com, entre otros ). Puedes dejar el símbolo <b>*</b> para habilitar todas las posibles combinaciones. Luego haz click en <b><em>Email forwarding needs setup</em></b> para configurar el dominio, Figura 2.
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-2.png" width="100%"/>
		<figcaption align="center">
		Figura 2. Configuración de las direcciones de correo personalizadas.
		</figcaption>
	</figure>

 3. Ve al panel de administración de tu dominio y modifica las entradas DNS.
Primero es necesario agregar las entradas <b>MX</b>, Figura 3.1
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-3.1.png" width="100%"/>
		<figcaption align="center">
		Figura 3.1. Agregar entradas MX en panel de administración del dominio.
		</figcaption>
	</figure>
Posteriormente es necesario agregar un registro SPF, del tipo TXT. Figura 3.2
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-3.2.png" width="100%"/>
		<figcaption align="center">
		Figura 3.2. Agregar entrada TXT en panel de administración del dominio.
		</figcaption>
	</figure>
	

 4. Una vez confirmado los registros en el dominio debería aparecer el servicio como activo y podremos hacer las pruebas con el botón <b>TEST</b>, Figura 4.
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-4.png" width="100%"/>
		<figcaption align="center">
		Figura 4. Servicio activo y botones para pruebas.
		</figcaption>
	</figure>

 5. Como método de verificación, al hacer click sobre el dominio los registros DNS deben salir marcados con un símbolo de OK, Figura 5, en vez de una cruz como en la Figura 3.1 y 3.2.
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-5.png" width="100%"/>
		<figcaption align="center">
		Figura 5. Verificación de los registros DNS.
		</figcaption>
	</figure>  

### 2. Configurar correo de Gmail

Una vez configurado el dominio para poder redirigir los correos a nuestra cuenta de GMAIL es necesario configurar este para que se puedan enviar correos como elijamos (e.g rrhh@johanaltamar.com) y eso se conoce como ***alias***.

  

1. Para que este método funcione es necesario tener habilitado la ***Autenticación en 2 pasos***, si no la tienes puedes activarla [aquí](https://www.google.com/landing/2step/) o puedes verificarlo desde el perfil de tu cuenta de Google, Figura 6.
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-6.png" width="100%"/>
		<figcaption align="center">
		Figura 6. Autenticación en 2 pasos activa.
		</figcaption>
	</figure>

2. Una vez verificado y activado, es necesario crear una ***Contraseña de aplicación*** desde el panel de seguridad de la cuenta de Google. Luego se selecciona la aplicación como **Otra (nombre personalizado)**, se elige el nombre y se hace click sobre el botón **generar**. La contraseña generada es una combinación de 16 caracteres. Figura 7.
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-7.png" width="100%"/>
		<figcaption align="center">
		Figura 7. Contraseña de aplicaciones.
		</figcaption>
	</figure>

3. Luego te dirijes a tu correo de Gmail e ingresas a la siguiente ruta:
Gmail -> Configuraciones -> Todos los ajustes -> Cuentas e importación -> Añadir otra dirección de correo electrónico. Esto abrirá una ventana, Figura 8, donde se debe llenar el nombre y la dirección de correo que queremos que aparezca como *remitente* del mensaje.
	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-8.png" width="100%"/>
		<figcaption align="center">
			Figura 8. Creando alias.
		</figcaption>
	</figure>

4. Posteriormente se completan los campos como sigue, Figura 9:
	- Servidor SMTP: smtp.gmail.com
	- Puerto: 587
	- Nombre de usuario: tu correo de gmail
	- Contraseña: la contraseña creada en el paso 2

	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-9.gif" width="100%"/>
		<figcaption align="center">
			Figura 9. Configuración del servidor.
		</figcaption>
	</figure>

  

5. Google te enviará un correo con un código para que confirmes la propiedad del correo que quieres agregar, Figura 10.

	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-10.png" width="100%"/>
		<figcaption align="center">
			Figura 10. Código de verificación.
		</figcaption>
	</figure>

  

6. Después de el paso anterior puedes intentar enviar un correo nuevo y tendrás la oportunidad de escoger la dirección desde la que se va a enviar, Figura 11.

	<figure>
		<img src="https://cdn.jsdelivr.net/gh/JohanAltamar/portfolio-assets@main/1.custom-free-email/step-11.png" width="100%"/>
		<figcaption align="center">
			Figura 11. Dirección escogida.
		</figcaption>
	</figure>

  

### Conclusión

De esta forma puedes enviar y recibir correos usando tu dominio de forma gratuita, cabe resaltar que tiene ciertas restricciones por cuestiones de seguridad como limitar el tamaño de los archivos adjuntos, así como también las extensiones de estos. La plataforma asegura dentro de sus políticas de privacidad que los correos no son almacenados a menos que ocurra un error durante la entrega y una vez este haya llegado a su destino se borraría. Si tienes alguna duda, puedes contactarme en blog@johanaltamar.com. Saludos y gracias por tomarte el tiempo de leer y poner en práctica. Espero haya sido de mucha ayuda.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMzUwMDg3MDE1XX0=
-->