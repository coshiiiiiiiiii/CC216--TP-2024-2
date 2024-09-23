# CC216--TP-2024-2

## Índice 
[1. Objetivo](https://github.com/coshiiiiiiiiii/CC216--TP-2024-2/edit/main/README.md#objetivo)

[2. Integrantes](https://github.com/coshiiiiiiiiii/CC216--TP-2024-2/edit/main/README.md#integrantes)

[3. Descripción del Dataset](https://github.com/coshiiiiiiiiii/CC216--TP-2024-2/edit/main/README.md#descripci%C3%B3n-del-dataset)

[4. Conclusiones](https://github.com/coshiiiiiiiiii/CC216--TP-2024-2/edit/main/README.md#conclusiones)

## Objetivo
El objetivo del TP es realizar un análisis exploratorio de datos (EDA) grupal, utilizando el conjunto de datos Hotel Booking Demand. Este análisis se llevará a cabo mediante el uso de R/RStudio, con el fin de explorar la estructura del dataset, identificar datos faltantes y atípicos, y generar visualizaciones que permitan extraer conclusiones iniciales. A través de este análisis, se busca comprender los patrones de demanda de reservas de hoteles urbanos y resorts, así como identificar tendencias relevantes, como el comportamiento de las reservas a lo largo del tiempo, las temporadas de mayor y menor demanda, y el impacto de variables como la cantidad de niños y plazas de estacionamiento disponibles.

Este análisis permitirá obtener información valiosa para la toma de decisiones en sectores relacionados, como el marketing hotelero, la optimización de la ocupación y la predicción de la demanda futura.

## Integrantes 
| Nombre  | Código |
| ------------- | ------------- |
| Ariana Graciela Quelopana Puppo  | U202122430  |
| Gabriel Alonso Reyna Alvarado  | U202126097  |
| Alexandra Fong Saravia | U202216001 |
|Leonardo David Joaquín Rodríguez|U202213866|

## Descripción del Dataset
![avt](https://github.com/user-attachments/assets/729353c2-4e6a-462e-86cd-e17b64f00f39)
El conjunto de datos Hotel Booking Demand recopila información sobre reservas de dos tipos de hoteles: un hotel urbano y un resort. Contiene detalles relacionados con la fecha de la reserva, la duración de la estancia, el número de adultos, niños, y bebés incluidos en la reserva, la cantidad de plazas de estacionamiento disponibles, el tipo de habitación, entre otros datos relevantes para la administración hotelera.

El dataset ha sido modificado específicamente para este trabajo, incorporando ruido en forma de datos faltantes (NA) y valores atípicos (outliers), lo cual añade complejidad al análisis. Estos datos proporcionan una oportunidad para realizar tareas de preprocesamiento, como la imputación de valores faltantes y la gestión de outliers.

**Variables principales del dataset:**

1. Hotel (Categórico): Indica el tipo de hotel (Resort Hotel, City Hotel)
2. Arrival_date (Fecha): Fecha de llegada al hotel.
3. Children (Numérico): Número de niños incluidos en la reserva.
4. Adults (Numérico): Número de adultos incluidos en la reserva.
5. Babies (Numérico): Número de bebés incluidos en la reserva.
6. Is_canceled (Categórico): Indica si la reserva fue cancelada o no.
7. Parking_spaces (Numérico): Número de plazas de estacionamiento reservadas.

Este dataset permitirá responder preguntas clave, como las preferencias de los clientes entre tipos de hoteles, las tendencias de la demanda a lo largo del tiempo, y el impacto de la disponibilidad de plazas de estacionamiento en las decisiones de reserva​

## Conclusiones
