# ///////////////////Metodos y propiedades para arreglos///////////////////
.lenght
	Para saber la longitud de un arreglo, tambien funciona con cadenas de texto

.push()
	Para agregar un nuevo elemento al final del arreglo

.concat()
	Para contatenar arreglos

.join()
	Sirve para obtener todos los datos de un arreglo y separarlos con el nodo ingresado

.sort()
	Para ordenar el arreglo alfabeticamente

.unshift()
	Agrega un dato al inicio de un array
	
.shif()
	Elimina el primer elemento de un array



# ///////////////////Metodos y propiedades para las cadenas de texto///////////////////
.lenght
	Para saber la longitud de un arreglo, tambien funciona con cadenas de texto

.substring()
	Para cortar caracteres desde la posicion 0 hasta lo indicado 

.substr()
	Para cortar caracteres desde la posicion indicada en el inicio y hasta el final

.indexOF()
	Devuelve la posicion de una letra en una cadena de texto

.lastindexOF()
	Devuelve la posicion de una letra en una cadena de texto, pero esta comienza a contar desde la ultima posicion

.replace()
	Para reemplazar una cadena de texto, recive dos parametros, la palabra que se quiere reemplazar y la palabra por el que se le va a reemplazar

.toUpperCase()
	Para convertir un texto en mayuscula

.toLowerCase()
	Para convertir un texto en minuscula

.startsWith("s")
	Devuele true si la cadena de texto inicia con la letra asingnada y false si no

.endsWith("s")
	Devuelve true si la cadena de texto finalisa con la letra asignada y false si no

.includes("xd")
	Devuelve true si el texto ingresado se encuentra en la cadena de texto.

parseInt(numero)
	Convierte una cadena de texto en un numero entero
parseFloat(numero)
	Convierte una cadena de texto en numeros con punto decimal

# ///////////////////Metodos y propiedades para el DOM///////////////////

.appendChild ()
	Para agregar un nodo al hijo (al final)

.removeChild()
	Para elminar el primer nodo

.insertBefore ()
	Para agregar un nodo al hijo (al inicio), se debe agregar una referencia para saber donde ubicar

.createTextNode()
	Para crear un nodo de texto

.createElement()
	Para crear un elemento HTML por ejemplo un parrafo (p)

.getElementById()
	Para obtener un elemento en el DOM por su ID

.getElementsByTagName[
	Para obtener elementos por su tag (por ejempo p), entre los corchetes se agrega la posicion del elemento (se cuenta desde el 0)

.setAttribute()
	Agregar un atributo a un elemento por ejemplo una clase (class="caja") 



# ///////////////////Objeto Math///////////////////
Math.sqrt(3)
	Devuelve la raiz cuadrada de un numero

Math.cbrt(3)
	Devuelve la raiz cubica de un numero


Math.max(3, 459, 405, 300)
	Devuelve el numero mas grande segun los datos ingresados, (no funciona con Array)


Math.ramdom()
	Devuelve un numero aleatorio

Math.round()
	Redondea un numero (para arriba)

Math.floor()
	Redondea un numero (para abajo)

# ///////////////////Metodos y propiedades para window///////////////////
window.open("url ramdom")
	Esta abre una ventana depende a la url que le indiquemos

window.closed
	Devuelve un valor bolean si es que una ventana esta abierta o cerrada

window.close("url ramdom")
	Cierra la url que le indiquemos

window.confirm("stas seguro?")
	Tira una alerta para confirmar algo, devuelve valores booleanos

window.stop()
	Detiene la carga de una web

window.print()
	imprime la ventana en formato pdf

window.screenLeft
	Devuelve la distancia entre la ventana del navegador y el limite superior izquierdo de la pantalla

window.screenTop
	Devuelve la distancia entre la ventana del navegador y el limite superior de ARRIBA de la pantalla 	


# ///////////////////Metodos y propiedades para Location///////////////////
window.location.href("")
	Devuelve la URL de la pagina actual

window.location.hostname
	Devuelve el nombre de dominio del sitio web actua

window.location.pathname
	Devuelve la ubicacion actual del archivo HTML

window.location.protocol
	devuelve el protocolo de la web (HTTPS, HTTP)


# ///////////////////Metodos y propiedades para las expresiones regulares///////////////////
RegExp('Hola', 'gi')
	Metodo para buscar una palabra en una cadena, recibe la palabra y la bandera

.test()
	para validar si una palabra existe dentro de una cadena, recibe la cadena de texto , devuelve true o false

.exec ()
	devuelve un array con los textos encontrados en una cadena, recibe una cadena de texto, devuelve un array