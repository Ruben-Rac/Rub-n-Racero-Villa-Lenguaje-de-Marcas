necesita que en el css de targeta sea position: relative para que la etiqueta se coloque extactamente en su esquina
Al poner overflow hidden si sobresale la targeta por arriba no se ve porque todo lo que salga de la targeta no se ve se recorta para solucionarlo se tendra que poner la etiqueta no tan al borde para que no la corte y se vea completamente
overflow: visible-> los comentarios sobresalen del cuadrado 
overflow: hidden-> todo lo que esta fuera del cuadrado no se ve y se corta
overflow: scroll-> te pone a la derecha una barra para ir bajando y tambien otra abajo para ir viendo todas las frases que no caben en el cuadrado. Siempre aparecen si hacen falta o si no
overflow: auto solo tiene la barrra de la derecha para las frases. Solo aparecen si hacen falta
visibility: hidden: Oculta el elemento, pero este sigue ocupando su espacio en la página.
display: none: Oculta el elemento y elimina su espacio por completo, haciendo que los demás elementos se reubiquen. 
