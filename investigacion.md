# Investigación: ¿esto ya existe? ¿quién lo dice?

> Instrucción: sustituye lo que está entre corchetes y borra las líneas que empiezan con
> "Instrucción:". Todos los enlaces deben abrir. Un enlace roto o inventado anula el
> criterio correspondiente.

**Autor:** [José Antonio Magallanes]
**Fecha:** [17/09/2026]
**Ideas analizadas:** [[ideas-proyecto]]

---

## Parte 1. Un ejemplo que ya existe, por cada idea

> Instrucción: busca algo parecido que alguien ya haya construido: un producto, un
> proyecto de otra universidad, un repositorio, un tutorial. Encontrar que ya existe no
> arruina tu idea; te dice desde dónde empezar.

### Idea 1: [Medidor de humedad para pasto]

- **Qué encontré:** [GARDENA smart Sensor, un sensor inteligente de humedad del suelo para jardines.]
- **Enlace:** [GARDENA smart Sensor](https://www.gardena.com/es/productos/smart-system/smart-system/sensor-smart/967986501.html?utm_source=chatgpt.com)
- **Qué hace:** [Mide la humedad del suelo y envía la información a la aplicación GARDENA smart. También puede utilizarse junto con un sistema de riego automático para evitar regar cuando el suelo todavía está suficientemente húmedo.]
- **Por qué no resuelve mi caso:** [Es un producto comercial diseñado para un sistema específico de jardinería. Mi propuesta busca desarrollar un sistema propio que, además de medir la humedad, pueda utilizar machine learning para reconocer patrones y anticipar cuándo será necesario regar, y que presente la información de una manera sencilla para personas sin experiencia.]

### Idea 2: [Ventanas inteligentes]

- **Qué encontré:** [OLIDE WiFi Smart Automatic Window Actuator with Wireless Rain Sensor.]
- **Enlace:** [OLIDE Smart Automatic Window Actuator](https://www.olidesmart.com/products/olide-wifi-smart-automatic-window-actuator-with-wireless-rain-sensor?utm_source=chatgpt.com)
- **Qué hace:** [Es un sistema que permite abrir y cerrar ventanas automáticamente y controlarlas desde el teléfono. También cuenta con un sensor de lluvia que puede cerrar automáticamente la ventana cuando comienza a llover.]
- **Por qué no resuelve mi caso:** [El producto está principalmente enfocado en detectar lluvia y controlar la ventana de manera remota. Mi propuesta busca combinar **temperatura interior, temperatura exterior y humedad**, además de permitir que el usuario establezca sus propios límites de temperatura para decidir cuándo abrir o cerrar la ventana.]

### Idea 3: [Implante medidor]

- **Qué encontré:** [Eversense, un sistema de monitoreo continuo de glucosa con un sensor implantable.]
- **Enlace:** [Artículo sobre el sistema Eversense en PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC7783000/?utm_source=chatgpt.com)
- **Qué hace:** [Utiliza un sensor colocado debajo de la piel para medir continuamente la glucosa en el líquido intersticial. La información puede enviarse a un dispositivo móvil y el sistema puede generar alertas relacionadas con niveles altos o bajos de glucosa.]
- **Por qué no resuelve mi caso:** [El sistema está diseñado específicamente para medir **glucosa**, principalmente para el manejo de la diabetes. Mi propuesta busca analizar una cantidad mayor de factores relacionados con la alimentación y utilizar esos datos para generar recomendaciones personalizadas. Además, desarrollar un implante que mida múltiples nutrientes, grasas y otros factores sería considerablemente más complejo.]

---

## Parte 2. Fuentes de la idea que elegí

> Instrucción: de dos a tres fuentes, solo de la idea elegida. Todavía no se pide formato
> APA; eso llega más adelante en el curso. Lo que se pide es que distingas quién publicó
> la información y por qué le crees.

### Fuente 1

| Campo                | Contenido                                                                                                                                                                                    |
| -------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Autor u organización | University of Illinois Urbana-Champaign                                                                                                                                                      |
| Título               | Smart Home Conditioning System                                                                                                                                                               |
| Año                  | No especificado                                                                                                                                                                              |
| Enlace               | [University of Illinois Urbana-Champaign](https://courses.grainger.illinois.edu/ece445/project.asp?id=11767&utm_source=chatgpt.com)                                                          |
| Tipo                 | Proyecto universitario                                                                                                                                                                       |
| Por qué le creo      | Es un proyecto publicado por la Facultad de Ingeniería de la University of Illinois Urbana-Champaign y describe los componentes y funcionamiento de un prototipo construido por estudiantes. |
| Qué dato me dio      | El proyecto utiliza sensores de temperatura y humedad, un sensor de lluvia y motores para abrir y cerrar automáticamente una ventana dependiendo de las condiciones ambientales.             |

### Fuente 2

| Campo                | Contenido                                                                                                                                                                 |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Autor u organización | University of Technology MARA (UiTM)                                                                                                                                      |
| Título               | Automatic window rain detector                                                                                                                                            |
| Año                  | 2015                                                                                                                                                                      |
| Enlace               | [University of Technology MARA (UiTM)](https://ir.uitm.edu.my/id/eprint/64039/?utm_source=chatgpt.com)                                                                    |
| Tipo                 | Proyecto universitario                                                                                                                                                    |
| Por qué le creo      | Está publicado en el repositorio institucional de una universidad y presenta un proyecto desarrollado por estudiantes.                                                    |
| Qué dato me dio      | El prototipo utiliza un sensor de humedad o agua para detectar lluvia y un Arduino que controla un motor para cerrar automáticamente la ventana cuando comienza a llover. |

### Fuente 3 (opcional)

| Campo | Contenido |
|---|---|
| Autor u organización | [ ] |
| Título | [ ] |
| Año | [ ] |
| Enlace | [ ] |
| Tipo | [ ] |
| Por qué le creo | [ ] |
| Qué dato me dio | [ ] |

---

## Parte 3. Qué haría distinto

[Mi propuesta busca que la ventana no solo detecte la lluvia, sino que también tome en cuenta la temperatura del exterior. El usuario va a poder establecer desde una aplicación las condiciones en las que quiere que las ventanas se abran o cierren. También buscaría que el sistema tenga un costo accesible y que pueda adaptarse a diferentes tipos de ventanas]

## Parte 4. Qué me falta averiguar

- [ ] [Qué tipo de motor o actuador sería el más adecuado para abrir y cerrar diferentes tipos de ventanas.]
- [ ] [Qué sensores necesito para medir correctamente la temperatura, humedad y lluvia.]
- [ ] [Cuánta fuerza necesita el motor para mover una ventana real y cuánto peso puede soportar el mecanismo.]

---

## Declaración de uso de IA

- **Herramienta utilizada:** [Chatgpt-5.6 Luna]
- **Qué le pedí:** [que me ayudara a encontrar productos que tuvieran similitudes y fuentes de informacion]
- **Qué modifiqué o rechacé de su respuesta, y por qué:** [Cambie las fuentes de informacion para que sean recursos que pueden ayudar a construir el sistema y no solo comprarlo]
