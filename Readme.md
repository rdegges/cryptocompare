criptocompare
CryptoCompare es un sitio web estático que compara los precios de las criptomonedas con las monedas populares.

Utiliza HTML, Javascript y CSS simples y antiguos para representar una aplicación muy simple de una página que le muestra:

Las 10 principales criptomonedas por capitalización de mercado
Todos los precios de las criptomonedas durante la última hora, día y semana
Esto es útil para las personas interesadas en especular sobre los mercados de criptomonedas, ya que puede echar un vistazo al rendimiento a corto plazo para tener una idea de cómo le gustaría especular.

imagen del sitio web

Detalles técnicos
Esta aplicación está construida con HTML antiguo simple y Bootstrap para CSS. También estoy usando un tema Bootstrap llamado Simplex que hace que las cosas se vean un poquito mejor.

La parte de Javascript del sitio funciona con Vue.js , un marco de Javascript muy simple.

También estoy usando:

vue2-filtros , una biblioteca Vue.js simple que proporciona algunos filtros de plantilla útiles para mostrar texto. En esta aplicación, solo utilizo el filtro para ayudar a mostrar bien los valores de las monedas.
axios , una biblioteca de JavaScript simple para realizar solicitudes HTTP
Por último, los datos de este sitio web funcionan con dos servicios API gratuitos e independientes:

coinmarketcap , que proporciona una lista de las 10 principales criptomonedas y los detalles de sus precios, y
cryptocompare , que proporciona metadatos sobre todas las criptomonedas, incluidas sus respectivas imágenes de logotipos (que es para lo que uso esto)
