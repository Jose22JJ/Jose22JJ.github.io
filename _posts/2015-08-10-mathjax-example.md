---
layout: post
title:  "Materiales de baloncesto"
date:   2020-10-07
excerpt: "El baloncesto es un deporte que ha alcanzado un gran desarrollo y popularidad en todo el planeta, siendo actualmente una de las prácticas deportivas más influyentes y relevantes a nivel global."
tag:
- markdown 
- mathjax
- example
- test
- jekyll
comments: true
---

Todo entrenador de baloncesto quiere sacar lo máximo de sus jugadores a lo largo de la temporada y para ello tiene que preparar hasta el más mínimo detalle. Pero sin duda, una de las cosas más importantes es tener unas instalaciones adecuadas y un material de entrenamiento de baloncesto en perfecto estado que permita realizar rutinas de ejercicios para potenciar las condiciones físicas de los jugadores.

![Entrenamiento de Baloncesto](https://www.mundosilbato.es/media/wysiwyg/blog6/entrenamiento-baloncesto.jpg)

## Usage

To enable MathJax support be sure Kramdown is your Markdown flavor of choice and MathJax is set to true in your `_config.yml` file.

~~~
markdown: kramdown
mathjax: true
~~~

~~~
Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]
~~~

Here is an example MathJax inline rendering \\( 1/x^{2} \\), and here is a block rendering: 
\\[ \frac{1}{n^{2}} \\]

The only thing to look out for is the escaping of the backslash when using markdown, so the delimiters become `\\[ ... \\]` and `\\( ... \\)` for inline and block maths respectively.
    

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$
