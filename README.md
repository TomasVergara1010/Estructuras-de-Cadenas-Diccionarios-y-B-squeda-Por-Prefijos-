# Estructuras-de-Cadenas-Diccionarios-y-B-squeda-Por-Prefijos-

Buscador de productos de Amazon por prefijo
Descripción
Este proyecto implementa un buscador de productos de Amazon que utiliza una estructura de datos Trie para encontrar nombres de productos a partir de las primeras letras que escriba el usuario. Cuando encuentra coincidencias, selecciona una sugerencia al azar y muestra información disponible del producto, como el precio con descuento y la calificación.

El proyecto está desarrollado en Python y se ejecuta en Google Colab.
Objetivos
- Cargar un conjunto de datos de productos de Amazon.
- Implementar una estructura de datos Trie.
- Insertar los nombres de los productos en el Trie.
- Buscar productos a partir de un prefijo.
- Mostrar una sugerencia aleatoria y algunos de sus datos.
Tecnologías y herramientas
- Python
- Google Colab
- KaggleHub, para descargar el conjunto de datos.
- Trie, estructura de datos utilizada para la búsqueda por prefijos.
Conjunto de datos

El notebook descarga el conjunto de datos amazon-sales-dataset de Kaggle, publicado por karkavelrajaj, mediante KaggleHub. Después carga el archivo amazon.csv y utiliza la columna product_name para construir el buscador.
¿Cómo funciona?
1. Descarga los datos de Amazon y carga el archivo CSV con Pandas.
2. Obtiene los nombres de los productos que no están vacíos.
3. Crea un Trie e inserta los nombres de los productos en minúsculas.
4. Solicita al usuario las primeras letras del producto que desea buscar.
5. Busca todos los productos cuyos nombres comienzan con ese prefijo.
6. Si hay coincidencias, elige una al azar y muestra su nombre, precio con descuento y calificación cuando esos datos están disponibles.
7. Si no hay coincidencias, informa que no se encontraron productos con ese prefijo.
Cómo ejecutar el proyecto
1. Abre el notebook en Google Colab.
2. Ejecuta las celdas en orden, desde la primera hasta la última.
3. Cuando el programa lo solicite, escribe las primeras letras del nombre de un producto.
4. Revisa las coincidencias y la sugerencia que muestra el programa.
El notebook descarga el conjunto de datos durante la ejecución. Se necesita conexión a internet y un entorno que permita instalar o utilizar las dependencias necesarias.
Ejemplo de uso
Si el usuario escribe un prefijo como sams, el programa busca nombres de productos que comiencen con esas letras. Si encuentra coincidencias, selecciona una al azar y muestra los detalles disponibles.

El resultado depende de los productos presentes en el conjunto de datos.
Estructura del proyecto
- Caso_Amazon.ipynb: notebook con la descarga y carga de datos, la implementación del Trie y el buscador interactivo.
  
## 👥 Integrantes

| Integrante | GitHub | 
|---|---|
| **Tomás Vergara** | [@TomasVergara1010](https://github.com/TomasVergara1010) | 
| **Jhonatan Oquendo** | [@Tatan072](https://github.com/Tatan072) | 

<div align="center">
  
📚 Proyecto académico · Asignatura **Estructuras de Datos**
