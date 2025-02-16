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


      h2(data-aos="fade-left").mb-4 Modelo de gestión por competencias
      p(data-aos="fade-right") Este modelo se centra en identificar, desarrollar y evaluar las competencias esenciales para el desempeño laboral. Sus elementos clave incluyen:

      .bg-full-width.bg-color-info.mb-5
        .px-4.px-md-5.pt-4.pt-md-5
          .row.justify-content-center.align-items-center.mb-5
            .col-lg-10
              ImagenInfografica.color-secundario
                  template(v-slot:imagen)
                    figure
                      img(src='@/assets/curso/tema2/info1.png', alt='', style="max-width: 642px;").mx-auto

                  .bg-color-white.box-shadow.p-3(x="19%" y="55%" numero="+")
                    h5 Definición de competencias
                    p Conjunto de conocimientos, habilidades y actitudes necesarias para cada puesto.

                  .bg-color-white.box-shadow.p-3(x="30%" y="15%" numero="+")
                    h5 Identificación
                    p Análisis de las competencias requeridas en la organización.

                  .bg-color-white.box-shadow.p-3(x="49%" y="2%" numero="+")
                    h5 Evaluación
                    p Métodos para medir el desempeño de los empleados.

                  .bg-color-white.box-shadow.p-3(x="72%" y="22%" numero="+")
                    h5 Desarrollo
                    p Programas de formación, mentoría y coaching.

                  .bg-color-white.box-shadow.p-3(x="80%" y="55%" numero="+")
                    h5 Planificación de carrera
                    p Estrategias para el crecimiento profesional dentro de la empresa.


      h2(data-aos="fade-left").mb-4 Planificación estratégica de talento humano
      p(data-aos="fade-right") La planificación estratégica determina la ruta de trabajo del área de recursos humanos y debe estar alineada con la estrategia organizacional. Su objetivo es equilibrar la oferta y demanda de talento dentro de la empresa, asegurando que los empleados sean gestionados eficientemente.


      .row.justify-content-center.align-items-stretch.mb-5
        .col-lg-3
          .tarjeta(style="background-color: #F2F7E5").h-100
            .bg(style="background-color: #86B60C").px-4.px-lg-5.py-3.rounded-top
              h4.mb-0.text-center.text-white Optimización del capital humano
            p.mb-0.p-4 Asegura personal capacitado y adecuado para cada función.

        .col-lg-3
          .tarjeta(style="background-color: #E9F9FD").h-100
            .bg(style="background-color: #36CEEF").px-4.px-lg-5.py-3.rounded-top
              h4.mb-0.text-center Desarrollo de colaboradores	
            p.mb-0.p-4 Mejora la formación y motivación de los empleados.

        .col-lg-3
          .tarjeta(style="background-color: #FFF4E6").h-100
            .bg(style="background-color: #FF9D1C").px-4.px-lg-5.py-3.rounded-top
              h4.mb-0.text-center Mejora del clima laboral	
            p.mb-0.p-4 Contribuye al bienestar organizacional.

        .col-lg-3
          .tarjeta(style="background-color: #F9F7F4").h-100
            .bg(style="background-color: #E2DACC").px-4.px-lg-5.py-3.rounded-top
              h4.mb-0.text-center Retención de talento
            p.mb-0.p-4 Reduce la rotación de personal.


      h2(data-aos="fade-left").mb-4 Atracción y selección de talento

      .bg-full-width.bg-color-4.mb-5
        .px-4.px-md-5.pt-4
          .row.justify-content-center.align-items-center.bg-h85
            .col-lg-11
              .row.justify-content-center.align-items-center
                .col-lg-7(data-aos="fade-left")
                  .pt-2.pb-4.pb-lg-0
                    p(data-aos="fade-right") Este proceso garantiza que la empresa cuente con el talento adecuado. Incluye:

                    ul.lista-ul--color.color-dark
                      li.mb-1
                        i.fas.fa-arrow-circle-right
                        | #[b Análisis del puesto:] identificación de habilidades y competencias requeridas.

                      li.mb-1
                        i.fas.fa-arrow-circle-right
                        | #[b Atracción de talento:] uso de plataformas de empleo, ferias y marca empleadora.

                      li.mb-1
                        i.fas.fa-arrow-circle-right
                        | #[b Evaluación de candidatos:] entrevistas, pruebas psicométricas y técnicas.

                      li.mb-0
                        i.fas.fa-arrow-circle-right
                        | #[b Selección final:] verificación de referencias y oferta laboral.

                .col-lg-5(data-aos="zoom-in")
                  img.img-fluid(src='@/assets/curso/tema2/3.svg', style="max-width:505px", alt="").mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0

      p(data-aos="fade-right").mb-4 La inclusión de líderes en la selección de personal favorece una mejor adaptación del nuevo talento y fortalece la cultura organizacional.

      h2(data-aos="fade-left").mb-4 Atracción y selección de talento

      p(data-aos="fade-right").mb-4 El proceso de formación es esencial para la mejora continua de los colaboradores. Sus fases incluyen:

      ul.lista-ul.mb-5
        li
          i.lista-ul__vineta
          | Detección de necesidades de capacitación (DNC).

        li
          i.lista-ul__vineta
          | Definición de competencias organizacionales.

        li
          i.lista-ul__vineta
          | La formación y desarrollo de talento refuerzan la estrategia empresarial y promueven el crecimiento profesional de los colaboradores.


      h4(data-aos="fade-left").mb-4 Detección de necesidades de capacitación (DNC).

      .bg-color-info.p-4.p-xl-5.mb-5
        .row.justify-content-center.align-items-center
          figure
            img(src='@/assets/curso/tema2/4.svg', alt='', style="max-width: 800px;").mx-auto

      h4(data-aos="fade-left").mb-4 Definición de competencias organizacionales.

      .bg-full-width-2.bg-fondo-2
        .px-4.px-md-5.pb-md-3

          .row.justify-content-center.align-items-stretch.mb-5
            .col-lg-4.mb-4(data-aos="zoom-in-up")
              .custom-image-card.h-100
                img.custom-image-card__image(src="@/assets/curso/tema2/5.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Nivel transversal
                  p.mb-0 Influye en toda la empresa.
            .col-lg-4.mb-4(data-aos="zoom-in-down")
              .custom-image-card.h-100
                img.custom-image-card__image(src="@/assets/curso/tema2/6.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Nivel por áreas
                  p.mb-0 Responde a necesidades específicas de cada departamento.
            .col-lg-4.mb-4(data-aos="zoom-in-down")
              .custom-image-card.h-100
                img.custom-image-card__image(src="@/assets/curso/tema2/7.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Nivel individual
                  p.mb-0 Enfocado en las habilidades de cada empleado.


      .row.mb-5
        .col-lg-5
          figure
            img(src="@/assets/curso/tema2/8.png", data-aos="zoom-in")
        .col-lg-7
          .bg-color-3.p-4(data-aos="fade-left").mb-4
            p.mb-0 La formación y desarrollo de talento refuerzan la estrategia empresarial y promueven el crecimiento profesional de los colaboradores.

          p(data-aos="fade-left").mb-4 La gestión del talento humano ha evolucionado hacia un modelo estratégico que prioriza el bienestar, la formación y la alineación con los objetivos organizacionales. Las empresas que implementen estos enfoques no solo atraerán y retendrán talento, sino que también fortalecerán su competitividad y sostenibilidad en el tiempo.


      .titulo-figura.mb-4
        h5 Figura 1. 
        span Niveles de asignación de competencias formativas

      .bg-color-info.p-4.p-xl-5.mb-5
        .row.justify-content-center.align-items-center
          figure
            img(src='@/assets/curso/tema2/9.svg', alt='', style="max-width: 495px;").mx-auto


      .row.mb-5
        .col-lg-7
          p(data-aos="fade-left").mb-4 Para diseñar un programa de formación dentro de una organización, es fundamental identificar las competencias a desarrollar en los diferentes niveles. Una vez determinadas, se procede a seleccionar los métodos y recursos más adecuados, los cuales pueden incluir:
          ul.lista-ul--color.color-dark.mb-4
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Talleres presenciales
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Cursos en línea
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Formación e-learning
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Seminarios
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Programas de mentoría y coaching
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Formación técnica o académica

          .bg-color-5.p-4(data-aos="fade-left").mb-4
            p(data-aos="fade-left").mb-0 La elección depende de las características de los empleados y de los objetivos establecidos, garantizando que los contenidos sean actualizados y relevantes, alineados con las tendencias del sector y la evolución tecnológica.

        .col-lg-5
          figure
            img(src="@/assets/curso/tema2/10.png", data-aos="zoom-in")


      h2(data-aos="fade-left").mb-4 Asignación de recursos
      p(data-aos="fade-right").mb-4 La asignación de recursos es clave en la implementación de programas formativos, ya que el presupuesto disponible influye en la selección de métodos y estrategias. Un presupuesto adecuado permite:


      .row.justify-content-center.align-items-stretch.mb-4
        .col-lg-6
          .bg-color-1.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema2/11.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 Elegir herramientas adecuadas para la formación.

        .col-lg-6
          .bg-color-1.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg-auto
                img(src="@/assets/curso/tema2/11.svg", style="max-width: 90px").mx-auto
              .col-lg
                p.mb-0 Maximizar el impacto de la capacitación en la mayor cantidad de empleados.

      p(data-aos="fade-right").mb-5 En muchos casos, la mayor parte de los recursos se destinan a la capacitación de la alta gerencia y líderes organizacionales, ya que estos juegan un papel fundamental en la ejecución de los objetivos estratégicos. Su formación no solo fortalece su capacidad de liderazgo y gestión, sino que también los prepara en pensamiento estratégico y toma de decisiones.


      h2(data-aos="fade-left").mb-4 Seguimiento y evaluación de la formación
      p(data-aos="fade-right").mb-4 Una vez implementado el programa, es esencial realizar un seguimiento del progreso de los participantes a través de:

      .row.justify-content-center.align-items-stretch.mb-4
        .col-lg-4
          .tarjeta.bg-color-primario.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg
                p.mb-0.text-white.mt-lg-2 Evaluaciones periódicas.

        .col-lg-4
          .tarjeta.bg-color-secundario.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg
                p.mb-0.mt-lg-2 Retroalimentación constante.
        
        .col-lg-4
          .tarjeta.bg-color-terciario.p-4(data-aos="fade-left").h-100
            .row.align-items-center
              .col-lg
                p.mb-0 Análisis del impacto de la formación en el desempeño laboral.


      p(data-aos="fade-right").mb-5 Además, se fomenta un ambiente de aprendizaje continuo, incentivando el intercambio de conocimientos y experiencias entre colaboradores.

      h2(data-aos="fade-left").mb-4 Modelo 70-20-10

      p(data-aos="fade-right").mb-4 El modelo 70-20-10 es un enfoque ampliamente utilizado en el desarrollo profesional, basado en la combinación de experiencias de aprendizaje:

      TabsC.color-acento-contenido.mb-0
        .tabs-content.border.px-4.p-md-5.py-3(titulo="70% - Experiencia práctica	" :icon="require('@/assets/bullets/icon-tab-c-1.svg')" )
          .row
            .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 70% - Experiencia práctica	
              p Se adquieren conocimientos a través del trabajo, la resolución de problemas y la toma de decisiones en situaciones reales.
          
            .col-md-6.col-lg-5.col-xl-4.order-1
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema2/tab-1.png', alt='')
        .tabs-content.border.px-4.p-md-5.py-3(titulo="20% - Aprendizaje social	" :icon="require('@/assets/bullets/icon-tab-c-2.svg')" )
          .row
            .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 20% - Aprendizaje social	
              p Se desarrolla a través de la interacción con otros: trabajo en equipo, mentorías y coaching.
          
            .col-md-6.col-lg-5.col-xl-4.order-1
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema2/tab-2.png', alt='')

        .tabs-content.border.px-4.p-md-5.py-3(titulo="Idear" :icon="require('@/assets/bullets/icon-tab-c-3.svg')" )
          .row
            .col-md-6.col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
              h4 10% - Formación formal
              p Incluye cursos, talleres y seminarios, proporcionando conocimientos teóricos y habilidades específicas.

            .col-md-6.col-lg-5.col-xl-4.order-1
              figure(data-aos="zoom-in")
                img(src='@/assets/curso/tema2/tab-3.png', alt='', style="width: 100%;")


      div(style="background-color: #FFEBD0").p-4.mb-5
        p(data-aos="fade-right").mb-0 Este modelo destaca que la formación estructurada es solo una parte del aprendizaje, ya que la experiencia directa y la interacción social son elementos clave en el desarrollo de competencias.


      h2(data-aos="fade-left").mb-4 Evaluación del impacto

      p(data-aos="fade-right").mb-4 El ciclo de formación finaliza con una evaluación del impacto en la organización, analizando mejoras en:

      .bg-color-info.p-4.p-xl-5.mb-5
        .row.justify-content-center.align-items-center
          .col-lg-8
            figure
              img(src='@/assets/curso/tema2/12.svg', alt='', style="max-width: 760px;").mx-auto

      p(data-aos="fade-right").mb-4 Los resultados obtenidos permiten ajustar las estrategias formativas y garantizar un proceso de mejora continua.

      h2(data-aos="fade-left").mb-4 Gestión del desempeño

      p(data-aos="fade-right").mb-4 Este proceso comprende un conjunto de prácticas y herramientas diseñadas para evaluar, mejorar y optimizar el rendimiento de los empleados. Su objetivo es alinear los objetivos individuales con los estratégicos de la empresa, fomentar el desarrollo profesional y mejorar la productividad general.

      h2(data-aos="fade-left").mb-4 Métodos de evaluación

      p(data-aos="fade-right").mb-4 Existen dos enfoques principales para medir el desempeño:

      .bg-full-width.bg-fondo-slider.mb-5
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white
            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slider-1.png")
              .col-lg-7
                h5 Evaluación de competencias
                p Permite medir el nivel de desarrollo de habilidades específicas en el entorno laboral. Las modalidades incluyen: autoevaluación, evaluación por supervisores y retroalimentación de clientes internos y compañeros. Se emplean modelos como la evaluación 360, 180 o 90 grados, dependiendo de la profundidad requerida. Sin embargo, este método tiene un componente de subjetividad, pues las calificaciones dependen de la percepción de otros.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slider-2.png")
              .col-lg-7
                h5 Medición por objetivos
                p Se basa en la definición de metas claras y alineadas con los objetivos organizacionales. Para ello, se utiliza el criterio SMART (específicas, medibles, alcanzables, relevantes y temporales).

      p(data-aos="fade-right").mb-4 El seguimiento del desempeño es continuo, con revisiones periódicas y retroalimentación constante para identificar oportunidades de mejora.

      .bg-full-width-2.bg-fondo-2
        .px-4.px-md-5.pb-md-3

          .row.justify-content-center.align-items-stretch.mb-5
            .col-lg-6.mb-4(data-aos="zoom-in-up")
              .custom-image-card.h-100
                img.custom-image-card__image(src="@/assets/curso/tema2/13.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Evaluación de competencias	
                  p.mb-0 Analiza habilidades específicas en el entorno laboral mediante retroalimentación de diferentes fuentes.
            .col-lg-6.mb-4(data-aos="zoom-in-down")
              .custom-image-card.h-100
                img.custom-image-card__image(src="@/assets/curso/tema2/14.png" alt="")
                .custom-image-card__text.p-4
                  h5.mb-2.text-center Medición por objetivos	
                  p.mb-0 Se centra en el cumplimiento de metas específicas, eliminando la subjetividad de la evaluación.


      h2(data-aos="fade-left").mb-4 Implementación y mejora del desempeño


      .row.mb-5
        .col-lg-7
          p(data-aos="fade-left").mb-4 Una evaluación efectiva no solo permite medir resultados, sino que también facilita la toma de decisiones respecto a:
          ul.lista-ul--color.color-dark.mb-4
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Necesidades de formación o mentoría.
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Planes de carrera y desarrollo profesional.
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Ascensos, ajustes salariales o bonificaciones.
            li.mb-0
              i.fas.fa-arrow-circle-right
              | Acciones correctivas, incluyendo posibles desvinculaciones.

          .bg-color-5.p-4(data-aos="fade-left").mb-4
            p(data-aos="fade-left").mb-0 Así, la gestión del desempeño contribuye al desarrollo de los empleados y al éxito organizacional, promoviendo un ambiente laboral motivador.
        .col-lg-5
          figure
            img(src="@/assets/curso/tema2/15.png", data-aos="zoom-in")


      h2(data-aos="fade-left").mb-4 Bienestar organizacional

      p(data-aos="fade-right").mb-4 El bienestar organizacional abarca condiciones y prácticas que promueven la salud física, emocional y social de los empleados. Este proceso no solo mejora el clima laboral y la retención del talento, sino que también aumenta la productividad. Su enfoque va más allá de eventos como celebraciones o reuniones recreativas.

      .bg-full-width.bg-fondo-slider.mb-5
        .p-4.p-md-5
          SlyderA(tipo="b").bg-white
            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slider-1-2.png")
              .col-lg-7
                h5 Diagnóstico del bienestar
                p Para conocer el estado del bienestar organizacional, se aplican diversas mediciones: evaluación del clima laboral, medición de la cultura organizacional, encuestas de riesgo psicosocial y entrevistas o encuestas sobre la percepción del entorno laboral.
            .row.align-items-center.p-4.p-md-5
              .col-lg-5
                figure
                  img(src="@/assets/curso/tema2/slider-2-2.png")
              .col-lg-7
                h5 Diseño de programas de bienestar
                p A partir de los diagnósticos, se establecen objetivos alineados con la estrategia organizacional, tales como la reducción del estrés laboral, el aumento de la satisfacción de los empleados y la mejora de la salud física y mental.

      p(data-aos="fade-right").mb-0 Los programas diseñados incluyen iniciativas que impactan la vida del colaborador en diversas dimensiones:

      .bg-full-width-2.bg-fondo-3.mb-5
        .p-4.p-md-5
          .row.justify-content-center.align-items-stretch.mb-5
            .col-lg-3.mb-4(data-aos="zoom-in-up")
              .bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema2/16.svg"
                  alt=""
                  style="width: 90px"
                )
                h5.mb-2.text-center Salud física
                p.mb-0.text-center Proporcionar al estudiante una comprensión inicial sobre qué es el derecho y su importancia en la sociedad.
            
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema2/17.svg"
                  alt=""
                  style="width: 90px"
                )
                h5.mb-2.text-center Salud mental
                p.mb-0.text-center Proporcionar al estudiante una comprensión inicial sobre qué es el derecho y su importancia en la sociedad.
            
            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema2/18.svg"
                  alt=""
                  style="width: 90px"
                )
                h5.mb-2.text-center Equilibrio vida-trabajo
                p.mb-0.text-center Proporcionar al estudiante una comprensión inicial sobre qué es el derecho y su importancia en la sociedad.

            div.col-lg-3.mb-4(data-aos="zoom-in-up")
              div.bg-color-white.box-shadow.px-4.py-5.h-100
                img.mx-auto.d-block.mb-4(
                  src="@/assets/curso/tema2/19.svg"
                  alt=""
                  style="width: 90px"
                )
                h5.mb-2.text-center Cultura de reconocimiento
                p.mb-0.text-center Proporcionar al estudiante una comprensión inicial sobre qué es el derecho y su importancia en la sociedad.


          h2(data-aos="fade-left").mb-4 Implementación y liderazgo



      .bg-full-width.bg-color-4.mb-0
        .px-4.px-md-5.pt-4
          .row.justify-content-center.align-items-center.bg-h85
            .col-lg-11
              .row.justify-content-center.align-items-center
                .col-lg-7(data-aos="fade-left")
                  .pt-2.pb-4.pb-lg-0
                    p(data-aos="fade-right") La implementación efectiva de programas de bienestar requiere:

                    ul.lista-ul--color.color-dark
                      li.mb-1
                        i.fas.fa-arrow-circle-right
                        | Comunicación interna clara sobre los recursos disponibles.

                      li.mb-1
                        i.fas.fa-arrow-circle-right
                        | Capacitación de líderes en bienestar organizacional.

                      li.mb-1
                        i.fas.fa-arrow-circle-right
                        | Fomento de un liderazgo participativo que escuche las necesidades de los empleados.

                .col-lg-5(data-aos="zoom-in")
                  img.img-fluid(src='@/assets/curso/tema2/20.svg', style="max-width:400px", alt="").mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0



      .bg-full-width(style="background-color: #FFEBD0").mb-5
        .p-4.p-md-5
          p(data-aos="fade-right").mb-0 Este modelo destaca que la formación estructurada es solo una parte del aprendizaje, ya que la experiencia directa y la interacción social son elementos clave en el desarrollo de competencias.

      .titulo-figura.mb-4
        h5 Figura 2. 
        span Procesos de gestión del talento humano

      .bg-color-info.p-4.p-xl-5.mb-5
        .row.justify-content-center.align-items-center
          figure
            img(src='@/assets/curso/tema2/21.png', alt='', style="max-width: 900px;").mx-auto


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
