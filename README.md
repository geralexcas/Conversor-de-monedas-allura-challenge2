
# Conversor de Monedas

<p>Este proyecto es una aplicación de consola en Java que permite realizar conversiones de moneda utilizando la API de ExchangeRate-API. El programa también mantiene un historial de las conversiones realizadas y ofrece un menú interactivo para seleccionar diferentes opciones de conversión. Esta aplicación es parte del Challenge 2 de la plataforma Alura.</p>

## Descripción del Proyecto
Este proyecto es una aplicación de conversión de monedas que permite a los usuarios convertir pesos colombianos (COP) a diferentes monedas extranjeras, incluyendo USD, EUR y JPY. La aplicación utiliza una API externa para obtener las tasas de cambio actuales y realiza los cálculos de conversión en tiempo real.

## Características

- Conversión de COP a USD
- Conversión de COP a EUR
- Conversión de COP a JPY
- Historial de conversiones realizadas

<h2>Funcionalidades</h2>
<li>
  Convertir de Peso Colombiano (COP) a otras monedas: USD, EUR, y JPY.

  <li>Mostrar un historial de todas las conversiones realizadas.</li>
<li>Menú interactivo para seleccionar la opción deseada. </li>
<h2>Requisitos</h2>
<li>Java 11 o superio</li>
<li>Biblioteca Gson para deserializar respuestas JSON de la API.</li>

## Estructura Del proyecto
 ```plaintext
.
├── models
│   ├── DetallesMoneda.java
│   └── Historial.java
├── principal
│   ├── Main.java
│   └── Principal.java
├── service
│   └── ConsumoApi.java
└── README.md

```

## Instalación

1. Clona el repositorio:
    ```sh
    git clone https://github.com/geralexcas/Conversor-de-monedas-allura-challenge2.git
    ```
2. Navega al directorio del proyecto:
    ```sh
    cd Conversor-de-monedas-allura-challenge2
    ```
3. Ejecuta la aplicación:
    ```sh
    java -jar conversor-de-monedas.jar
    ```
    ## Uso

Al ejecutar la aplicación, se mostrará un menú en la consola donde puedes seleccionar la conversión deseada y la cantidad a convertir. La aplicación mostrará el resultado de la conversión y guardará la consulta en un historial.

## Ejemplo de Conversión

![Ejemplo de conversión](https://github.com/geralexcas/Conversor-de-monedas-allura-challenge2/blob/master/images/ejemplo-conversion.png)
 
## Tecnologías Utilizadas
Este proyecto utiliza varias tecnologías para proporcionar una aplicación robusta y eficiente para la conversión de monedas. A continuación se describen las principales tecnologías empleadas:
## :hammer:java
-`Descripción:` Java es un lenguaje de programación de propósito general, concurrente, orientado a objetos y basado en clases.

-`Uso en el Proyecto:` Java es el lenguaje principal en el que está escrita la aplicación. Se utiliza para la lógica de conversión, manejo de datos y comunicación con la API externa.

## Librería Gson
-`Descripción:` Gson es una librería de Java que permite la conversión entre objetos Java y su representación JSON.

-`Uso en el Proyecto:` Se utiliza para convertir las respuestas JSON de la API de tasas de cambio en instancias de objetos Java (DetallesMoneda).

## API de Tipo de Cambio
-`Descripción:` La API de tipo de cambio (Exchange Rate API) proporciona tasas de cambio actualizadas para varias monedas.
-`Uso en el Proyecto:` La aplicación realiza solicitudes HTTP a esta API para obtener las tasas de cambio necesarias para las conversiones de moneda.

## HTTP Client
-`Descripción:` El HttpClient es una herramienta de Java para realizar solicitudes HTTP.
-`Uso en el Proyecto:` Se utiliza para enviar solicitudes a la API de tipo de cambio y recibir las respuestas en formato JSON.

## Control de Versiones con Git y GitHub
-`Descripción:` Git es un sistema de control de versiones distribuido, y GitHub es una plataforma basada en la web para el alojamiento de repositorios Git.
-`Uso en el Proyecto:` Git se utiliza para el control de versiones del código fuente, y GitHub para alojar el repositorio del proyecto, permitiendo la colaboración y el seguimiento del historial de cambios.

## IntelliJ IDEA
-`Descripción:` IntelliJ IDEA es un entorno de desarrollo integrado (IDE) para el desarrollo de software.
-`Uso en el Proyecto:` Se utiliza como IDE principal para escribir, depurar y ejecutar el código Java del proyecto.

## Contribuciones
Las contribuciones son bienvenidas. Por favor, crea un fork del repositorio y abre un pull request con tus cambios

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Ver el archivo LICENSE para más detalles
