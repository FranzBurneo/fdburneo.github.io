---
layout: post
title:  "¡Bienvenido a Jekyll!"
date:   2024-06-25 23:23:54 -0500
categories: jekyll actualización
---

Encontrarás este post en tu directorio `_posts`. Adelante y edítalo y reconstruye el sitio para ver tus cambios. Puedes reconstruir el sitio de muchas formas diferentes, pero la más común es ejecutar `jekyll serve`, que inicia un servidor web y regenera automáticamente tu sitio cuando se actualiza un archivo.

Jekyll requiere que los archivos de las entradas del blog se nombren de acuerdo con el siguiente formato:

`AÑO-MES-DÍA-título.MARCADO`

Donde `AÑO` es un número de cuatro dígitos, `MES` y `DÍA` son números de dos dígitos, y `MARCADO` es la extensión de archivo que representa el formato utilizado en el archivo. Después de eso, incluye el front matter necesario. Echa un vistazo a la fuente de este post para tener una idea de cómo funciona.

Jekyll también ofrece un soporte poderoso para fragmentos de código:

{% highlight ruby %}
def saludar(nombre)
  puts "Hola, #{nombre}"
end
saludar('Tom')
#=> imprime 'Hola, Tom' en STDOUT.
{% endhighlight %}

Consulta la [documentación de Jekyll][jekyll-docs] para obtener más información sobre cómo aprovechar al máximo Jekyll. Presenta todos los errores/solicitudes de funciones en el [repositorio de GitHub de Jekyll][jekyll-gh]. Si tienes preguntas, puedes hacerlas en [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
