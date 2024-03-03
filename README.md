# Data_GPT_Contratacion
Este proyecto utiliza datos abiertos del gobierno para generar una base de datos de 50000 contratos para la creación de un GPT
# Análisis de Contratos en Nariño

Este proyecto utiliza datos abiertos del gobierno para analizar los contratos celebrados en el departamento de Nariño desde el año 2018. Utiliza la API de Socrata para hacer consultas específicas y filtrar la información relevante como el año de firma del contrato, la entidad, el municipio, entre otros detalles.

## Requisitos Previos

Para ejecutar este proyecto, necesitarás Python instalado en tu sistema. Además, es necesario instalar las siguientes librerías:

- Pandas: Para la manipulación y análisis de datos.
- Sodapy: Para interactuar con la API de Socrata.

Puedes instalar estas dependencias ejecutando:

```bash
pip install pandas sodapy
``` 

## Instalación y Ejecución
Para utilizar este script, sigue estos pasos:

- Clona este repositorio o descarga el código fuente.
- Asegúrate de tener instaladas todas las dependencias mencionadas en la sección de requisitos previos.
- Ejecuta todas las celdas del Notebook

## Uso
Este script realiza una petición a la base de datos del gobierno para obtener información sobre los contratos celebrados en Nariño desde 2018, excluyendo los de prestación de servicios. Filtra las columnas relevantes y exporta los resultados a un archivo CSV llamado contratos_narino.csv.

Una vez ejecutado el script, encontrarás el archivo CSV en el directorio actual, el cual podrás utilizar para tus análisis.

## Contribuciones
Las contribuciones son bienvenidas. Si tienes alguna sugerencia para mejorar este proyecto, por favor, abre un issue o envía un pull request.

## Contacto
Si tienes preguntas, comentarios o necesitas ayuda con el proyecto, no dudes en contactarme:

- Correo Electrónico: contacto@ingeleyton.com ; ingeleyton@gmail.com
- GitHub: [ingeleyton](https://github.com/ingeleyton)
- Pagina Web: https://ingeleyton.com 

No olvides seguirme en GitHub para estar al tanto de este y otros proyectos interesantes.

## Licencia
Este proyecto está licenciado bajo MIT License, lo que significa que puedes utilizar, modificar y distribuir este código bajo los términos de esa licencia.
