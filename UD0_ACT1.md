# UD0_ACT1 - Lenguaje de marcas y sistemas de gestión de la información

Rubén Racero Villa
Fecha: 21-09-2026

1.Crea un archivo de texto llamado textos.txt

Mi conclusión es que al crear en archivo txt y abrirlo con el navegador se ve tal cual lo has escrito como texto plano, en cambio si lo abres con .html, al tener h1 y h3 son modificadores y aplica el formato correspondiente por eso h1 se ve en grande y h3 un poco mas pequeño

2. Observa el siguiente fragmento de un texto

<dam>
  <modulo>
   <titulo>Base de datos</titulo>
   <contenido>
    <unidad>Introducción</unidad>
    <unidad>Sistemas de almacenamiento de la información</unidad>
    <unidad>Diseño lógico de bases de datos</unidad>
   </contenido>
  </modulo>

  <modulo>
   <titulo>Planificació i Administració de Xarxes</titulo>
   <contenido>
    <unidad>Introducción</unidad>
    <unidad> Capa física</unidad>
    <unidad> Capa de enlace</unidad>
   </contenido>
  </modulo>

  <modulo>
   <titulo>Fonaments de Maquinari</titulo>
   <contenido>
    <unidad>Introducción</unidad>
    <unidad>Sistemas Informáticos. Estructura Funcional.</unidad>
    <unidad>  Sistemas Informáticos. Estructura Física</unidad>
   </contenido>
  </modulo>
</dam>

3. Crea tu propio documento SGML indicando vocabulario y reglas. Implementa los
datos para PAISES DEL MUNDO.
Vocabulario: paises, pais, nombre, capital, continente, idioma, poblacion
Reglas:
- Un documento `paises` contiene varios `pais`.
- Un `pais` tiene: `nombre`, `capital`, `continente`, `idioma` y `poblacion`.
- Todos los elementos dentro de `pais` son de texto simple.
- El orden recomendado es: nombre → capital → continente → idioma → poblacion.
- Detrás de un `pais` solo puede ir otro `pais` o el fin de `paises`.

<paises>
  <pais>
    <nombre>España</nombre>
    <capital>Madrid</capital>
    <continente>Europa</continente>
    <idioma>Español</idioma>
    <poblacion>47615034</poblacion>
  </pais>

  <pais>
    <nombre>Francia</nombre>
    <capital>París</capital>
    <continente>Europa</continente>
    <idioma>Francés</idioma>
    <poblacion>67750000</poblacion>
  </pais>

  <pais>
    <nombre>Japón</nombre>
    <capital>Tokio</capital>
    <continente>Asia</continente>
    <idioma>Japonés</idioma>
    <poblacion>125700000</poblacion>
  </pais>

  <pais>
    <nombre>Brasil</nombre>
    <capital>Brasilia</capital>
    <continente>América del Sur</continente>
    <idioma>Portugués</idioma>
    <poblacion>215300000</poblacion>
  </pais>

  <pais>
    <nombre>Australia</nombre>
    <capital>Canberra</capital>
    <continente>Oceanía</continente>
    <idioma>Inglés</idioma>
    <poblacion>26400000</poblacion>
  </pais>
</paises>

4. Modifica con un lenguaje de marcas la siguiente información para darle estructura
y significado semántico al documento. Indica vocabulario y reglas.

Vocabulario: biblioteca, libro, titulo, autor, isbn, paginas, editorial, idioma, formato, descripcion, año

Reglas:
- Un documento `biblioteca` contiene varios `libro`.
- Un `libro` contiene: `titulo`, `autor`, `isbn`, `paginas`, `editorial`, `idioma`, `formato` y opcionalmente `descripcion` y `año`.
- Todos los elementos hijos de `libro` son de texto simple.
- Detrás de un `libro` solo puede ir otro `libro` o el fin de `biblioteca`.

<biblioteca>
  <libro>
    <titulo>FALCO</titulo>
    <formato>En papel</formato>
    <isbn>9788420419688</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <paginas>296</paginas>
    <editorial>ALFAGUARA</editorial>
    <idioma>CASTELLÀ</idioma>
  </libro>

  <libro>
    <titulo>TODO ALATRISTE</titulo>
    <formato>EBOOK</formato>
    <isbn>9788420425528</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <editorial>ALFAGUARA</editorial>
    <idioma>CASTELLÀ</idioma>
  </libro>

  <libro>
    <titulo>HOMBRES BUENOS</titulo>
    <formato>En papel</formato>
    <isbn>9788466329804</isbn>
    <autor>ARTURO PEREZ REVERTE</autor>
    <editorial>PUNTO DE LECTURA</editorial>
    <año>2024</año>
    <descripcion>La heroica aventura de quienes se atrevieron a cambiar el mundo con libros. En tiempos de oscuridad siempre hubo hombres buenos que lucharon para llevar las luces y el progreso. Y otros que procuraron impedirlo.</descripcion>
  </libro>
</biblioteca>
