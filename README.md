# 🎧🎶 Dejame escuchar música🎵🌆
## Descripción del proyecto 
Este proyecto tiene como objetivo analizar las preferencias musicales de dos ciudades ficticias, Springfield y Shelbyville, utilizando datos reales de transmisión de música online. Como analista de datos, se realizarán diferentes etapas clave para obtener información valiosa sobre el comportamiento de los usuarios de ambas ciudades🏙️.
El análisis permitió obtener insights sobre las tendencias musicales de los usuarios, lo que puede ser útil para la toma de decisiones en el ámbito de la música online, el marketing y otros sectores. A lo largo del proyecto, se usaron herramientas estadísticas y técnicas de análisis de datos para validar las suposiciones sobre los gustos musicales de estas dos ciudades. 

## Motivación 
La motivación principal es entender cómo varían los gustos musicales en diferentes comunidades, lo cual es crucial para tomar decisiones informadas en sectores como la música online y el marketing. Al obtener insights sobre las tendencias musicales de los usuarios, el proyecto busca ofrecer información valiosa que ayude a mejorar la personalización de servicios musicales, así como a optimizar estrategias de marketing. A través de herramientas estadísticas y técnicas de análisis de datos, se validaron suposiciones sobre las preferencias de estas ciudades, permitiendo así un análisis más preciso y fiable. Este enfoque ayuda a generar estrategias más efectivas y a mejorar la experiencia del usuario en plataformas de streaming musical.

## Dataset 
Los datos alojados en el dataset contienen las siguientes columnas: 

'userID': identifica de forma exclusiva a cada usuario o usuaria;

'Track': título de la canción;

'artist': nombre del artista;

'genre': género musical;

'City': ciudad del usuario o la usuaria;

'time': hora del día en la que se reprodujo la pista (HH:MM:SS);

'Day': día de la semana.

## Herramientas utilizadas 
### Lenguaje:
Python 
### Librerias:
Pandas

## Proceso del Poyecto 
### Introducción
### Etapa 1. Descripción de los datos

### Etapa 2. Preprocesamiento de datos.
El objetivo aquí es preparar los datos para que sean analizados. El primer paso es resolver cualquier problema con los encabezados. Luego podemos avanzar a los valores ausentes y duplicados.
2.1 Estilo del encabezado
2.2 Valores ausentes
2.3 Duplicados

### Etapa 3. Prueba de hipótesis
Hipótesis: comparar el comportamiento del usuario o la usuaria en las dos ciudades
La hipótesis afirma que existen diferencias en la forma en que los usuarios y las usuarias de Springfield y Shelbyville consumen música. Para comprobar esto, usa los datos de tres días de la semana: lunes, miércoles y viernes.

Agrupa a los usuarios y las usuarias por ciudad.
Compara el número de canciones que cada grupo reprodujo el lunes, el miércoles y el viernes.
Realiza cada cálculo por separado.

El primer paso es evaluar la actividad del usuario en cada ciudad. Recuerda las etapas dividir-aplicar-combinar de las que hablamos anteriormente en la lección. Tu objetivo ahora es agrupar los datos por ciudad, aplicar el método apropiado para contar durante la etapa de aplicación y luego encontrar la cantidad de canciones reproducidas en cada grupo especificando la columna para obtener el recuento.

A continuación se muestra un ejemplo de cómo debería verse el resultado final: df.groupby(by='....')['column'].method()Realiza cada cálculo por separado.

Para evaluar la actividad de los usuarios y las usuarias en cada ciudad, agrupa los datos por ciudad y encuentra la cantidad de canciones reproducidas en cada grupo.


3.1 Hipótesis 1: actividad de los usuarios y las usuarias en las dos ciudades

### Conclusiones
Se puden ver claramente las diferencias de la actividad de los usarios tanto en las varientes del día de la semana, así como en la ciudad en la que se encuentran. Al comparar entre las ciudades Shelbyville y Sprinfield, los usuarios de esta ultima ciudad son evidentemente más activos que de la otra, sin importar el día de la semana que sea. De la misma manera, se puede notar que el día con mayor actividad es el viernes mientras que el día con menor actividad es el miércoles, para ambas ciudades.
