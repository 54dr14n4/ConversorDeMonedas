<em> # *Convertidor de Monedas* </em>

<em> *Descripcion* </em>
<em> Este proyecto es un Challenge de Alura Latam y Oracle Next education. El objetivo a lograr es contruir un conversor de monedas, los diversos tipos de cambio actuales desde una API (EschangeRate) y permite convertir cantidades entre diferentes monedas. </em>

<em> El conversor de monedas tiene un menu donde el usuario puede seleccionar diferentes opciones entre distintas monedas. para convertir entre diferentes monedas. El programa tiene las siguientes opciones:

<em> Dólar (USD) a Peso Mexicano (MXN) </em>
<em> Peso argentino (MXN) a Dólar (USD) </em>
<em> Dólar (USD) a Peso colombiano (COP) </em>
Peso colombiano (COP) a Dólar (USD)
Dólar (USD) a Real brasileño (BRL)
Real brasileño (BRL) a Dólar (USD)
Covertir otra moneda
Salir </em>

<em> *Estructura del Proyecto* </em>

El proyecto tiene tres clases:

ConsultarMoneda: Esta clase es la encargada de realizar la solicitud HTTP a la API de ExchangeRate y obtener las tasas de cambio que el usuario necesite.
ConvertirMonedas: Esta clase es la encargada de realizar las operaciones matematicas.
Principal: Esta clase contiene el menú interactivo y la lógica principal del programa.
Monedas: Esta clase almacena los datos de las tasas de cambio obtenidos de la API.

<em> *Recursos Utilizados* </em>
Java 17.
IntelliJ IDEA.
ExchangeRate.
Library Gson.
