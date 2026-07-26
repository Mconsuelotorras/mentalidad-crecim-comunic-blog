---
---
# Producto Nuevo, Canales Desincronizados: Un Post-Mortem sobre Comunicación y Procesos en un Emprendimiento Gastronómico

   ## Introducción
   
   En un emprendimiento gastronómico en crecimiento, la comunicación entre lo que ocurre en el local físico y lo que se muestra en los canales digitales no es un detalle menor: es parte de la experiencia de compra. Este post documenta un incidente real ocurrido durante el lanzamiento de un nuevo producto, analiza sus causas raíz mediante un post-mortem constructivo, y describe el proceso implementado a partir de una mentalidad de crecimiento para evitar que se repita.

   ## Contexto
   
   El proyecto es una marca de comida mexicana con año y medio de trayectoria, actualmente en expansión, que atraviesa un proceso de rebranding y el diseño de un nuevo local de take away. La estructura del equipo incluye a la persona encargada de marketing y comunicación, responsable de mantener alineados tres frentes (identidad de marca, espacio físico y comunicación digital), la persona encargada de cocina, responsable de las novedades de menú y la operación del local y personas que trabajan dentro de la cocina, responsables de elaborar los productos.
   Al momento del incidente no existía un protocolo formal que sincronizara los lanzamientos de productos nuevos entre el local y los canales digitales (redes sociales y la plataforma de pedidos online Pedix): las novedades de cocina se comunicaban e implementaban de manera informal, sin un punto de control que asegurara que se reflejaran en todos los canales el mismo día.

   ## Problema
   
   El 10 de mayo de 2026 se lanzó un nuevo producto, nuevo combo de tacos, y comenzó a ofrecerse para pedidos presenciales en el local. La comunicación en redes sociales y la carga en Pedix no se realizaron en simultáneo con el lanzamiento en el local físico.
El problema pasó desapercibido durante siete días, hasta que el 17 de mayo de 2026 una clienta que había pedido el combo presencialmente intentó volver a pedirlo a través de Pedix, no lo encontró disponible, y consultó por WhatsApp.
Causas raíz identificadas:

•	Ausencia de un calendario de lanzamiento: no existía un cronograma que vinculara la fecha de disponibilidad de productos en el local con la actualización de redes y plataforma de pedidos.

•	Comunicación informal entre cocina y marketing: los cambios de menú no llegaban de forma sistemática al área de comunicación, dependían de un aviso puntual y no de un proceso definido.

•	Detección reactiva, no proactiva: el desfasaje se descubrió por la consulta de una clienta, no por un chequeo interno propio.


   ## Acciones
   
   Para resolver el problema de fondo, y no solo el caso puntual, se implementaron los siguientes cambios de proceso:
   
•	Calendario de lanzamiento de productos: cada producto nuevo se planifica con fecha de salida definida de antemano, visible para todo el equipo.

•	Regla de sincronización same-day: el mismo día en que un producto se habilita en el local, se actualiza en simultáneo la comunicación en redes sociales y la disponibilidad en la plataforma de pedidos. Ningún canal queda adelantado ni atrasado respecto de los demás.

•	Checklist previo a cada lanzamiento: antes de anunciar un producto nuevo en redes, se verifica que ya esté cargado en la plataforma de pedidos, evitando generar expectativa sobre algo que el cliente todavía no puede pedir online.


   ## Aprendizajes
   
   •	Un error de coordinación no constituye un fracaso individual, sino información sobre un proceso que faltaba definir. Abordarlo como oportunidad de mejora, en lugar de minimizarlo, resultó clave para resolverlo de raíz.
   
•	La comunicación entre áreas de un emprendimiento pequeño no puede depender de la memoria o la buena voluntad de las personas involucradas: requiere un sistema, por simple que sea.

•	Detectar un problema a través de un cliente, en lugar de mediante monitoreo interno, constituye una señal de alerta en sí misma: indica la ausencia de una instancia de revisión previa a que el problema llegue al cliente.

•	La previsión, mediante la planificación anticipada de lanzamientos, resulta más sostenible que la corrección apresurada después de cada error.


   ## Control de versiones
   
   El desarrollo de este blog se documentó utilizando Git y GitHub, registrando el proceso en etapas mediante commits sucesivos en lugar de una única subida de contenido. Esto permite trazar la construcción del análisis: desde la estructura inicial, pasando por el desarrollo del problema y las acciones, hasta la incorporación de la reflexión final.
   
   
**Repositorio:** [Ver repositorio](https://github.com/Mconsuelotorras/mentalidad-crecim-comunic-blog)


   **Historial de commits:** [Ver historial de commits](https://github.com/Mconsuelotorras/mentalidad-crecim-comunic-blog/commits/main)

   ## Reflexión sobre feedback radicalmente sincero
   
   Tras la consulta de la clienta por WhatsApp, se identificó que el problema no era un error aislado sino la ausencia de un canal claro de aviso entre el área de cocina y el área de comunicación. En lugar de resolverlo puertas adentro sin dejarlo explícito, la encargada de marketing y comunicación planteó directamente al encargado de cocina la necesidad de recibir los cambios en el menú (altas, bajas o modificaciones de producto) con anticipación y de forma sistemática, en vez de depender de un aviso informal.
Formular ese pedido con esa claridad no fue inmediato ni cómodo: implicaba señalar que el proceso existente no funcionaba, y que además requería un cambio de hábito por parte del área operativa del local. Sin embargo, encarar el problema de forma directa, en lugar de compensar el desorden sin comunicarlo, fue lo que permitió instalar un cambio real en el equipo: el lanzamiento de un producto nuevo pasó a ser un evento coordinado entre áreas, en lugar de una sucesión de avisos sueltos.
Este intercambio reafirma que el feedback radicalmente sincero no consiste en señalar un error para asignar responsabilidades, sino en nombrar con precisión qué necesita cambiar para que el proceso funcione, incluso cuando eso implica pedir explícitamente algo a otra área del equipo.


   ## Checklist de cumplimiento
- [x] Entrada de blog publicada y accesible públicamente
- [x] Documentación estructurada según plantilla (Contexto, Problema, Acciones, Aprendizajes)
- [x] Evidencia de control de versiones (repositorio + historial de commits)
- [x] Reflexión sobre feedback radicalmente sincero incluida
- [x] Lenguaje claro, sin jerga innecesaria, apto para audiencias técnicas y no técnicas
