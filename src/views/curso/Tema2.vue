<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(:subTitulo="'2. Gestión del talento en la vida cotidiana y en las organizaciones'")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden
  

      .row.mb-5.align-items-center
        .col-lg-8

          .bg-color-1.p-4(data-aos="fade-left").mb-4
            p.mb-0 Después de comprender la importancia y transformación del talento humano, es esencial analizar los subprocesos que lo integran y su impacto en el desarrollo organizacional.

          h3(data-aos="fade-right").mb-4 Procesos que pueden o no ser parte de recursos humanos
          
          p(data-aos="fade-right") Algunos subprocesos pueden estar dentro del departamento de recursos humanos o ser gestionados de manera independiente, dependiendo de la estrategia organizacional. Estos procesos incluyen:

        .col-lg-4
          figure
            img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")

      .row.align-items-start.mb-5
        .col-lg-4
          figure
            img(src="@/assets/curso/tema2/2.png", alt="").mb-4.mb-lg-0
        .col-lg-8

          AcordionA(tipo="b")
            .div(titulo="Gestión de nómina")
              p Incluye la generación de contratos y afiliaciones a seguridad social, el manejo de la documentación laboral, la gestión de pagos fijos, variables y beneficios extralegales, así como la elaboración de reportes contables y el cumplimiento normativo.

            .div(titulo="Gestión legal y laboral")
              p Abarca la elaboración de contratos y documentos legales, la implementación de políticas laborales, la ejecución de procedimientos disciplinarios, como llamados de atención y suspensiones, y el equilibrio entre el cumplimiento normativo y el bienestar del trabajador.

            .div(titulo="Seguridad y salud en el trabajo")
              p Comprende la evaluación de riesgos y el desarrollo de políticas preventivas, la implementación de capacitaciones en seguridad, la reducción de accidentes laborales y la mejora del clima organizacional.

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
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
