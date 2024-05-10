##Practica de interface 
Soriano

Se presentara la primera intefaz de practica del tercer semetre de la universidad de guayaquil.

Imagen de ejemplo del Proyecto
![image](https://github.com/brayton992/brayton992/assets/142423609/8ec719c2-d129-4386-9746-c72f82db4bdc)

Textfield

Se creó un campo de texto en el diseño del proyecto. En el código, se utiliza la clase TextField para crear un campo de texto. Luego, se establece su posición vertical (top) y horizontal (left) dentro de un contenedor AnchorPane. Finalmente, se agrega el campo de texto al AnchorPane para que sea visible en la interfaz de usuario.

ListView

Se crea un ListView vacío y se le asigna una posición dentro de un AnchorPane. En este ejemplo, se posiciona en la esquina superior izquierda con coordenadas específicas (20.0 desde la parte superior y 220.0 desde la izquierda). Posteriormente, el ListView se agrega al AnchorPane, permitiendo que sea visible en la interfaz de usuario.

Metodo label

El método agregarLabels está diseñado para agregar múltiples etiquetas al AnchorPane llamando repetidamente al método agregarLabel. Cada vez que se llama a agregarLabel, se especifica el texto y la posición de una etiqueta diferente dentro del AnchorPane. De esta manera, el método agregarLabels facilita la adición de varias etiquetas con texto y posiciones personalizadas al diseño.

Agregar el label

El método agregarLabel crea un objeto Label con el texto proporcionado y luego establece su posición dentro del AnchorPane utilizando los métodos estáticos setTopAnchor y setLeftAnchor de la clase AnchorPane. Por último, agrega el Label al AnchorPane llamando al método getChildren().add(label) del AnchorPane.

Metodos usadors

 El método agregarImagen se utiliza para agregar imágenes al AnchorPane utilizando una URL que indica dónde está ubicada la imagen en el sistema. Esta función también incluye la capacidad de escalar la imagen para que se ajuste a un tamaño específico y se posiciona dentro del AnchorPane utilizando las coordenadas proporcionadas como argumentos.

El método agregarLabel se utiliza para agregar una etiqueta específica al AnchorPane, con el texto proporcionado y las posiciones especificadas.
