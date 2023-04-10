# DOCTOR_FURBBY
## Proyecto de Animatrónico Furby con IA generadora de texto
Este proyecto consiste en la creación de un animatrónico (Furby) que se conecta a una inteligencia artificial generadora de texto a través de un dispositivo ESP32. El animatrónico puede escuchar a través de la tecnología STT (Speech-to-Text) y hablar mediante la tecnología TTS (Text-to-Speech).

## Descripción del proyecto
El objetivo principal de este proyecto es combinar la tecnología de inteligencia artificial con un juguete animatrónico popular para crear una experiencia interactiva única. Se ha utilizado un Furby, que es un muñeco electrónico con movimiento y sonido, como base para este proyecto.

La tecnología STT permite al animatrónico reconocer el habla y convertirlo en texto. A continuación, el texto se envía a la IA generadora de texto, que crea una respuesta en forma de texto. La respuesta se envía al dispositivo ESP32, que se encarga de convertir el texto en habla utilizando la tecnología TTS. El habla generada se reproduce a través del altavoz del animatrónico, lo que da la impresión de que el Furby está hablando.

## Componentes utilizados
- Furby animatrónico
- ESP32
- Módulo de reconocimiento de voz
- Módulo de síntesis de voz
- Altavoz
## Cómo funciona
El módulo de reconocimiento de voz recoge el habla y la convierte en texto.
El texto se envía a la IA generadora de texto, que crea una respuesta.
La respuesta se envía al ESP32.

El ESP32 utiliza el módulo de síntesis de voz para convertir el texto en habla.

El habla generada se reproduce a través del altavoz del Furby, dando la impresión de que el Furby está hablando.

