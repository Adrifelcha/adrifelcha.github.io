# Lab25 Official website

Welcome to the Lab25 webpage; Click on it!

https://bouzaslab25.github.io/




--------
Para facilitar la administración del sitio, les dejo instrucciones más precisas:

**CARPETAS ESENCIALES**  
**1.- "_layouts"_**
Esta es la carpeta donde se vacían los "templates" o el diseño general de la página. Básicamente, por cada ventana que añadimos a la página no es necesario que especifiquemos todo el environment, basta con que llamemos el layout correspondiente y nos concentremos en únicamente especificar el contenido a imprimir en el espacio {{content}}.      
**2.- css**  
Contiene el _Cascading Style Sheet_ donde se detallan las características de los objetos a crear a lo largo de la página. El archivo "main.css" es llamado como referente principal a lo largo de los distintos layouts creados. Recuerden que para hacer una especificación distinta a la contenida en el css, pueden hacerlo al interior de <style></style> en el archivo layout que estén editando.  

**CARPETAS FUNCIONALES**  
**3.- "events"**  
Esta carpeta contiene un único archivo "index.html" que contiene el código necesario para mantener nuestro blog funcionando. **Se recomienda NO modificarlo en lo absoluto**, ya que lo único que hace es indicar cómo deben leerse las entradas que se vayan haciendo al blog para irlas incorporando al sitio.  
4.- "_posts"_  
Esta carpeta contiene un archivo por cada entrada publicada en el blog. Es importante notar que estos archivos están **escritos en markdown (.md)**, por lo que el contenido se ve diferente. **Es importante que las nuevas entradas que se generen, se guarden con el mismo formato de título** para que puedan leerse, de acuerdo a lo especificado en la carpeta events.  
**5.- "_site"_**  
Esta carpeta contiene una copia del sitio, de cuando se intentaba configurar por primera vez. **Recomiendo que la ignoremos**  

CARPETAS DE CLASIFICACION  
A) Almacenamiento de archivos  
1.- LabPictures  
Fotos de eventos importantes, a imprimir como parte de las entradas del blog  
2.- Documents  
Documentos varios (CSV, capítulos, etc) a referir a lo largo de la página (por ejemplo, en sus perfiles, etc.)  
3.- Presentations  
Posters y presentaciones utilizadas durante nuestras participaciones en congresos (en formato pdf)  
4.- Images  
Fotografías a usar en el perfil de cada miembro del Lab. **Es importante cuidar el tamaño de las fotos, para que no sean demasiado grandes. Siempre es cosa de hacer pruebas**

B) Segmentando el sitio web  
1.- Posts  
Como ya se mencionó, contiene un archivo .md por cada entrada a agregar al blog.  
2.- About  
Contiene el archivo "index.html" a imprimirse cuando alguien hace click en la ventana "About" desde el menú principal.  
3.- People  
Contiene dos tipos de archivos : **1)** Un archivo .html para cada miembro del Lab, utilizando el Layout "Perfil" para imprimir la información de cada uno de nosotros (Cargando la fotografía correspondiente de la carpeta Images y los CSV y otros archivos adjuntos de Documents) **2)** Los archivos para navegar a través de los perfiles. El primero de ellos es "index.html" que es el que se muestra por default al ir al Menú "Miembros", lo único que hace es imprimir en una cuadrícula de 3 columnas, las fotografías de cada uno de los miembros del lab y el enlace a su propio perfil; Los archivos "collaborators.html" y "alumni.html" cumplen funciones similares, pero corresponden al menú que se despliega cuando clickeamos en el submenú correspondiente.
4.- Publications  
Contiene el archivo "index.html" a imprimirse cuando alguien hace click en la ventana "Publicaciones" desde el menú principal. Es sólamente una lista, con títulos y bullets, de todos los productos del Lab.


 


**Las carpetas que se recomienda _no_ cambiar, a menos que quieran hacer cambios de estructura en la página, están marcadas en negritas**

-Para cualquier duda adicional, no duden en contactarnos:
adrifelcha@gmail.com; villaele14@gmail.com

¡Saludos por siempre!
- Elena y Adriana
