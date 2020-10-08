---
layout: post
title:  "Tema de Depor JJ Store"
date:   2020-10-07
excerpt: "<b>Depor JJ Store</b>, es una tienda deportiva, en donde encontrarás lo que necesitas."
project: true
tag:
- jekyll 
- moon
- blog
- about
- theme
comments: true
---

{% capture images %}
    https://www.depasio.com/wp-content/uploads/2019/01/5.jpg
{% endcapture %}
{% include gallery images=images caption="Moon Theme on Small Screen Size" cols=1 %} 
    
<center><b>Depor JJ Store</b>, es una tienda deportiva, en donde encontrarás lo que necesitas.</center>
     
 I'm not a developer or designer. And I don't add footer to show who did this theme. If you like this theme or using it, please give a **star** for motivation, It makes me happy.

<iframe src="https://ghbtns.com/github-btn.html?user=TaylanTatli&repo=Moon&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>    
      
## Installation
* Fork the [Moon repo](https://github.com/TaylanTatli/Moon/fork)
* Edit `_config.yml` file.
* Remove sample posts from `_posts` folder and add yours.
* Edit `index.md` file in `about` folder.
* Change repo name to `YourUserName.github.io`    
     
That's all.

## Preview

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509716/61ac6c8e-01d6-11e6-879f-8308883de790.png
	https://cloud.githubusercontent.com/assets/754514/14509717/61ad05ae-01d6-11e6-85ae-5a817dd8763b.png
	https://cloud.githubusercontent.com/assets/754514/14509714/61a89708-01d6-11e6-8fcd-74b002a060df.png
{% endcapture %}
{% include gallery images=images caption="Screenshots of Moon Theme" cols=3 %}

---

{% capture images %}
	https://cloud.githubusercontent.com/assets/754514/14509718/61b09a20-01d6-11e6-8da1-4202ae4d83cd.png
	https://cloud.githubusercontent.com/assets/754514/14509715/61aa9d00-01d6-11e6-81a6-c6837edf2e84.png
{% endcapture %}
{% include gallery images=images caption="Moon Theme on Small Screen Size" cols=2 %}      
      
See a [live version of Moon](http://taylantatli.github.io/Moon) hosted on GitHub.      

## Site Setup
A quick checklist of the files you’ll want to edit to get up and running.    

### Site Wide Configuration
`_config.yml` is your friend. Open it up and personalize it. Most variables are self explanatory but here's an explanation of each if needed:

#### reading_time

Set true to show reading time for posts. And set `words_per_minute`, default is 200.

#### logo
Your site's logo. It will show on homepage and navigation menu. Also used for twitter meta tags.

#### background
Image for background. If you don't set it, color will be used as a background.

---

## Diseños y contenido

Depor JJ Store Theme usa Jekyll Compress para comprimir la salida html. Pero puede causar errores si usa "linenos" (números de línea). Sugiero no usar números de línea para los códigos, porque no se verá bien con este tema, y Les pueden dar un estilo de acuerdo a sus temas. Si insiste en usar números de línea, simplemente elimine la layout: compresscadena de los diseños. Desactivará la compresión.


### Comments
To show disqus comments for your post add `comments: true` to your post's front matter.

---

## ¿Preguntas?

¿Encontraste un error o no estás seguro de cómo funciona algo? Por todos los medios [archive un problema de GitHub](https://github.com/TaylanTatli/Moon/issues/new). Y si haces algo genial con este tema no dudes en hacerlo saber.

---

## Licencia

Este tema es software libre y de código abierto, distribuido bajo la licencia MIT. Así que siéntase libre de utilizar este tema Jekyll en su sitio sin vincularse de nuevo a mí o incluyendo un descargo de responsabilidad.
