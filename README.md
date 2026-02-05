Git es un sistema de control de versiones descentralizado. Su función principal es registrar los cambios realizados en archivos de código a lo largo del tiempo.

Utilidad: Permite volver a versiones anteriores, trabajar en diferentes ramas (features) sin romper el código principal y coordinar el trabajo entre varios desarrolladores.

Comandos básicos usados:

git init: Inicializa un repositorio local en la carpeta actual.

git add .: Prepara todos los archivos modificados para el siguiente "commit" (foto del estado actual).

git commit -m "mensaje": Guarda los cambios en el historial local con una descripción.

git push: Sube los cambios del repositorio local al servidor remoto (GitHub).

¿Qué es GitHub? (La plataforma)
GitHub es una plataforma de alojamiento en la nube que utiliza la tecnología Git.

Función: Actúa como un servidor donde guardamos nuestros proyectos (repositorios) para que estén accesibles desde cualquier lugar, facilitando la colaboración, el despliegue de webs y el control de proyectos mediante una interfaz gráfica.

Lenguaje de Marcado: Markdown

    Encabezados: Se definen mediante almohadillas (#). A mayor número de #, menor es el tamaño del título (del H1 al H6).

Énfasis: Se usa el asterisco * o el guion bajo _. Doble símbolo para negrita y símbolo simple para cursiva.

Listas: Se usan números para listas ordenadas y guiones o asteriscos para listas desordenadas (bullets).

No entiendo muy bien que es el marckdown pero bueno 


# ASIX1_0373_A00_Apuntes1
repositorio para entregar los apuntes por primera vez

# ASIX1_0373_A00_IntroGitHub
## primer repositorio
### Es mi primera toma de contacto con github
#### soy marc serra

esto esta en __negrita__ *2 barrabajas
Esto esta en **negrita** tambien

Esto esta en _cursiva_
Esto esta en *cursiva*

__*TEXTO*__
ABRIR ETIQUETA 1
    ABRUR ETIQUETA 2
        contenido
    CERRAR ETIQUETA 2
CERRAR ETIQUETA 1

**_TEXTO_**

1. Elemento
2. Elemento
3. Elemento

* Elemento desordenado 1
+ Elemento desordenado 2
- Elemento desordenado 3



```html
<P>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, 

enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a, tellus. Phasellus viverra nulla ut metus varius laoreet. Quisque rutrum. Aenean imperdiet. Etiam ultricies nisi vel augue. Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. Maecenas nec odio et ante tincidunt tempus. Donec vitae sapien ut libero venenatis faucibus. Nullam quis ante. Etiam sit amet orci eget eros faucibus tincidunt. Duis leo. Sed fringilla mauris sit amet nibh. Donec sodales sagittis magna. Sed consequat, leo eget bibendum sodales, augue velit cursus nunc,</p>  
``` 

[Link](https://www.fcbarcelona.es/es/)

![alt text](./imagen%201.jpeg "imagen de prueba")


| *Jugador* | Equipo | Nombre |
|---------:|:-------:|:--------|
| 32| Lakers | Messi |
| 32| Lakers | Messi |
| 32| Lakers | Messi |



<!--comandos github

        git init
        git add .
        git commit -m “añadidas dos lineas al README”
        git push origin
    
    -->

   
    # H1 - encabezado principal 


    ## H2 - encabezado mas pequeño que el anterior


    ### H3 - encabezado mas pequeño que el anterior 


    #### H4 - encabezado mas pequeño que el anterior 


    ##### H5 - encabezado mas pequeño que el anterior 


    ###### H6 - encabezado mas pequeño que el anterior
    

    <table border="1">
        <thead>

            <tr>
            <th>orden</th>
            <th>atleta</th>
            <th>tiempo</th>
            </tr>

            
        </thead>
        <tbody>

            <tr>
            <td>1</td>
            <td>michel mesi</td>
            <td>2:23:00</td>
            </tr>

            <tr>
            <td rowspan="2">2</td>
            <td colspan="2">penaldo</td>
            
            </tr>

            <tr>
            
            <td>ernesto</td>
            <td>34:23:55</td>
            </tr>


        </tbody>
        <tfoot>

            <tr>
            <td>orden</td>
            <td>atleta</td>
            <td>tiempo</td>
            </tr>
            

        </tfoot>
    </table>
    <caption>tabla clasificatoria maraton bcn</caption>









    <form action="url_destino.html" method="get" target="_blank">

      
        <label>username: </label><input type="text" name="username" value="anonimo"><br>
        <br>
        <label>realname: </label><input type="text" name="realname" id="realname">
        <br>

        <fieldset>
            <legend>carnet de conducir</legend>
            <label for="carnetSI">Si:</label>
            <input type="radio" name="carnet" value="carnetSI" id="carnetSI">
            <label for="carnetNO">No:</label>
            <input type="radio" name="carnet" value="carnetNO" id="carnetNO">
        </fieldset>
          <br>
          <fieldset>
            <legend>gustos musicales</legend>
            <label for="musica">pop</label>
            <input type="checkbox" name="musica()" value="pop" id="pop">
            <label for="heavy">heavy</label>
            <input type="checkbox" name="musica()" value="heavy" id="heavy">
            <label for="heavy">pachanga</label>
            <input type="checkbox" name="musica()" value="pachanga" id="pachanga">
        </fieldset>
         <br>
        <label for="nacionalidad">nacionalidad</label>
        <select id="nacionalidad" name="nacionalidad">
            <option value="espana">espana</option>
            <option value="brasil">brasil</option>
            <option value="usa">usa</option>
        </select><br>
         <br>
        
         <label for="observaciones">observaciones</label><br>
         <textarea name="observaciones" rows="5" cols="30" placeholder="introduce aqui cualquier cosa"></textarea>
        <br>

        <button type="submit" name="enviar" value="enviar">enviar datos</button>

    </form>

<br>
<br>
<br>

    <h1>buenas</h1>

<h2>probando probando</h2> <!--esto es un titulo mas pequeño-->



<p>

    <!--el "em" es para poner en cursiva-->
   <p> 
    <em>ipsum dolor, sit amet consectetur</em>  adi   <!-- esto son comentarios-->
    pisicing elit. Consectetur doloremque volup
    tas dolore molestiae error harum facere a
    dipisci numquam tempora asperiores digniss
    imos sequi omnis facilis, assumenda aut
    laborum repellat veniam quibusdam? 
    Lorem ipsum dolor sit amet consectetur 
    adipisicing elit. Obcaecati aut nesciunt, 
    repellendus soluta magni voluptates ad similique 
    voluptatum enim optio quis illo, neque fugit cumque,
    deleniti ducimus placeat iste eligendi.
    <br> <!-- esto es como un enter-->
    <br> <!-- esto es como un enter-->
    </p>

    <hr> <!--esto es una linea-->

    <p>
    Lorem ipsum dolor sit amet consectetur 
    adipisicing elit. Deleniti, dignissimos 
    sunt officiis nam praesentium iste, numquam, 
    libero officia dolorem maiores perspiciatis 
    dolores quas blanditiis autem at! Ipsum tempora v
    oluptatibus laborum?
    </p>
    
</p>

<ol> <!--lista ordenada-->
    <li>primer elemento</li> 
       <ol>
            <li>subelemento 1.1</li>
            <li>subelemento 1.1</li>
       </ol>
    <li>segundo elemento</li>
    <li>tercero elemento</li>
</ol>

<ul> <!--lista desordenada-->
    <li>elemento desordenado</li> 
    <li>elemento desordenado</li>
    <li>elemento desordenado</li> 
</ul>

    <img src="./escudo barça.jpg" alt="esto es una imagen de prueba"> <!--el alt muestra un texto por si no aparece la imagen-->
    
<!--ejemplo de codigo de formulari abajo-->


    <h1>Contacta amb nosaltres</h1>
<form action="processa.html" method="get">
   <fieldset>
      <legend>Dades personals</legend>
      <div> 
         <label for="nom">Escriu el teu nom: </label> 
         <input type="text" name="nom" size="30" maxlength="100" id="nom"/> 
      </div>
      <div> 
         <label for="contrasenya">Escriu la teva contrasenya: </label> 
         <input type="password" name="contrasenya" size="10" maxlength="15" id="contrasenya"/> 
      </div>
      <div> 
         Edat: 
         <input type="radio" name="edat" id="edat_menor" value="menor" /> 
         <label for="edat_menor">Menys de 18 anys </label> 
         <input type="radio" name="edat" id="edat_major" value="major" checked="checked" /> 
         <label for="edat_major">De 18 a 65 anys </label> 
         <input type="radio" name="edat" id="edat_jubilat" value="jubilat" /> 
         <label for="edat_jubilat">Més de 65 anys</label> 
      </div>
      <div>
         <label for="municipi">On vius? </label> 
         <select name="municipi" id="municipi">
            <option value="Abella de la Conca">Abella de la Conca</option>
            <option value="Abrera">Abrera</option>
            <option value="Àger">Àger</option>
            <option value="Agramunt">Agramunt</option>
            <option value="Aguilar de Segarra">Aguilar de Segarra</option>
            <option value="Agullana">Agullana</option>
            <option value="Aiguafreda">Aiguafreda</option>
            ... 
         </select>
      </div>
      <div> 
         <label for="foto">Envia'ns la teva foto: </label> 
         <input type="file" name="foto" id="foto" /> 
      </div>
   </fieldset>
   <fieldset>
      <legend>Aficions</legend>
      <div> 
         Escull les teves aficions: 
         <input type="checkbox" name="llegir" id="llegir" value="si" /> 
         <label for="llegir">Llegir</label> 
         <input type="checkbox" name="cine" id="cine" value="si" /> 
 <label for="cine">Anar al cine</label> 
         <input type="checkbox" name="trekking" id="trekking" value="si" /> 
         <label for="trekking">Trekking</label> 
      </div>
   </fieldset>
   <fieldset>
      <legend><label for="comentari">Comentaris</label></legend>
      <div> 
         <textarea name="comentari" id="comentari" cols="30" rows="5">Escriu aquí els teus comentaris</textarea> 
      </div>
   </fieldset>
   <div> 
      <input type="reset" value="Esborrar formulari" /> 
      <input type="submit" value="Enviar formulari" /> 
   </div>
</form>



NUEVO APARTADO CSS:





CSS: Evolución y función (1/2)

En los orígenes de la web, HTML era muy sencillo y fácil de aprender y no era capaz de representar recursos gráficos para añadir a la información textual. Eso fue cambiando a medida que el número de sitios web fueron creciendo y con ellos la cantidad de etiquetas que HTML se necesitaba para construir sitios cada vez más atractivos. Se tenían que incluir nuevas etiquetas destinadas a conseguir efectos visuales.

Para evitar que HTML fuese el responsable de la parte estética y visual de la web se idearon las hojas de estilo y el lenguaje CSS (Cascading Style Sheets).

Mientras que HTML estructura el documento e indica a los navegadores la función de un elemento en concreto (un vínculo, un título, …), el CSS da instrucciones al navegador sobre cómo ha de mostrar un elemento concreto: estilo, espaciado, posición…

La versión Transicional de (X)HTML tiene etiquetas relacionadas con la visualización y la presentación de la web, pero es mejor no usar este tipo de etiquetas ya que mezclan la estructura y la presentación del documento.

CSS no es un lenguaje de programación como JavaScript ni un lenguaje de etiquetas como HTML.


CSS: Evolución y función (2/2)

Lo que ahora conocemos como CSS apareció cuando el W3C recibió 9 propuestas diferentes para hojas de estilo, de las cuales seleccionó dos: Cascading HTML Style Sheets (CHSS), propuesta por Håkon Wium Lie en 1994, y Stream-based Style Sheet Proposal (SSP). De ahí nacieron las Cascading Style Sheets (CSS), cuya primera versión, denominada CSS Level 1, fue propuesta como estándar a finales del año 1996.

En mayo de 1998 se publicó el estándar CSS Level 2. Diez años después, en 2008, se realizó una revisión y se publicó el CSS Level 2 Revision 1, conocido como CSS2.1.

Actualmente se está trabajando con CSS3. En este caso, la especificación está dividida en módulos, algunos de los cuales ya se han convertido en estándares, mientras que otros aún están en desarrollo.xº


CSS: Ubicación (1/4).

Los estilos se pueden asociar de diferentes maneras a los elementos (X)HTML dado que se pueden ubicar las propiedades CSS en diferentes ubicaciones:

Estilo “inline”. En la propia etiqueta.

Estilo “interno”. En la cabecera del documento (X)HTML.

Estilo “externo”. En un documento externo.


En la etiqueta HTML: (estilo “INLINE”). Se añaden las propiedades CSS directamente en el elemento usando el atributo “style”. Por ejemplo:

<p style="text-align:center; color:red">Paràgraf centrat vermell</p>

CSS: Ubicación (3/4)

En la cabecera del documento (X)HTML: (estilo INTERNO) Podemos poner diferentes propiedades CSS dentro del elemento <style>, dentro del elemento <head> del documento. Por ejemplo:

<!DOCTYPE html>
<html lang="ca">
<head>
    <!-- ... -->
    <style>
        p {
            text-align: center;
            color: red;
        }
    </style>
</head>
<body>
    <p>Párrafo centrado rojo</p>
    <p>Párrafo centrado rojo</p>
    <p>Párrafo centrado rojo</p>
</body>
</html>


CSS: Ubicación (4/4)

En un documento externo: (estilo externo) Se colocan las propiedades de estilo en un documento externo con extensión .css y desde el documento (X)HTML se enlaza con esta hoja de estilo con la etiqueta <link> dentro del elemento <head>. Por ejemplo:

El documento (X)HTML tendría el siguiente aspecto:

<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="estils.css" type="text/css" />
</head>
<body>
    <p>Paràgraf centrat vermell</p>
</body>
</html>


El fichero estils.css tendría el siguiente contenido:

p {
    text-align: center;
    color: red;
}



CSS: Prioridad (1/4)

Podría darse el caso de que varias declaraciones CSS afectasen de forma diferente a un mismo elemento HTML, así pues, ¿cuál de ellas es la que tendrá preferencia?

En primer lugar, se comprueba si existe una hoja de estilos externa asociada al documento HTML (estilo externo). Si no, estilos en otras ubicaciones son las que se ejecutarán.

En segundo lugar, si hay alguna definición de estilos en el HEAD del documento HTML (estilo interno). En este caso, si alguna definición contradice a la definida en la hoja de estilos externa, tendrá prioridad la definición del estilo interno.

Por último, si hay alguna definición de estilos “inline”, en la propia etiqueta HTML, en caso de contradicción, tendrá prioridad la definida en la propia etiqueta.

Se ha de tener en cuenta también que el orden dentro de cada estilo es importante, teniendo más prioridad “por regla general” los situados más abajo en el documento y que, en caso de que haya declaraciones sobre un mismo elemento en diferentes ámbitos que no sean contradictorias, éstas se suman.


CSS: Prioridad (1/4)

Podría darse el caso de que varias declaraciones CSS afectasen de forma diferente a un mismo elemento HTML, así pues, ¿cuál de ellas es la que tendrá preferencia?

En primer lugar, se comprueba si existe una hoja de estilos externa asociada al documento HTML (estilo externo). Si no, estilos en otras ubicaciones son las que se ejecutarán.

En segundo lugar, si hay alguna definición de estilos en el HEAD del documento HTML (estilo interno). En este caso, si alguna definición contradice a la definida en la hoja de estilos externa, tendrá prioridad la definición del estilo interno.

Por último, si hay alguna definición de estilos “inline”, en la propia etiqueta HTML, en caso de contradicción, tendrá prioridad la definida en la propia etiqueta.

Se ha de tener en cuenta también que el orden dentro de cada estilo es importante, teniendo más prioridad “por regla general” los situados más abajo en el documento y que en caso de que haya declaraciones sobre un mismo elemento en diferentes ámbitos que no sean contradictorias, estas se combinarán.




5. Profundización en HTML: Teoría y Estructura
¿Qué es realmente HTML?
Las siglas significan HyperText Markup Language (Lenguaje de Marcas de Hipertexto):

HyperText: Texto que contiene enlaces a otros recursos o páginas.

Markup: El contenido se organiza y estructura mediante etiquetas.

Language: Posee reglas y una estructura gramatical propia.

Importante: HTML no es un lenguaje de programación, ya que carece de lógica (bucles, condiciones o funciones). Su única función es describir y estructurar el contenido.

Anatomía de un Elemento HTML
Un elemento estándar se compone de:

Etiqueta de apertura: <p>

Contenido: El texto o recurso que queremos mostrar.

Etiqueta de cierre: </p> (Notar la barra inclinada /).

Existen elementos vacíos que no tienen contenido ni cierre, como <img>, <br> o <input>.

Atributos
Los atributos ofrecen información extra sobre un elemento. Siempre se escriben en la etiqueta de apertura con el formato nombre="valor".

Ejemplos comunes: class, id, src, alt, href.

6. Estructura Global de un Documento
Todo archivo HTML debe seguir este esquema jerárquico:

<!DOCTYPE html>: Declaración obligatoria que indica al navegador que el documento es HTML5.

<html>: El elemento raíz que envuelve todo el código.

<head>: El "cerebro" oculto. Contiene metadatos:

<meta charset="utf-8">: Permite mostrar tildes y caracteres especiales.

<title>: El nombre que aparece en la pestaña del navegador (clave para el SEO).

<link>: Para conectar archivos CSS o el favicon (icono de la pestaña).

<style>: Para escribir CSS interno.

<body>: El "cuerpo" visible. Contiene todo lo que el usuario ve (textos, imágenes, botones).

Enlaces y Navegación (<a>)
El sistema de navegación se basa en el Hipertexto.

Externos: Enlazan a otras webs usando href="URL".

Locales: Enlazan a páginas del propio sitio usando rutas relativas.

Anclas (Internos): Enlazan a un punto específico de la misma página.

Se crea el destino con un ID: <h2 id="contacto">Contacto</h2>

Se crea el enlace usando almohadilla: <a href="#contacto">Ir al pie</a>


Formularios Avanzados (<form>)
Permiten captar datos del usuario. Los atributos principales del contenedor son:

action: URL donde se envían los datos.

method: GET (datos visibles en URL) o POST (datos ocultos, más seguro).

target: _self (abre en la misma pestaña) o _blank (nueva pestaña).

Atributos del <input>:
name: Identificador del dato para el servidor (fundamental).

value: Valor predeterminado.

placeholder: Texto de ayuda grisáceo.

required: Obliga al usuario a rellenar el campo.

readonly / disabled: Bloquean la edición del campo.



Para que tu trabajo no parezca un "copia y pega" de una lista de definiciones, he redactado la información de las tablas de una forma más narrativa y técnica, explicando para qué sirve cada etiqueta y cómo se estructuran jerárquicamente.

Aquí tienes el texto listo para tu documento:

10. Estructura de Datos: Tablas en HTML
Las tablas en HTML se utilizan para organizar información en filas y columnas. Su estructura es jerárquica, lo que significa que unas etiquetas deben contener a otras necesariamente para que la tabla sea válida y accesible.

El contenedor principal: <table>
Es la etiqueta que envuelve toda la estructura. Antiguamente se usaban atributos como border (grosor del borde) o width (ancho), aunque hoy en día lo ideal es controlar estos aspectos mediante CSS.

Organización Semántica (Agrupación)
Para que el navegador y los lectores de pantalla entiendan mejor los datos, dividimos la tabla en tres secciones principales:

<thead> (Encabezado): Se sitúa en la parte superior y agrupa las filas que contienen los títulos de las columnas.

<tbody> (Cuerpo): Es el corazón de la tabla donde reside la información principal. Permite separar el contenido real de los encabezados.

<tfoot> (Pie): Se usa al final de la tabla para mostrar totales, resúmenes o información legal.

Estructura de Filas y Celdas
Dentro de los grupos anteriores, los datos se organizan mediante:

<tr> (Table Row): Define una fila horizontal. Puede llevar atributos de alineación como align (horizontal) o valign (vertical), además de bgcolor para el color de fondo.

<th> (Table Header): Es una celda especial para encabezados. El texto suele aparecer en negrita y centrado por defecto.

<td> (Table Data): Es la celda estándar que contiene los datos de la tabla.

Atributos de Expansión (Gestión de Celdas Complejas)
Para crear tablas donde una celda ocupe más de un espacio, utilizamos dos atributos clave:

colspan: Permite que una celda se expanda horizontalmente a través de varias columnas.

rowspan: Permite que una celda se expanda verticalmente a través de varias filas.

Descripción y Título: <caption>
Esta etiqueta se coloca inmediatamente después de abrir <table>. Su función es proporcionar un título descriptivo o leyenda a la tabla, mejorando la accesibilidad. Se puede alinear respecto a la tabla con el atributo align.




