<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Ejecución de un proyecto deportivo 
    p.mb-5 Es en esta fase se llevan a cabo los planes del proyecto, se ejecutan las actividades o una fase determinada según ha sido planificada, de modo que se generen los entregables definidos en el alcance. Para que se cumpla todo lo establecido en el plan es importante asignar responsables, sus respectivas responsabilidades y velar por su cumplimiento conforme a lo estipulado en el plan. 
      br
      br
      |Para garantizar la ejecución del proyecto, el gestor deportivo deberá tener en cuenta tres aspectos importantes:
    .row.mb-5
      .col-lg-4.mb-4
        .tarjeta.tarjeta-rotate.color-acento-botones--borde.p-4.bg-gray.h-100
          .img-rotate.mb-4
            .img-rotate__img: img(src='@/assets/curso/0.svg', alt='Texto que describa la imagen' style='width: 115px')
            .img-rotate__img: img(src='@/assets/curso/1.svg', alt='Texto que describa la imagen' style='width: 115px')
          p 
            b Dirigir a los miembros del equipo 
            | para que las actividades se cumplan según lo establecido en el plan.
      .col-lg-4.mb-4
        .tarjeta.tarjeta-rotate.color-primario--borde.p-4.bg-gray.h-100
          .img-rotate.mb-4
            .img-rotate__img: img(src='@/assets/curso/2.svg', alt='Texto que describa la imagen' style='width: 115px')
            .img-rotate__img: img(src='@/assets/curso/3.svg', alt='Texto que describa la imagen' style='width: 115px')

          p 
            b Asegurar que se recopile la información 
            | necesaria para el diseño de los informes de progreso del proyecto
      .col-lg-4.mb-4
        .tarjeta.tarjeta-rotate.color-acento-botones--borde.p-4.bg-gray.h-100
          .img-rotate.mb-4
            .img-rotate__img: img(src='@/assets/curso/4.svg', alt='Texto que describa la imagen' style='width: 115px')
            .img-rotate__img: img(src='@/assets/curso/5.svg', alt='Texto que describa la imagen' style='width: 115px')

          p 
            b Evaluar el rendimiento 
            | del equipo de trabajo.
    p.mb-5 A continuación, se describen los principales productos esperados en la fase de ejecución del proyecto:
    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-acento-botones.p-5.text-white
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/6.svg', alt='Texto que describa la imagen')
          
        h4.text-center Entregables
        p.text-center Informes, artefactos, construcciones, etc.

      .col-md.tarjeta.color-primario.p-5.text-white
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/7.svg', alt='Texto que describa la imagen')
          
        h4.text-center Peticiones de cambio  
        p.text-center Posibles cambios en el alcance del proyecto.
      .col-md.tarjeta.color-acento-contenido.texto-oscuro.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/8.svg', alt='Texto que describa la imagen')
          
        h4.text-center.texto-oscuro Informes
        p.text-center.texto-oscuro Resumen de los resultados y ejecución del proyecto. 
      .col-md.tarjeta.color-acento-botones.p-5.text-white
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/9.svg', alt='Texto que describa la imagen')
          
        h4.text-center Evaluación y estimulación del rendimiento del equipo 
        p.text-center Formación, recompensas, reconocimientos.
      .col-md.tarjeta.color-primario.p-5.text-white
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/10.svg', alt='Texto que describa la imagen')
          
        h4.text-center Contratos
        p.text-center Administración de contratos, selección de proveedores.
    #t_1_1.titulo-segundo(data-aos="fade-right")
      h2 1.1 Gestión de comunicaciones
    p.mb-5 La gestión de las comunicaciones según la PMBOK (2003) incluye los procesos necesarios para garantizar la adecuada y oportuna recopilación, distribución, almacenamiento, recuperación y disposición final de la información del proyecto. En este sentido, la comunicación eficaz permite un puente entre las diferentes partes interesadas en el proyecto. Además, suministrar la información a la persona requerida en el momento oportuno, empleando el medio, formato y técnica más apropiada, es lo más acertado para establecer una adecuada apropiación de los procesos al interior de un proyecto. 
      br
      br
      |Por lo anterior, este componente es de gran importancia, ya que de nada sirve tener una correcta planificación en un proyecto, sino se establecen canales ágiles de comunicación que permitan un trabajo sincronizado y coordinado. Por ello, en la gestión de comunicaciones del proyecto es importante tener en cuenta:
    .row.mb-5
      .col-lg-3.mb-3
        .tarjeta-slide-up.bg-gray.h-100
          .tarjeta-slide-up__content.text-center.p-4
            img(src='@/assets/curso/11.svg', alt='Texto que describa la imagen' style='width: 125px').m-auto.mb-3
            p Qué información requiere.
          .tarjeta-slide-up__up.bg--1.text-center.p-4
            img(src='@/assets/curso/13.svg', alt='Texto que describa la imagen' style='width: 163px').m-auto.mb-3
            p.text-white Qué información requiere
      .col-lg-3.mb-3
        .tarjeta-slide-up.bg-gray.h-100
          .tarjeta-slide-up__content.text-center.p-4
            img(src='@/assets/curso/11.svg', alt='Texto que describa la imagen' style='width: 125px').m-auto.mb-3
            p Cuándo la necesita.
          .tarjeta-slide-up__up.bg--4.text-center.p-4
            img(src='@/assets/curso/12.svg', alt='Texto que describa la imagen' style='width: 163px').m-auto.mb-3
            p.text-white Cuándo la necesita.
      .col-lg-3.mb-3
        .tarjeta-slide-up.bg-gray.h-100
          .tarjeta-slide-up__content.text-center.p-4
            img(src='@/assets/curso/11.svg', alt='Texto que describa la imagen' style='width: 125px').m-auto.mb-3
            p Quién necesita la información. 
          .tarjeta-slide-up__up.bg--1.text-center.p-4
            img(src='@/assets/curso/13.svg', alt='Texto que describa la imagen' style='width: 163px').m-auto.mb-3
            p.text-white Quién necesita la información.
      .col-lg-3.mb-3
        .tarjeta-slide-up.bg-gray.h-100
          .tarjeta-slide-up__content.text-center.p-4
            img(src='@/assets/curso/11.svg', alt='Texto que describa la imagen' style='width: 125px').m-auto.mb-3
            p Cómo se debe presentar la información. 
          .tarjeta-slide-up__up.bg--4.text-center.p-4
            img(src='@/assets/curso/12.svg', alt='Texto que describa la imagen' style='width: 163px').m-auto.mb-3
            p.text-white Cómo se debe presentar la información. 
    p.mb-5 La comunicación debe ser siempre clara, sin ambigüedades permitiendo el intercambio fluido de información. Para ello, existen diferentes tipos de comunicación que se pueden emplear en un proyecto, a saber:
    BotonesC.mb-5
    p.mb-5 Según las particularidades de cada proyecto, se define el plan de comunicaciónes que se llevará a cabo, que puede ser:
    .row.mb-5
      .col-lg-4.mb-5
        .tarjeta-icono.bg--1.d-flex.align-items-center.px-5.py-4.h-100
          .tarjeta-icono__icono: img(src='@/assets/curso/15.svg', alt='Texto que describa la imagen' style='width: 102px')
          .tarjeta-icono__texto
              h5.text-white.my-2 Informes de gestión
      .col-lg-4.mb-5
        .tarjeta-icono.bg--4.d-flex.align-items-center.px-5.py-4.h-100
          .tarjeta-icono__icono: img(src='@/assets/curso/17.svg', alt='Texto que describa la imagen' style='width: 102px')
          .tarjeta-icono__texto
              h5.text-white.my-2 Correos electrónicos
      .col-lg-4.mb-5
        .tarjeta-icono.bg--1.d-flex.align-items-center.px-5.py-4.h-100
          .tarjeta-icono__icono: img(src='@/assets/curso/18.svg', alt='Texto que describa la imagen' style='width: 102px')
          .tarjeta-icono__texto
              h5.text-white.my-2 Reuniones presenciales o virtuales tipo videoconferencias
    .row.mb-5.justify-content-center
      .col-lg-4.mb-5
        .tarjeta-icono.bg--1.d-flex.align-items-center.px-5.py-4.h-100
          .tarjeta-icono__icono: img(src='@/assets/curso/19.svg', alt='Texto que describa la imagen' style='width: 102px')
          .tarjeta-icono__texto
              h5.text-white.my-2 Llamadas telefónicas
      .col-lg-4.mb-5
        .tarjeta-icono.bg--4.d-flex.align-items-center.px-5.py-4.h-100
          .tarjeta-icono__icono: img(src='@/assets/curso/20.svg', alt='Texto que describa la imagen' style='width: 102px')
          .tarjeta-icono__texto
              h5.text-white.my-2 Redes sociales virtuales
    p.mb-5 En la ejecución del proyecto, una adecuada gestión de la comunicación permitirá velar por un óptimo cumplimiento del plan y cronograma de trabajo de las distintas partes que componen el proyecto.    
    #t_1_2.titulo-segundo(data-aos='fade-right')
      h2 1.2 Gestión de conflictos
    .row.mb-5.align-items-center
      .col-lg-6(data-aos='fade-right') 
        p Es inevitable que los conflictos se presenten durante todas las fases del proyecto debido a multiplicidad de factores, pueden ser por la gestión del mismo, como por la relación de las personas que intervienen. Sin duda, en el momento de ejecutar el proyecto es donde surge una necesidad más marcada en el trabajo en equipo, por lo que surgen imprevistos, diferentes puntos de vista para abordar un tema o resolver una situación, y esto hace que se presenten los conflictos.
          br
          br
          | Es de gran importancia identificar por qué se generan los conflictos y qué efectos causan, pero más importante es entender que no es cuestión de tratar de eliminarlos, o peor, ignorarlos, sino que es cuestión de gestionarlos y aprender de ellos. En este sentido, los conflictos deben percibirse como algo natural y valorarse como una oportunidad para el autocrecimiento organizacional, ya que los conflictos surgen cuando una de las partes en litigio o disputa percibe que la otra parte le ha afectado o perjudicado sus intereses. 
      .col-lg-6(data-aos='fade-left')
        img(src='@/assets/curso/21.jpg', alt='Texto que describa la imagen' style='width: 100%') 
    .row
      .col-lg-4.mb-3
        .tarjeta.tarjeta-slide-up2.color-primario--borde.overflow-hidden.bg-gray(style="height: 300px")(@mouseover="mostrarIndicador = false")
          .indicador--hover(v-if="mostrarIndicador")
          .tarjeta-slide-up__up: img(src='@/assets/curso/22.jpg', alt='Texto que describa la imagen' style='width:100%')
          .tarjeta__texto.p-5.m-auto.d-flex.align-self-center
            h3.text-center.m-auto Ganar a toda costa sin importar lo que pase. 
          .tarjeta__titulo.bg--1.d-flex.align-self-end.aling-items-center.justify-content-center.p-2
            h4.text-center.text-white.m-auto Competencia
      .col-lg-4.mb-3
        .tarjeta.tarjeta-slide-up2.color-primario--borde.overflow-hidden.bg-gray(style="height: 300px")
          .tarjeta-slide-up__up: img(src='@/assets/curso/23.jpg', alt='Texto que describa la imagen' style='width:100%')
          .tarjeta__texto.p-5.m-auto.d-flex.align-self-center
            h3.text-center.m-auto Ayuda entre las partes para satisfacción mutua. 
          .tarjeta__titulo.bg--1.d-flex.align-self-end.aling-items-center.justify-content-center.p-2
            h4.text-center.text-white.m-auto Colaboración
      .col-lg-4.mb-3
        .tarjeta.tarjeta-slide-up2.color-primario--borde.overflow-hidden.bg-gray(style="height: 300px")
          .tarjeta-slide-up__up: img(src='@/assets/curso/24.jpg', alt='Texto que describa la imagen' style='width:100%')
          .tarjeta__texto.p-5.m-auto.d-flex.align-self-center
            h3.text-center.m-auto Se trata de evitar el conflicto a toda costa o se retira cuando se presenta
          .tarjeta__titulo.bg--1.d-flex.align-self-end.aling-items-center.justify-content-center.p-2
            h4.text-center.text-white.m-auto Evasión
    .row.mb-5.justify-content-center
      .col-lg-4.mb-3
        .tarjeta.tarjeta-slide-up2.color-primario--borde.overflow-hidden.bg-gray(style="height: 300px")
          .tarjeta-slide-up__up: img(src='@/assets/curso/25.jpg', alt='Texto que describa la imagen' style='width:100%')
          .tarjeta__texto.p-5.m-auto.d-flex.align-self-center
            h3.text-center.m-auto Adaptación y aceptación de las demandas para satisfacer la otra parte 
          .tarjeta__titulo.bg--1.d-flex.align-self-end.aling-items-center.justify-content-center.p-2
            h4.text-center.text-white.m-auto Acomodación
      .col-lg-4.mb-3
        .tarjeta.tarjeta-slide-up2.color-primario--borde.overflow-hidden.bg-gray(style="height: 300px")
          .tarjeta-slide-up__up: img(src='@/assets/curso/26.jpg', alt='Texto que describa la imagen' style='width:100%')
          .tarjeta__texto.p-5.m-auto.d-flex.align-self-center
            h3.text-center.m-auto Cada parte cede algo para alcanzar el acuerdo
          .tarjeta__titulo.bg--1.d-flex.align-self-end.aling-items-center.justify-content-center.p-2
            h4.text-center.text-white.m-auto Conciliación
    p.mb-5 Así, el gestor deportivo se enfrenta frecuentemente con muchos conflictos dentro de su equipo de trabajo, por lo que es importante tener en cuenta los siguientes aspectos para su gestión:
    .row.mb-5.justify-content-center
      .col-lg-10
        PasosA.color-acento-contenido.mb-5(tipo="n")
          .row.align-items-center
            .col-md-4
              figure
                img(src='@/assets/curso/27.svg', alt='Texto que describa la imagen')
            .col-md-8.mb-4.mb-md-0
              p Asumirlos sin temerles, con paciencia, con equilibrio emocional que debe demostrar un líder y sin desespero en su mediación, ya que no se deberán quemar las etapas.

          .row.align-items-center
            .col-md-9
              p Se debe centrar en los hechos, sucesos y nunca en las personas.
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/28.svg', alt='Texto que describa la imagen')
          .row.align-items-center
            .col-md-3
              figure
                img(src='@/assets/curso/29.svg', alt='Texto que describa la imagen')
            .col-md-9.mb-4.mb-md-0
              p Los conflictos no se resuelven con agresividad, violencia o posiciones de poder. Ya que con esto se puede vencer a alguien, pero no convencer ni persuadir por lo tanto el conflicto no se resolverá.

          .row.align-items-center
            .col-md-9
              p Se debe garantizar que cada parte colabore y aporte a la solución; no se deberá imponer.
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/30.svg', alt='Texto que describa la imagen')
          .row.align-items-center
            .col-md-3
              figure
                img(src='@/assets/curso/31.svg', alt='Texto que describa la imagen')
            .col-md-9.mb-4.mb-md-0
              p Se deben identificar las causas del conflicto. El error frecuente es tratar de solucionar o corregir los efectos. 

          .row.align-items-center
            .col-md-9
              p No se deben interrelacionar diferentes conflictos entre sí.
            .col-md-3.mb-4.mb-md-0
              figure
                img(src='@/assets/curso/32.svg', alt='Texto que describa la imagen')
          .row.align-items-center
            .col-md-3
              figure
                img(src='@/assets/curso/33.svg', alt='Texto que describa la imagen')
            .col-md-9.mb-4.mb-md-0
              p Finalmente, el conflicto debe ser mediado sin arbitrariedades, equitativamente y en términos de reciprocidad.
    #t_1_3.titulo-segundo(data-aos="fade-right")
      h2 1.3 Gestión de riesgo
    .row.mb-5.justify-content-center
      .col-lg-2: img(src='@/assets/curso/34.svg')
      .col-lg-10
        p El riesgo es entendido como el control de situaciones que pueden generar algún tipo de daño mediante mecanismos preventivos y correctivos en los casos que el riesgo se materializa. En un proyecto, los riesgos pueden presentarse desde diferentes enfoques, así:
    .row.mb-5.justify-content-center
      .col-lg-5
        .tarjeta.bg--1.p-5
          h4.text-white.text-center.mb-0 Riesgos para la ejecución del proyecto
      .col-lg-5
        .tarjeta.bg--3.p-5
          h4.text-center.mb-0 Riesgos inherentes a la actividad
    p.mb-5 Dentro del proyecto se deberán contemplar acciones preventivas y proactivas para identificar, con antelación, posibles peligros y controlar de manera oportuna los riesgos. Para tal fin es preciso implementar acciones como:
    figure.mb-5(data-aos="zoom-in-up")
      img(src='@/assets/curso/35.svg', alt='Texto que describa la imagen')
    #t_1_4.titulo-segundo(data-aos="fade-right")
      h2 1.4 Gestión de la calidad y aseguramiento de la calidad
    p.mb-5 Es preciso partir por la definición de calidad, la que es entendida como un proceso continuo, sin fin, de mejora aplicable a todas las fases y componentes del proyecto para mejorar los productos y servicios que la organización oferta. Así, la ISO 9000 define la calidad como “la totalidad de rasgos y características de un producto o servicio que son relevantes en su habilidad para satisfacer las necesidades declaradas o implícitas del cliente” Por otro lado, el IPMA define la calidad de un proyecto como “la base de  la calidad de un proyecto son las prácticas de dirección de calidad por la organización permanentemente implicado y contribuye a los procesos y resultados del proyecto”.
      br
      br
      |De acuerdo con lo anterior, la gestión de calidad comprende los siguientes componentes:
    figure.mb-5(data-aos="zoom-in-up")
      img(src='@/assets/curso/36.svg', alt='Texto que describa la imagen')
    .row.mb-5
      .col-lg-7(data-aos="fade-right")
        p Luego de pasar por la definición de política y objetivos de calidad propias de la fase de planificación del proyecto, sigue el aseguramiento de la calidad propia de la ejecución. Según el PMI (2004) el aseguramiento de la calidad es la aplicación de actividades planificadas y sistemáticas relativas a la calidad, para asegurar que el proyecto emplee todos los procesos necesarios para cumplir con los requisitos. 
          br
          br
          |En este proceso, el gestor deportivo cumple un papel importante, ya que tiene la responsabilidad de establecer procesos administrativos para asegurar que el alcance del proyecto cumple con los requerimientos del cliente conforme a parámetros normativos, de seguridad y conservación del medio ambiente.
        .cajon.color-primario.bg--1-claro.p-4.mb-4
          p.mb-0 El aseguramiento de la calidad permite prevenir más que corregir defectos de calidad, identificar claramente los objetivos y verificar su cumplimiento ajustado al plan y generar auditorías de calidad. Pero para que lo anterior sea posible, es indispensable conocer los elementos básicos para el plan correspondiente: 
      .col-lg-5(data-aos="fade-left"): img(src='@/assets/curso/37.jpg')
    .row.mb-5(data-aos="zoom-in-up").justify-content-center
      .col-lg-8: img(src='@/assets/curso/38.svg')
    p.mb-5 Coherente con la fase de ejecución del plan, cada una de las actividades del proyecto y sus respectivos entregables o productos finales, deberán cumplir con los siguientes parámetros:
    .row.mb-5.justify-content-center
      .col-lg-4
        .tarjeta.bg--1.p-5
          h4.text-white.text-center.mb-0 Gestión de riesgos
      .col-lg-4
        .tarjeta.bg--3.p-5
          h4.text-center.mb-0 Gestión ambiental
      .col-lg-4
        .tarjeta.bg--4.p-5
          h4.text-white.text-center.mb-0 Gestión de calidad
          

    
            
      

</template>

<script>
import BannerInterno from '../components/BannerInterno'

import BotonesC from '../components/BotonesC.vue'
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras,
    BotonesC,
    BannerInterno, // borrar una vez el componente "Muestras" no se necesite
  },
  data: () => ({
    mostrarIndicador: true, // variables de vue
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

<style lang="sass" scoped>
.tarjeta-rotate
  overflow-x: hidden

  &:hover
    .img-rotate
      transform: translateX(-50%)
  .img-rotate
    display: flex
    width: 200%
    position: relative
    transition: transform 0.3s ease-in-out
    .img-rotate__img
      flex: 1
      display: flex
      justify-content: center
.contenedor-tarjetas
  display: flex
  flex-wrap: wrap
  .tarjetas
    width: 248px !important
    flex-grow: .2
.tarjeta-slide-up
  overflow: hidden
  position: relative
  &:hover
    .tarjeta-slide-up__up
      bottom: 0%
    .tarjeta__texto
      z-index: -1
  .tarjeta-slide-up__up
    position: absolute
    width: 100%
    height: 100%
    bottom: -100%
    transition: bottom 0.3s ease-in-out
  .tarjeta__titulo
    position: absolute
    bottom: 0
    width: 100%
  .tarjeta__texto
    position: absolute
    bottom: 0

    height: 100%
.tarjeta-slide-up2
  overflow: hidden
  position: relative
  transition: background-color 0.3s ease-in-out
  &:hover
    border: solid $color-acento-botones !important
    .tarjeta-slide-up__up
      bottom: -100%
    .tarjeta__texto
      z-index: 1
    .tarjeta__titulo
      background-color: $color-acento-botones !important
  .tarjeta-slide-up__up
    position: absolute
    width: 100%
    height: 100%
    bottom: -100%
    bottom: 0%
    transition: bottom 0.3s ease-in-out
  .tarjeta__titulo
    transition: background-color 0.3s ease-in-out
    position: absolute
    bottom: 0
    width: 100%
  .tarjeta__texto
    position: absolute
    bottom: 0
    z-index: -1
    height: 100%

.tarjeta-icono
  position: relative
  .tarjeta-icono__icono
    position: absolute
    top: 0
    left: 3%
    transform: translateY(-25%)
  .tarjeta-icono__texto
    margin-left: 102px
.texto-oscuro
  h1,h2,h3,h4,h5, p
    color: $color-sistema-texto !important
</style>
