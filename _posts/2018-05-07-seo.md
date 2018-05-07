---
layout: post
title: SEO: Posicionamiento Natural en Buscadores
categories: SEO
image:      img/customer-journey.png
---

## El SEO Local en Google
#### Google My Business
- Para salir en Google Maps:
Cuando vas a crear una ficha en [Google my Business](https://www.google.com/business/) lo que hay que tener en cuenta es que desde el perfil de persona de Google+ crea una ficha de empresa.

## Sitemap

**Para saber si un sitio web web está indexado en Google, realizaremos la siguiente búsqueda:**
- [x] "site:nombredelaweb.com” substituyendo “nombredelaweb.com” por el nombre de dominio del sitio web que deseamos analizar.

**¿Cómo puedo conseguir que Google en menos de dos días lea todo mi sitio Web, lo introduzca en su base de datos y que cuando alguien haga una búsqueda me encuentre entre los resultados?**

-Crear un Sitemap para wordpress utilizando, por ejemplo: un plugin de SEO llamado [Yoast SEO](https://wordpress.org/plugins/wordpress-seo/) o el plugin [Google XML Sitemaps](https://wordpress.org/plugins/google-sitemap-generator/)

-Crear un sitemap para una web usando, por ejemplo: [XML Sitemaps](https://www.xml-sitemaps.com/) o [Online XML sitemap generator](https://xmlsitemapgenerator.org/sitemap-generator.aspx)

1. Indicar el sitio web 
2. Indicar cada cuanto tiempo cambiamos el contenido
3. La úntima modificación: usar la respuesta del servidor
4. Prioridad: calcular automáticamente

Lo que hace es enviar una araña al sitio Web, lee sitio Web, crea el sitemap y crea un documento con ese sitemap. Ese documento se descarga y se guarda en el sitio Web con el nombre del sitemap, subiéndolo a través de FTP.

Una vez está publicado en el sitio Web es el momento de ir a [Google search console](https://www.google.com/webmasters/tools) y darlo de alta. Esperar 48 horas y todo el sitio Web indexado.


## Robots.txt
#### El protocolo de exclusión de robots

Cualquier araña que llegue a tu sitio Web, lo primero que hace es buscar si tienes creada esta página: robots.txt
[Robotstxt.com](http://www.robotstxt.org/) En esta página puedes ver todas las instrucciones que puedes dar a los robots si haces clic donde pone: the /robots.txt

**¿Cómo crear este documento?**
```html
User-Agent: *
Sitemap: https://nombredelaweb.com/sitemap.xml
```

## El algoritmo de Google

La diferencia entre un sitio web publicado siguiendo el protocolo http y el https es que en este último la información viaja entre la pantalla del usuario y el servidor en el que está alojada la web de forma encriptada. Esto asegura que si alguien es capaz de interceptar el flujo de datos, no podrá interpretarlos por qué no podrá entenderlos.

Así que **utilizar el https en lugar del http en una página web se está convirtiendo en una necesidad, no sólo para la protección de tus usuarios, si no porqué mejora el SEO del sitio web**.

#### Instrucciones para pasar una web de http a https

Para empezar, necesitas activar el certificado SSL que te ofrezca el hosting del sitio web. 
Suele ser un servicio gratuito. Si tu hosting no ofrece este servicio, puedes encontrarlo en sitios como [Let’s Encrypt](https://letsencrypt.org/)

Ahora necesitas indicarle a tu web que utilice el certificado que acabas de activar. Si la web está creada con WordPress esto es realmente sencillo. Te descargas el plugin gratuito “Really Simple SSL”, lo instalas y lo activas dándole al botón “activar”. Ya está, todo OK. Si tu web está creada con otro gestor de contenidos, busca el plugin equivalente. Si tu web está hecha a mano, deberás cambiar el fichero .htaccess.


## SEO On Page y Off Page

1. On page: están dentro del sitio Web. 
2. Off page: están fuera de nuestro sitio Web.

#### El SEO *on page*
Las variables que afectan el SEO *on page* son:
- La densidad de las palabras en una página en concreto.
- La densidad de las palabras en todo el sitio web.
- La prominencia de las palabras: hay unas partes del sitio Web que valen más puntos y unas partes del 
sitio Web que valen menos puntos (ver más abajo).
- La estructura del sitio web.
- La velocidad del sitio web.

#### El SEO *off page*
También está formado por unas variables:
- El número de enlaces que apuntan a un sitio Web, de sitios de calidado sea de sitios que transmitan confianza.
- La palabra con la que terceros enlazan a tu sitio web. Google mira el entorno o sea el resto de palabras que forman parte de esa página que nos está enlazando y si no tiene nada que ver el contenido de esta página con nuestro contenido ese enlace también va a valer menos.


## Las palabras clave 
#### La densidad en todo un sitio Web
Ejemplo:
-En cuántas páginas aparece el concepto “recubrimientos industriales”, que es el concepto por el cual quiere posicionarse esta empresa:

**site:nombredelaweb.com espacio y entre comillas el concepto por el que se quiera analizar y ver en cuantas páginas aparece**.

*site:unipinta.es "recubrimientos industriales"*
Resultado: 31 páginas donde aparece el concepto “recubrimientos industriales”
*site:unipinta.es*
Resultado 33 páginas tiene el sitio web

#### La densidad en una página
Por ejemplo, en un artículo el concepto “Magdalenas”, aparece 5 veces, y en el total de esa página hay 300 palabras.
Para calcular la densidad, dividir el total de veces que aparece la palabra “magdalenas” entre el total de palabras que tiene ese artículo en concreto. En este caso, la densidad es del 1,66%. 

**Nota**: Google penaliza a partir de un **15% de densidad**

Google también comprueba la densidad de una frase en el contexto general de un sitio web. Por eso es una buena idea: Crear un pie de página con las frases principales y repetirlo a lo largo de todo el sitio web

#### ¿Qué densidad sería la óptima, tanto en todo el website, como en una página en concreto? 
Eso dependería también en de cómo están actuando a nivel de posicionamiento natural nuestros competidores por esos conceptos clave; si tus competidores tienen una densidad para ese concepto en una página en concreto de un 2%, tú tendrías que lograr llegar a un 3%.

#### Herramienta gratuita para analizar la densidad
Una herramienta gratuita que funciona bastante bien es: [SeoBook](http://www.seobook.com/)
Para calcular la densidad: [Keyword Density](http://tools.seobook.com/general/keyword-density/)

![SEO Book]({{ site.url }}img/seobook.jpg)

## La prominencia de las palabras
Significa que hay algunos apartados de los sitios Web, a los que Google les da más importancia, dándoles lo que se llama “puntos de prominencia”. 

- El dominio:
Aspectos básicos que debes tener en cuenta: preferiblemente que incluya el concepto clave por el que te quieres posicionar, aparte del nombre de marca; y que sea lo más breve posible. 
- La URL *SEO Friendly*
- El título de la página.
- La metaetiqueta <title>
- Las cabeceras o títulos: los headings (H1, H2, H3...):
  El texto que se vaya a utilizar en esos headings, da información importante a Google sobre el contenido que se encuentra en esa página. 
  **Nota**: Se recomienda que todo lo que se ponga como subtítulo dentro del texto, sea a partir de un H2.
- Los  anchor  text, o textos de anclaje enlaces, que son los textos que enlazan hacia otra página:
  Hay que tener en cuenta que tienen que ser descriptivos: [“cursos en marketing digital"](https://www.google.com/search?q=cursos+en+marketing+digital&ie=utf-8&oe=utf-8&client=firefox-b), no ponerlo como: ["clic aquí"](https://es.wikipedia.org/wiki/Wikipedia:No_uses_clic_aqu%C3%AD)
- Breadcrums:
  ¿Por qué ayuda también en el SEO si lo tienes activado en tu sitio Web? Porque son Anchor text, y si haces clic, te lleva a un enlace interno del site.
- Las palabras en negrita.
- Las listas.
- También los textos alternativos: la etiqueta ALT
```html
<img src="image.jpg" alt="Alternate text to describe the image.">
```

#### ¿Cómo sacar el máximo provecho de un pie de página?
El footer es un buen sitio para poner los conceptos por los que te quieres posicionar, porque el footer normalmente se repite en todas las páginas de un sitio Web.

## Creación de buen contenido

[Google lo dice claro](https://support.google.com/webmasters/answer/40349?hl=es)

> Ofrece contenido de alta calidad en tus páginas, sobre todo en la página principal. **Esto es lo más importante.**

#### ¿Qué tipo de contenido consigue que la gente nos linke?
- Listas de herramientas que pueden ser útiles para tus usuarios.
- Los artículos sobre tendencias o sobre innovación en tu sector.
- Las estadísticas sobre ventas y sobre usos de algún producto.
- Publicación de puntos de vista opuestos.
- Las infografías.
- También son excelentes los vídeos de gatos 😹

#### ¿Cómo crear ese contenido?
![Customer Journey]({{ site.url }}img/customer-journey.png)

## Haz tu sitio para móviles
Utilizando un diseño web adaptable (RWD) puedes publicar para ordenadores y para móviles desde la misma URL. **Google recomienda utilizar la configuración de diseño web adaptable**.

## La velocidad del sitio 
Para mejorar la velocidad de un sitio web puedes contratar los servicios de un proveedor de CDN (*Content Delivery Network*), como [CloudFlare](https://www.cloudflare.com/es/cdn/)

### Herramientas para medir la velocidad
- [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
- [WebPageTest](https://www.webpagetest.org/)
- [GTmetrix](https://gtmetrix.com/)
- [Pingdom Website Speed Test](https://tools.pingdom.com/)

A  partir de 3 segundos empieza afectar la penalización de Google por sitio Web lento. 

### Optimizar imágenes
- Comprimir imágenes es una buena manera de reducir la velocidad de carga del sitio web. Las imágenes deben pesar desde 50 KB hasta unos 100 KB aproximadamente.
- Resolución óptima 72ppp para que se visualice correctamente a través de Web. Para reducir la resolución se pueden utilizar 
un programa gratuito como [Gimp](https://www.gimp.org/).
- Para una imagen muy grande sería máximo unos 1.400 píxeles de ancho.
- El texto alternativo "alt" de la etiqueta <img> puede ser el mismo que el nombre de la imagen, se utiliza para la accesibilidad web.
- El nombre de los archivos debe ser representativo de lo que muestra la imagen, por ejemplo: "robot-dog.jpg"
<img alt="robot dog" style="border-width:0" src="https://gilfinart.com/img/robot-dog.jpg">


#### Herramientas para optimizar las imágenes
- [TinyPNG](https://tinypng.com/)
- [Optimizilla](http://optimizilla.com/es/)
- Para WordPress: [Smush Image Compression and Optimization](https://wordpress.org/plugins/wp-smushit/)

### Gzip
Aplicando la compresión gzip consigues reducir el tamaño de ciertos tipos de archivos antes de ser enviados al navegador, reduciendo considerablemente los tiempos de carga de tu sitio.
[Habilitar compresión gzip](https://varvy.com/pagespeed/enable-compression.html)


### Almacenamiento en caché del navegador
Cuando un navegador web muestra tu página web, tiene que cargar varias cosas como el logotipo, archivo CSS y otros recursos. Lo que hace el caché del navegador es "recordar" los recursos que el navegador ya ha cargado.
[Aprovecha el almacenamiento en caché del navegador](https://varvy.com/pagespeed/leverage-browser-caching.html)

## Link Building
- Foros:
  Crear links en un foro relacionado con la temática de tu web.
- Redes sociales: 
  Google+, Pinterest
- Blog
  
- Si deseas que Google no tenga en cuenta un enlace que te está perjudicando, en Google Search Console existe un servicio que permite solicitar que un enlace no sea tenido en cuenta. En este enlace encontrarás dónde indicar a Google que no tenga en cuenta un enlace.

### Herramientas
[Majestic](https://majestic.com/)
- Es una herramienta que te servirá para poder asignar un valor numérico a la importancia de tu sitio Web.
- En un sitio web, debes conseguir como mínimo un “Trust flow” de 25.

[Nofollow](http://www.igorware.com/extensions/nofollow-simple)
- Extensión para Chrome o Firefox que permite detectar en qué sitios web no está funcionando el link building, porque tiene incluido en la programación un no follow que impide a las arañas seguir el enlace.
- Al usar esta extensión, se ve un cuadrado de puntitos rojos que sale alrededor de los links del sitio web que estas visitando, esto quiere decir que a essos enlaces no los siguen las arañas.

## SEO y Buscadores de Teléfonos Móviles

### Optimización para móviles
**Google penaliza** aquellos sitios Web que no estaban optimizados para móvil. 
[¿Tu página web está optimizada para móviles?](https://search.google.com/test/mobile-friendly?hl=ES)

### Ventanas emergentes
**Google penaliza** las websites que no permiten al usuario ver el contenido indexado en el momento en el que se entra en el sitio (no hay penalización si la pop-up aparece un rato después de estar navegando). Esta penalización afecta a los sitios webs que por ejemplo, muestran una ventana emergente invitando a la suscripción de su boletín justo al entrar en el sitio web, impidiendo que el usuario pueda ver el contenido si no cierra la ventana. 
Las ventanas emergentes que muestran el aviso del uso de cookies no penalizan.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png"></a>


Recursos: 
- [SEO: posicionamiento natural en buscadores (3.ª edición)](https://miriadax.net/web/seo-posicionamiento-natural-en-buscadores-3-edicion-/inicio) 
- ["A Practical Guide to Search Engine Optimization (SEO) with Google"](https://www.taniarascia.com/a-practical-guide-to-search-engine-optimization-seo-with-google/)

[![Kittens meowing](https://i.imgur.com/MVNkeIY.png)](https://www.youtube.com/watch?v=BgIgKcqPd4k)
