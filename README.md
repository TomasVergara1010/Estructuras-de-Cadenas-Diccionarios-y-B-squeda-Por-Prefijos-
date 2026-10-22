# Estructuras-de-Cadenas-Diccionarios-y-B-squeda-Por-Prefijos-

🍎 Sistema de Autocompletado para una Frutería
Descripción
El proyecto consiste en desarrollar una búsqueda de frutas para la caja registradora de una pequeña frutería. Al escribir las primeras letras de una fruta, el sistema encuentra sugerencias y permite consultar el precio asociado a una fruta.

El objetivo es aplicar cadenas, diccionarios y árboles de prefijos (Trie) para resolver una necesidad práctica mediante estructuras de datos.
Dataset
Los datos utilizados corresponden a un catálogo de frutas y sus precios, definidos dentro del código del proyecto. No se utiliza un dataset externo.

El catálogo incluye nombres de frutas como manzana, mango, mandarina, maracuyá, mora, melón y melocotón, junto con sus precios en pesos colombianos (COP).
Tecnologías
- Python 3: lenguaje de programación.
- Diccionarios (dict): almacenan los nodos del Trie y relacionan cada fruta con su precio.
- random: permite seleccionar aleatoriamente una sugerencia en la simulación. Es una librería incluida en Python, por lo que no requiere instalación adicional.
- Google Colab : entorno recomendado para ejecutar el archivo del proyecto.
Implementación
El proyecto utiliza dos estructuras de datos principales:
Árbol de prefijos (Trie)
Se insertan los nombres de las frutas carácter por carácter. Cuando se proporciona un prefijo, el árbol localiza el nodo correspondiente y recorre las ramas que comparten esas letras para obtener las coincidencias.
Diccionario de precios
Se utiliza un diccionario que relaciona el nombre de cada fruta con su precio. Una vez obtenida una sugerencia, el sistema consulta el diccionario para mostrar el precio correspondiente.
Flujo de funcionamiento
1. Se insertan las frutas en el Trie.
2. Se almacenan sus precios en un diccionario.
3. Se busca un prefijo configurado en el código.
4. Se muestran las frutas que coinciden con ese prefijo.
5. Se selecciona una sugerencia al azar para simular la elección.
6. Se consulta y muestra el precio de la fruta seleccionada

Resultados
El sistema encuentra las frutas cuyo nombre comienza con el prefijo indicado y muestra las coincidencias. Después selecciona una sugerencia al azar y consulta su precio en el diccionario.

Por ejemplo, con el prefijo m, pueden aparecer frutas como mango, manzana, mandarina, mora, melón, maracuyá y melocotón. La fruta seleccionada y el orden de las sugerencias pueden variar según la ejecución.

La aplicación demuestra cómo el Trie facilita las búsquedas por prefijo y cómo el diccionario permite consultar el precio de una fruta por su nombre.
Autores

- Jhonatan Oquendo
- Tomás Vergara
