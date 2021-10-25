<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Evaluación solicitudes financieras bajo la normatividad SARLAFT
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Evaluación solicitudes financieras bajo la normatividad SARLAFT.
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 13330003
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 48 
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 1
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenido, apreciado aprendiz.
    p Conozca un poco lo que verá en este programa de formación:
    p El Servicio Nacional de Aprendizaje SENA le extiende la bienvenida al programa de formación: <b>Evaluación solicitudes financieras bajo la normatividad SARLAFT</b>, con el cual usted, como aprendiz, podrá realizar diferentes procesos y actividades encaminadas a determinar los requisitos cumplidos por los clientes dentro del Sistema de Administración del Riesgo de Lavado de Activos y de la Financiación del Terrorismo, cuya finalidad es conocer la responsabilidad que tienen las empresas de servicios financieros y entidades afines de gestionar control para evitar riesgos y que los dineros de procedencia ilícita circulen libremente por las economías nacionales o internacionales.
    p El Lavado de Activos y la Financiación del Terrorismo (LA/ FT) se han convertido en flagelos para la humanidad, impactando negativamente la economía y la sociedad, donde se evidencia la utilización de entidades y negocios del sector financiero para lograr fines ilícitos.
    p Por esta razón, es importante apoyar a las empresas instruyendo en mecanismos de prevención para evitar que la delincuencia organizada utilice a las entidades del sector financiero para darle apariencia de legalidad a los activos provenientes de actividades delictivas o para canalizar los recursos lícitos o ilícitos con destino a la realización de actividades terroristas, y así contribuir para que nuestro país pueda salir de este flagelo que, de una u otra manera, viene atentando contra la estabilidad económica de Colombia.
    p Durante el presente curso, se dará un recorrido sobre la normatividad y sobre su aplicación, para que usted, apreciado aprendiz, pueda directamente aplicar conocimientos, diligenciar formatos del Sistema de Administración del Riesgo de Lavado de Activos y de la Financiación del Terrorismo, y se convierta en un empoderado del cambio en las organizaciones financieras y, en general, en cualquier empresa, ya que la normatividad no es solo para entidades financieras. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p La problemática de la prevención del lavado de activos y financiación del terrorismo es un asunto que los diferentes Estados han venido reglamentando y controlando, dejando en parte a las entidades del sector real y de servicios financieros la responsabilidad de ejercer control para evitar que los dineros de procedencia ilícita circulen libremente por las economías nacionales e internacionales.
    p Como respuesta a las necesidades que genera la situación anterior y en la búsqueda de opciones para que los trabajadores del sector real y financiero que tienen directa relación con la evaluación de solicitudes de servicios financieros obtengan niveles de conocimiento y desarrollen destrezas, habilidades y la fundamentación de actitudes y valores sobre los sistemas para la administración del riesgo y las estrategias a implementar para el control y prevención del lavado de activos y financiación del terrorismo, el Servicio Nacional de Aprendizaje SENA ha diseñado el programa de nivel complementario denominado Evaluación solicitudes financieras bajo la normatividad SARLAFT.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar

    p 210301088 - Evaluar solicitudes financieras de acuerdo con tipo de producto y manual técnico. 


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    p Dominio de los elementos básicos relacionados con la evaluación de solicitudes financieras. 
      br
      | Manejo de herramientas informáticas y de comunicación.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso

    p N/A


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica
    
    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportada en el utilización de las tecnologías de la información y la comunicación, integrada en ambientes abiertos y pluritecnológicos que, en todo caso, recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
    ul.lista-ul--color.px-4
      li.mb-1
        i.fas.fa-circle
        | Simulación.  
      li.mb-1 
        i.fas.fa-circle
        | Trabajo colaborativo.
      li.mb-1 
        i.fas.fa-circle
        | Dinámica de grupos.
      li 
        i.fas.fa-circle
        | Técnicas participativas.
      li 
        i.fas.fa-circle
        | Trabajo de campo.  
    
    p Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul--color.px-4
      li.mb-1
        i.fas.fa-circle
        | El instructor – Tutor.  
      li.mb-1 
        i.fas.fa-circle
        | El entorno.
      li.mb-1 
        i.fas.fa-circle
        | Las TIC.
      li 
        i.fas.fa-circle
        | El trabajo colaborativo.

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
