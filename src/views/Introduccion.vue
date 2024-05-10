<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .fondo-intro.p-5.mn
      .tarjeta.p-5(data-aos="zoom-in" style="background-color: #debefb ").mb-5
        .row.justify-content-center.align-items-center
          .col-lg-3.col-5.mb-lg-0.mb-3: img(src='@/assets/curso/temas/1.svg', alt='')
          .col-lg-9
            p.mb-0 El diseño de interfaces web constituye una faceta crítica del desarrollo tecnológico moderno, actuando como el puente esencial que facilita la interacción entre los usuarios y las aplicaciones basadas en la web. A través de estas interfaces, las aplicaciones ofrecen sus servicios y funcionalidades, operando dentro de un entorno dinámico y accesible mediante navegadores web. #[b Estas plataformas pueden ser accesibles a través de diversas redes, incluyendo LAN (Red de Área Local), WAN (Red de Área Amplia) o la omnipresente Internet, lo que les permite llegar a un público extenso y diverso.]
      .row.justify-content-center.align-items-center.mb-5
        .col-lg-1.col-6.mb-lg-0.mb-3(data-aos="fade-right"): img(src='@/assets/curso/temas/2.svg', alt='')
        .col-lg-11(data-aos="fade-left")
          p.mb-0 En la era digital de hoy, la demanda por interfaces web intuitivas, eficientes y estéticamente agradables está en constante aumento. Las organizaciones y desarrolladores buscan innovar constantemente en este campo para mejorar la experiencia del usuario, reconociendo que una interacción positiva con la interfaz puede ser decisiva para el éxito de una aplicación web. Esta evolución no solo se centra en la estética visual sino también en la funcionalidad, con un enfoque particular en la adaptabilidad y la accesibilidad.
      p Las interfaces modernas están diseñadas para ser fluidas y eficaces en una amplia gama de dispositivos, desde computadoras de escritorio y portátiles hasta tabletas y smartphones, garantizando así una experiencia de usuario coherente y satisfactoria independientemente del medio utilizado. 
      h5.mb-5(style="color: #8722E2 ") El diseño de interfaces web abarca múltiples dimensiones clave para el éxito en el entorno digital actual: 
      .row.justify-content-center.mb-5
        .col-lg-7.mb-lg-0.mb-3(data-aos="fade-right")
          AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--morada")
            .p-2(titulo="Enfoque en usabilidad y estética"): p.mb-0 
            .p-2(titulo="Importancia de la lealtad del usuario"): p.mb-0 En un mercado digital saturado, conseguir la lealtad de los usuarios es un desafío significativo, haciendo que la capacidad de atraer y retener usuarios sea crucial.
            .p-2(titulo="Aplicación de principios fundamentales"): p.mb-0 
            .p-2(titulo="Educación avanzada en diseño"): p.mb-0 
            .p-2(titulo="Dinamismo del campo"): p.mb-0 
            .p-2(titulo="Crecimiento impulsado por la tecnología"): p.mb-0 
        .col-lg-5.col-7(data-aos="fade-left"): img(src='@/assets/curso/temas/3.svg', alt='')
              

    
</template>

<script>
import Prism from 'prismjs'
import 'prismjs/components/prism-python'
import 'prismjs/themes/prism-okaidia.css'
export default {
  name: 'Tema1',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
    window.Prism = window.Prism || {}
    window.Prism.manual = true
    Prism.highlightAll()
  },
  updated() {
    this.$aosRefresh()
    window.Prism = window.Prism || {}
    window.Prism.manual = true
    Prism.highlightAll()
  },
}
</script>
<style lang="sass"></style>
