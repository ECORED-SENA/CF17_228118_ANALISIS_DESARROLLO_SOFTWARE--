<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 JavaScript 
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-1.col-5(data-aos="fade-right").mb-lg-0.mb-3: img(src='@/assets/curso/temas/33.svg', alt='')
      .col-lg-11(data-aos="fade-left")
        p.mb-0 #[b JavaScript] es un lenguaje de programación que se integra en páginas web y es interpretado por los navegadores. La característica de ser “interpretado” se refiere a que el código se ejecuta de manera secuencial, línea por línea, por el intérprete del navegador, primordialmente en el lado cliente. Sin embargo, con el desarrollo de tecnologías como Node.js, JavaScript también se puede ejecutar en el lado del servidor, a diferencia de otros lenguajes de programación que requieren compilación. 
    .row.justify-content-center.mb-5
      .col-lg-10
        .tarjeta.color-primario.p-5
          .row.justify-content-center.align-items-center
            .col-lg-2.col-6: img(src='@/assets/curso/temas/34.svg', alt='')
            .col-lg-10
              p Este lenguaje está especialmente diseñado para permitir la creación de contenido HTML de forma dinámica. Esto significa que los programas escritos en #[span.color-azul JavaScript] pueden generar y manipular etiquetas HTML automáticamente, enriqueciendo significativamente el diseño de las interfaces web.
    p.mb-5(data-aos='fade-right') Es crucial distinguir entre #[b JavaScript y Java], ya que, a pesar de la similitud en sus nombres, son lenguajes de programación completamente diferentes. Esto puede llevar a confusiones entre quienes no están familiarizados con ellos. #[b Para integrar código JavaScript en una página web, existen varias maneras, entre ellas:]
    .row.justify-content-center.mb-5
      .col-lg-7(data-aos="fade-right").mb-lg-0.mb-3
        .tarjeta(style="background-color: #f2e5fd ").p-4
          ul.lista-ul--color
            li
              i.fas.fa-circle.fa-xs(style="color:#8722E2 ")
              | Con código que se agrega dentro de la misma página. 

            li
              i.fas.fa-circle.fa-xs(style="color:#8722E2 ")
              | Con archivos independientes que se almacenan en rutas diferentes a la página. 

            li
              i.fas.fa-circle.fa-xs(style="color:#8722E2 ")
              | Con código referenciado en otras páginas web ya publicadas en la red internet. 
      .col-lg-5(data-aos="fade-left"): img(src='@/assets/curso/temas/35.svg', alt='')
    p.mb-5(data-aos='fade-right') Explorando la integración de #[b JavaScript] en la web, esta guía visual proporciona ejemplos claros y concisos de cómo insertar código JavaScript directamente en el HTML, así como cómo incluirlo desde archivos externos, y los resultados esperados de dicha implementación. 
    .f-3-1.mn.p-5.mb-5
      .tarjeta.bg-white.p-5
        SlyderA(tipo='b')
          .row
            .col-lg-6.mb-4.mb-md-0
              h4: span.color-morado Código interno 
              p Aquí se incluye el código dentro del tag &lt;script&gt;&lt;/script&gt; después del tag &lt;title&gt;. Ejemplo de código interno: 
            .col-lg-6
              .tarjeta-codigo.p-5.mb-5
                pre.language-html(language="html").mt-5
                  code
                    | &lt;html&gt; 
                    | &lt;head&gt; 
                    | &lt;title&gt; 
                    | Página web con código JavaScript embebido 
                    | &lt;/title&gt; 
                    | &lt;script type=”text/javascript”&gt; insertar tag con atributo type indicando el uso del lenguaje java JavaScript alert(“Mi primer mensaje usando JavaScript”);    
                    | &lt;/script&gt;  
                    | &lt;/head&gt; 
                    | &lt;body&gt;  
                    | &lt;p&gt;Contenido de la página web&lt;/p&gt; 
                    | &lt;/body&gt; 
                    | &lt;/html&gt; 
          .row
            .col-lg-6.mb-4.mb-md-0
              h4: span.color-morado 
              p 
            .col-lg-6
              .tarjeta-codigo.p-5.mb-5
                pre.language-html(language="html").mt-5
                  code
                    |
          .row
            .col-lg-6.mb-4.mb-md-0
              h4: span.color-morado 
              p 
            .col-lg-6
              .tarjeta-codigo.p-5.mb-5
                pre.language-html(language="html").mt-5
                  code
                    |
          .row
            .col-lg-6.mb-4.mb-md-0
              h4: span.color-morado 
              p 
            .col-lg-6
              .tarjeta-codigo.p-5.mb-5
                pre.language-html(language="html").mt-5
                  code
                    |

</template>

<script>
import 'prismjs'
import 'prismjs/themes/prism-tomorrow.min.css'
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
