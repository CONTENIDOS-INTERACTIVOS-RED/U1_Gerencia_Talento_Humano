<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Definición del talento humano'")
  .container.tarjeta.tarjeta--blanca.px-4.px-md-5.pt-md-5.pt-4

    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5
        .row.align-items-center
          .col-lg-7
            p.mb-4 Para comprender el concepto de talento humano, es fundamental considerar dos perspectivas complementarias:
            ul.lista-ul--color
              li.mb-0
                i.fas.fa-check-circle
                | #[b Como conjunto de colaboradores:] se refiere a los empleados que forman parte de una organización, contribuyen a sus objetivos y reciben una compensación por su trabajo.
              li.mb-0
                i.fas.fa-check-circle
                | #[b Como función organizacional:] es el área responsable de la gestión del talento humano, encargada de implementar estrategias y políticas que optimicen el potencial de los trabajadores, promoviendo un ambiente de trabajo productivo y motivador.

          .col-lg-5.align-self-end
            figure
              img(src="@/assets/curso/tema1/1.svg", style="max-width: 505px").mx-auto

    p(data-aos="fade-right").mb-5 Este enfoque integral abarca el desarrollo personal y profesional de los empleados, así como su bienestar dentro del entorno laboral. La gestión del talento humano implica diversos procesos clave:

    .row.justify-content-center.mb-3
      .col-lg-11
        .tarjeta-move.d-flex.align-items-center
          .tarjeta-move__title(style="background-color: #86B60C; "): h4.mb-0.text-white Atracción de talento  
          .tarjeta-move__content.w-100(style="background-color: #E6F0CD; border: solid 2px #86B60C")
            p.mb-0 Diseño de estrategias para captar a los mejores profesionales.

    .row.justify-content-center.mb-3
      .col-lg-11
        .tarjeta-move.d-flex.align-items-center
          .tarjeta-move__title(style="background-color: #36CEEF "): h4.mb-0 Desarrollo y capacitación 
          .tarjeta-move__content.w-100(style="background-color: #D6F5FB; border: solid 2px #36CEEF")
            p.mb-0 Implementación de programas de formación continua.

    .row.justify-content-center.mb-3
      .col-lg-11
        .tarjeta-move.d-flex.align-items-center
          .tarjeta-move__title(style="background-color: #FF9D1C; "): h4.mb-0.text-white Evaluación del desempeño  
          .tarjeta-move__content.w-100(style="background-color: #FFEBD0; border: solid 2px #FF9D1C")
            p.mb-0 Medición del rendimiento y retroalimentación para la mejora.

    .row.justify-content-center.mb-3
      .col-lg-11
        .tarjeta-move.d-flex.align-items-center
          .tarjeta-move__title(style="background-color: #E2DACC "): h4.mb-0 Retención de talento 
          .tarjeta-move__content.w-100(style="background-color: #F6F3EF; border: solid 2px #E2DACC")
            p.mb-0 Creación de sistemas de compensación y beneficios.

    .row.justify-content-center.mb-5
      .col-lg-11
        .tarjeta-move.d-flex.align-items-center
          .tarjeta-move__title(style="background-color: #8B550E "): h4.mb-0.text-white Cumplimiento normativo 
          .tarjeta-move__content.w-100(style="background-color: #FFF4E6; border: solid 2px #8B550E")
            p.mb-0 Aseguramiento de los derechos y bienestar de los empleados.


    h2(data-aos="fade-left").mb-5 Importancia estratégica del talento humano

    p(data-aos="fade-right").mb-5 Según Flores (2014), la administración de recursos humanos abarca la contratación, desarrollo, motivación y compromiso de los empleados con la organización. A su vez, según Fernández (2013), el departamento de recursos humanos debe anticiparse a los cambios y participar activamente en la estrategia organizacional, mediante:


    .row.justify-content-center.align-items-stretch.mb-5
      .col-lg-4
        .tarjeta(style="background-color: #86B60C").h-100
          .p-4
            h4.mb-2.text-white 01
            p.mb-0.text-white Construcción de la arquitectura de recursos humanos.

      .col-lg-4
        .tarjeta(style="background-color: #36CEEF").h-100
          .p-4
            h4.mb-2 02
            p.mb-0 Desarrollo de la cultura organizacional.

      .col-lg-4
        .tarjeta(style="background-color: #FF9D1C").h-100
          .p-4
            h4.mb-2 03
            p.mb-0 Fomento del liderazgo y la innovación en la gestión del talento

    h2(data-aos="fade-left").mb-5 Evolución de la percepción del trabajo

    p(data-aos="fade-right").mb-5 El área de talento humano ha experimentado una transformación significativa debido a cambios generacionales en la percepción del trabajo. Mientras que los #[b Baby Boomers] valoraban la estabilidad laboral y el compromiso a largo plazo, los #[b Millennials] y la #[b Generación Z] buscan mayor flexibilidad y significado en sus carreras. Estos cambios están impulsados por:


    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-1.png")
            .col-lg-7
              h5 Globalización y comunicación
              p Mayor acceso a información sobre oportunidades laborales y mejores prácticas empresariales.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-2.png")
            .col-lg-7
              h5 Avances tecnológicos
              p Expansión del trabajo remoto y metodologías flexibles.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-3.png")
            .col-lg-7
              h5 Bienestar y calidad de vida
              p Priorización del equilibrio entre vida laboral y personal.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-4.png")
            .col-lg-7
              h5 Estrés laboral y burnout
              p Creciente demanda por ambientes laborales saludables.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5
              figure
                img(src="@/assets/curso/tema1/slider-5.png")
            .col-lg-7
              h5 Propósito y valores
              p Mayor interés en empresas con impacto positivo en la sociedad.

    h2(data-aos="fade-left").mb-5 Adaptación de las empresas a la nueva realidad laboral

    p(data-aos="fade-right").mb-5 Para responder a estos cambios, los departamentos de talento humano han evolucionado de funciones administrativas a roles estratégicos. Algunas acciones clave incluyen:

    .bg-full-width.bg-color-3
      .px-4.px-md-5
        .row.align-items-center
          .col-lg-7
            ul.lista-ul--color
              li.mb-2
                i.fas.fa-check-circle
                | #[b Fomento del bienestar integral:] implementación de programas de salud física, mental y emocional.

              li.mb-2
                i.fas.fa-check-circle
                | #[b Cultura organizacional inclusiva:] promoción de diversidad, equidad e inclusión.

              li.mb-2
                i.fas.fa-check-circle
                | #[b Desarrollo y aprendizaje continuo:] creación de oportunidades de capacitación y mentoría.

              li.mb-2
                i.fas.fa-check-circle
                | #[b Flexibilidad laboral:] modelos de trabajo remoto e híbrido.

              li.mb-2
                i.fas.fa-check-circle
                | #[b Comunicación bidireccional:] espacios de diálogo abierto entre empleados y líderes.

              li.mb-0
                i.fas.fa-check-circle
                | #[b Evaluación y reconocimiento:] medición de desempeño enfocada en el crecimiento personal.

          .col-lg-5.align-self-end
            figure
              img(src="@/assets/curso/tema1/2.svg", style="max-width: 400px").mx-auto


    .bg-full-width.bg-color-1
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 La gestión del talento humano ha evolucionado para alinearse con las expectativas cambiantes de los colaboradores y las necesidades del mercado laboral. Las organizaciones que adapten sus estrategias a esta nueva realidad no solo atraerán y retendrán talento, sino que también mejorarán su productividad y sostenibilidad a largo plazo. Para ello, es crucial que la alta dirección valore el papel estratégico del talento humano y lo integre en sus decisiones clave.

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://elibro.net/es/lc/tecnologicadeloriente/titulos/274611" target="_blank" rel="noopener noreferrer") De Castro Emilio Cerdá, F. J. A. L. M. (s/f). Las energías renovables en el ámbito internacional. Revistasice.com. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/book.svg' :style="{'max-width':'16px'}")
              span De Janeiro, R. (1992). La declaración del Río sobre el Medio Ambiente y el Desarrollo. Río de Janeiro República Federativa del Brasil., aprobada en Estocolmo el, 16.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/QKLjwCMyv3M?si=uAWhO9tnyghljaJg" target="_blank" rel="noopener noreferrer") Innovación y sostenibilidad.

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
