# Conversor de Monedas

## Resumen del Proyecto

Este proyecto es una **aplicación web** llamada **"Conversor de Monedas"** que permite a los usuarios convertir pesos chilenos (CLP) a otras monedas internacionales, como dólares, euros, entre otras. La aplicación utiliza una interfaz simple con campos de entrada y un botón para realizar la conversión. Además, se muestra un gráfico que ilustra la evolución del tipo de cambio.

## Funcionalidades del Proyecto

| Funcionalidad              | Descripción                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| **Ingreso de Datos**        | El usuario ingresa una cantidad en pesos chilenos (CLP) en un campo de texto. |
| **Selección de Moneda**     | El usuario selecciona la moneda de destino en un desplegable (select).       |
| **Conversión de Moneda**    | Al hacer clic en el botón "Convertir", se realiza la conversión y se muestra el resultado en el sitio. |
| **Visualización de Gráfico**| Se muestra un gráfico utilizando **Chart.js** que ilustra la evolución del tipo de cambio en el tiempo. |
| **Interfaz Interactiva**    | La página permite realizar varias conversiones en tiempo real sin necesidad de recargarla. |

## Tecnologías Utilizadas

| Tecnología     | Descripción                                                              |
|----------------|--------------------------------------------------------------------------|
| **HTML**       | Se utiliza para estructurar el contenido de la página web.               |
| **CSS**        | Estiliza la interfaz de usuario, incluyendo la disposición de los elementos y el fondo de la página. |
| **JavaScript** | Controla la lógica de conversión de monedas y la interacción con el usuario. |
| **Chart.js**   | Librería de JavaScript utilizada para crear y mostrar gráficos dinámicos (en este caso, un gráfico de tipo de cambio). |
| **Google Fonts** | Se utiliza la fuente **Inter** para mejorar la legibilidad y estética del texto. |

## Estructura Visual del Proyecto

| Elemento                    | Descripción                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| **Contenedor Principal**     | La página está contenida en un `div` con clase `container`, centrado en la pantalla con un fondo semitransparente. |
| **Título**                  | Un encabezado `h1` que presenta el nombre de la aplicación, "Conversor de Monedas". |
| **Formulario de Conversión** | El formulario contiene un campo de entrada de número, un selector de moneda y un botón para realizar la conversión. |
| **Resultado**               | Un área (`div`) donde se muestra el resultado de la conversión, además de un gráfico. |
| **Gráfico**                 | Un `canvas` que utiliza Chart.js para visualizar los resultados de la conversión de moneda en un gráfico dinámico. |

## Autora del Proyecto
- **Autora**: [LeBrokennn](https://github.com/LeBrokennn)
