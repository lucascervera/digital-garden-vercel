---
{"dg-publish":true,"permalink":"/lc-guide/innovacion/curva-de-adopcion-de-las-innovaciones/","noteIcon":""}
---

La Curva de Adopción de Innovaciones es un modelo teórico que describe cómo los nuevos productos, servicios o tecnologías son adoptados por los consumidores y cómo se difunden en una población determinada. El modelo fue propuesto por el sociólogo Everett Rogers en su libro Diffusion of Innovations en 1962.

description:
La curva de adopción de innovaciones se divide en cinco categorías de consumidores.
-   Los innovadores son el primer grupo de consumidores en adoptar una innovación. Representan aproximadamente el 2,5% de la población y son muy entusiastas acerca de las nuevas tecnologías.
-   Los primeros adoptantes son el segundo grupo en adoptar una innovación, representando aproximadamente el 13,5% de la población. Son influenciados por los innovadores y están dispuestos a asumir ciertos riesgos para adoptar una innovación temprana.
-   La mayoría temprana es el tercer grupo en adoptar una innovación, representando aproximadamente el 34% de la población. Son un grupo más conservador que los primeros adoptantes y esperan a ver la evidencia de éxito antes de adoptar una innovación.
-   La mayoría tardía es el cuarto grupo en adoptar una innovación, representando aproximadamente el 34% de la población. Son un grupo escéptico que necesita más tiempo para considerar una innovación antes de adoptarla.
-   Los rezagados son el último grupo en adoptar una innovación, representando aproximadamente el 16% de la población. Son los consumidores más tradicionales y resistentes al cambio.
El modelo de la Curva de Adopción de Innovaciones es útil para los innovadores y los mercadólogos para entender cómo se difunde una innovación y cómo llegar a los diferentes grupos de consumidores en el mercado.
https://upload.wikimedia.org/wikipedia/commons/thumb/d/d3/Technology-Adoption-Lifecycle.png/640px-Technology-Adoption-Lifecycle.png
![[640px-Technology-Adoption-Lifecycle.png\|640px-Technology-Adoption-Lifecycle.png]]

## templater
# [[<%+ tp.file.title %>\|<%+ tp.file.title %>]]
<%+ tp.file.path %>
<%+ tp.frontmatter.summary %>

## handlebars plugin
```handlebars
{{summary}}
```
```handlebars
tags: {{#each frontmatter.tags}}{{.}}, {{/each}}
{{summary}}
```
```handlebars
summary: {{#each frontmatter.summary}}{{.}}, {{/each}}
tags: {{#each frontmatter.tags}}{{.}}, {{/each}}
```


```handlebars
{{#notes 'obsidian'}}  - {{@index}} [[{{name}}]]
{{/notes}}
```

```handlebars
{{#notes 'obsidian'}}  - {{>link path=path rel=../path alias=@index}}
{{/notes}}
```
