<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Presentación

    .titulo-segundo.color-acento-contenido
      h2#t_1_1 1.1 Definición

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade-down")
      .col-12.col-md-5.mb-2
        img(src='@/assets/curso/temas/1.png', alt='')
      .col-12.col-md-7
        p La presentación es una técnica de enseñanza muy utilizada en la actualidad. Se adecua para preparar a los estudiantes al asumir los retos y roles en un mundo cambiante de características tecnológicas. Cuando se aplica de manera apropiada, con contenido adecuado y en combinación con otras técnicas o estrategias didácticas, puede contribuir enormemente a un proceso de enseñanza-aprendizaje efectivo. 
        p.mb-0 Las presentaciones se componen de diapositivas que pueden contener texto, gráficos, videos e imágenes explicando alguna temática particular. Las diapositivas pueden tener transiciones, que son efectos agregados para mejorar la diapositiva y proporcionar diferentes estilos de visualización. 

    separador 
    .titulo-segundo.color-acento-contenido
      h2#t_1_2 1.2 Elementos que componen la presentación

    .row 
      
      .col-lg-8.col-12
        ol.lista-ol--cuadro
          li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>1</b>
            | #[b Título:] resume la información visual y textual del tema. Debe ser breve y conciso. 
          li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>2</b>
            | #[b Introducción:] debe orientar a la audiencia hacia el tema y propósito. Para captar el interés y establecer una relación.  
          li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>3</b>
            | #[b Cuerpo:]  es la parte principal y más extensa, en la que se explica un tema a la audiencia y contiene un mensaje contundente. 
          li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>4</b>
            | #[b Conclusiones:] en este espacio se resume los puntos claves que se plantearon o destacaron, y que la audiencia debería haber aprendido. Aclarar el propósito general de la presentación y refuerza la razón para verla. 
          li 
            .lista-ol--cuadro__vineta
              span(style="color: #12263F") <b>5</b>
            | #[b Referentes bibliográficos:] colocar las fuentes consultadas para la presentación bajo la norma APA 7ª edición.
      .col-lg-4.col-12
        figure(data-aos="zoom-in")
        img(src="@/assets/curso/temas/2.svg", alt="alt")

    separador 
    .titulo-segundo.color-acento-contenido
      h2#t_1_3 1.3 Pasos para elaborar una presentación

    .tarjeta.tarjeta--gris.p-4
      PasosB.color-acento-contenido
        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/3.svg', alt='Texto que describa la imagen')
          
          .col-md-10.mb-4.mb-md-0
            h4 Seleccione una plantilla
            p Se debe elegir la herramienta y la plantilla en donde se va a realizar la presentación, y que se adecue al proyecto.

        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/4.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 Coloque el título de la presentación
            p Hay que centrarse en el tema principal. 
            
        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/5.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 Introducción
            p Es una parte crucial de una presentación efectiva. Es importante captar la atención del público y establecer el propósito de la presentación, se debe tener en cuenta la importancia del tema, definir el punto central, y realizar una visión general. 

        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/6.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 Selecciones el texto y las imágenes a incluir
            p Es importante organizar la información en un orden lógico y luego proporcionar la información para respaldar cada punto. Además, es fundamental que la información visual tenga coherencia con la información escrita. Una forma de lograr esto es combinar el uso de iconos e ilustraciones, pero sin saturar la presentación. 

        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/7.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 Equilibrio visual
            p Es importante tener en cuenta las proporciones y dimensiones de tal forma que el contenido sea fácil y agradable de leer. Para ello, es fundamental elegir el tipo y tamaño de letra más adecuado, teniendo en cuenta el público potencial, el color y la resolución. 

        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/8.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 Espacios
            p Es importante tener en cuenta los espacios y las márgenes para garantizar la correcta legibilidad de los textos. Los espacios son necesarios para que la función comunicativa de la presentación no pierda fuerza. 

        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/9.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 El cuerpo y conclusiones
            p El cuerpo de la presentación debe ser claro y fácil de seguir para que la audiencia pueda comprender el mensaje que se está transmitiendo. Por otro lado, la conclusión debe ser breve y concisa, y debe dejar una impresión duradera en la audiencia. 

        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/10.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 Referentes bibliográficos
            p En la diapositiva final, se deben incluir las fuentes consultadas para la presentación, se deben aplicar las normas APA 7ª edición. 

        .row(titulo="")
          .col-md-2
            figure
              img(src='@/assets/curso/temas/11.svg', alt='Texto que describa la imagen')
          .col-md-10.mb-4.mb-md-0
            h4 Redacción y ortografía
            p Por último, revisar la ortografía y redacción de la presentación.  

    separador 
    .titulo-segundo.color-acento-contenido
      h2#t_1_4 1.4 Recomendaciones para desarrollar una presentación 

    .tarjeta--container.row.mb-5
      .col-md.tarjeta(style="background-color:#CDF5E2").p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/12.svg', alt='Texto que describa la imagen')
          
        p Utilizar formatos ligeros o contenidos que faciliten la descarga y/o desarrollo. 

      .col-md.tarjeta(style="background-color:#FAFFD7").p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/13.svg', alt='Texto que describa la imagen')
          
        p Utilizar imágenes de buena calidad que refuercen y complementen el mensaje. 

      .col-md.tarjeta(style="background-color:#CDF5E2").p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/14.svg', alt='Texto que describa la imagen')

        p Evitar el uso de transiciones llamativas. 

      .col-md.tarjeta(style="background-color:#FAFFD7").p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/15.svg', alt='Texto que describa la imagen')

        p Evitar diapositivas con mucho texto. 

    separador 
    .titulo-segundo.color-acento-contenido
      h2#t_1_5 1.5 Herramientas digitales que se pueden utilizar para la elaboración de presentaciones.
    
    LineaTiempoD.color-acento-botones
      .row(numero="1" titulo="Power Point").justify-content-center
        .col-12
          p  Es de uno de los programas más populares creados por Microsoft. Se trata de un software que permite realizar presentaciones a través de diapositivas.  
      
        .col-12.mb-3
          figure
            img(src='@/assets/curso/temas/16.jpg', alt='Texto que describa la imagen')

      .row(numero="2" titulo=" Prezi").justify-content-center
        .col-12
          p  Se ha convertido en un pionero en el proceso de creación de presentaciones en línea.
      
        .col-12.mb-3
          figure
            img(src='@/assets/curso/temas/17.jpg', alt='Texto que describa la imagen')

        .col-2
          a.boton.color-acento-botones.me-3(href="https://prezi.com/es/" target="_blank" type="web")
            span Enlace web
            i.fas.fa-file-download

      .row(numero="3" titulo="Visme").justify-content-center
        .col-12
          p  Es una herramienta de presentación online basada en la nube que le permite crear presentaciones muy visuales para atraer a los espectadores y comunicar sus ideas.
      
        .col-12.mb-3
          figure
            img(src='@/assets/curso/temas/18.jpg', alt='Texto que describa la imagen')

        .col-2
          a.boton.color-acento-botones.me-3(href="https://www.visme.co/ " target="_blank" type="web")
            span Enlace web
            i.fas.fa-file-download

      .row(numero="4" titulo="Canva").justify-content-center
        .col-12
          p  Es una plataforma en línea que proporciona plantillas para una amplia gama de publicaciones. Hay cientos de diseños y plantillas para empezar, y se pueden subir imágenes propias o elegir del archivo de Canva
      
        .col-12.mb-3
          figure
            img(src='@/assets/curso/temas/19.jpg', alt='Texto que describa la imagen')

        .col-2
          a.boton.color-acento-botones.me-3(href="https://www.canva.com/ " target="_blank" type="web")
            span Enlace web
            i.fas.fa-file-download

      .row(numero="5" titulo="Powtoon").justify-content-center
        .col-12
          p  Es una plataforma donde se pueden crear presentaciones animadas, y es fácil de manejar.
      
        .col-12.mb-3
          figure
            img(src='@/assets/curso/temas/20.jpg', alt='Texto que describa la imagen')

        .col-2
          a.boton.color-acento-botones.me-3(href=" https://www.powtoon.com/" target="_blank" type="web")
            span Enlace web
            i.fas.fa-file-download

      .row(numero="6" titulo="Genially").justify-content-center
        .col-12
          p  Es una plataforma donde se pueden crear contenidos multimedia de manera sencilla y cuenta con plantillas gratuitas, permite insertar imágenes propias o externas, textos, audios.
      
        .col-12.mb-3
          figure
            img(src='@/assets/curso/temas/21.jpg', alt='Texto que describa la imagen')

        .col-2
          a.boton.color-acento-botones.me-3(href="https://www.genial.ly/es" target="_blank" type="web")
            span Enlace web
            i.fas.fa-file-download

    separador 
    .titulo-segundo.color-acento-contenido
      h2#t_1_6 1.6 Ejemplo de una presentación

    .row.justify-content-center.align-items-center.mb-5
      .col-10.desktop(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Ejemplo presentación en Power Point</em>
        figure
          img.mb-3(src='@/assets/curso/temas/22.jpg', alt='La imagen muestra diferentes diseños de presentaciones de diapositivas en el programa Power Point.')

    .row.justify-content-center.align-items-center.mb-5
      .col-10.movil(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 #[b Figura 1.] <em>Ejemplo presentación en Power Point</em>
        figure
          img.mb-3(src='@/assets/curso/temas/22-m.jpg', alt='La imagen muestra diferentes diseños de presentaciones de diapositivas en el programa Power Point.')

</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
