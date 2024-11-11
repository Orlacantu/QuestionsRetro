# QuestionsRetro
const preguntasPMI = [
  {
    pregunta: "¿Cuál de los siguientes documentos es publicado por el PMI y se considera una guía estándar para la gestión de proyectos?",
    opciones: [
      "A) PMBOK® Guide: Correcto. Es la guía estándar publicada por el PMI.",
      "B) Agile Manifesto: Incorrecto. No es publicado por el PMI, fue creado para guiar metodologías ágiles.",
      "C) Six Sigma Handbook: Incorrecto. Se enfoca en la mejora de procesos, no en gestión de proyectos.",
      "D) ISO 9001: Incorrecto. Es una norma de gestión de calidad, no de proyectos."
    ]
  },
  {
    pregunta: "¿Qué certificación del PMI está orientada principalmente a la gestión de proyectos ágiles?",
    opciones: [
      "A) PMP®: Incorrecto. Es para la gestión general de proyectos, no se enfoca en metodologías ágiles.",
      "B) CAPM®: Incorrecto. Es introductoria a la gestión de proyectos, no tiene un enfoque específico en ágil.",
      "C) PMI-ACP®: Correcto. Esta certificación se enfoca en metodologías ágiles.",
      "D) PgMP®: Incorrecto. Se centra en la gestión de programas, no en gestión ágil."
    ]
  },
  {
    pregunta: "Según el PMI, un proyecto es exitoso si cumple con los siguientes tres criterios, EXCEPTO:",
    opciones: [
      "A) Cumplir con el alcance del proyecto: Incorrecto. Cumplir con el alcance es esencial.",
      "B) Completar el proyecto a tiempo: Incorrecto. Terminar a tiempo es un requisito fundamental.",
      "C) Mantener una documentación exhaustiva: Correcto. No es un criterio fundamental según el PMI.",
      "D) Ejecutar el proyecto dentro del presupuesto: Incorrecto. Cumplir el presupuesto es un indicador clave de éxito."
    ]
  },
  {
    pregunta: "¿Cuál de las siguientes áreas de conocimiento del PMBOK® Guide está relacionada con el proceso de identificar, analizar y responder a factores que pueden afectar al proyecto?",
    opciones: [
      "A) Gestión del cronograma: Incorrecto. Se enfoca en planificar y controlar el tiempo.",
      "B) Gestión de riesgos: Correcto. Está orientada a la identificación y mitigación de riesgos.",
      "C) Gestión de calidad: Incorrecto. Asegura el cumplimiento de los estándares, no de riesgos.",
      "D) Gestión de adquisiciones: Incorrecto. Se refiere a la compra de bienes y servicios."
    ]
  },
  {
    pregunta: "En la metodología del PMI, el ciclo de vida de un proyecto generalmente incluye todas las siguientes fases, EXCEPTO:",
    opciones: [
      "A) Iniciación: Incorrecto. Es la primera fase donde se define y autoriza el proyecto.",
      "B) Planificación: Incorrecto. Se detallan los objetivos y el camino para alcanzarlos.",
      "C) Ejecución: Incorrecto. Aquí se llevan a cabo las actividades planificadas.",
      "D) Operaciones: Correcto. No es una fase del ciclo de vida del proyecto."
    ]
  }
];

const preguntasXP = [
  {
    pregunta: "¿Cuál de los siguientes principios es un pilar fundamental de Extreme Programming (XP)?",
    opciones: [
      "A) Documentación exhaustiva antes del desarrollo: Incorrecto. XP enfatiza la entrega rápida de software funcional.",
      "B) Codificación aislada sin revisiones: Incorrecto. XP promueve la colaboración y revisiones frecuentes.",
      "C) Retroalimentación continua: Correcto. Es uno de los pilares de XP.",
      "D) Desarrollo en cascada: Incorrecto. XP usa un enfoque iterativo y colaborativo."
    ]
  },
  {
    pregunta: "En XP, el concepto de 'programación en pareja' se refiere a:",
    opciones: [
      "A) Dos desarrolladores trabajando en tareas independientes en la misma sala: Incorrecto. Trabajan en la misma tarea.",
      "B) Un desarrollador y un tester colaborando para escribir pruebas unitarias: Incorrecto. Son dos desarrolladores escribiendo el mismo código.",
      "C) Dos desarrolladores trabajando juntos en la misma computadora: Correcto. Es el concepto de programación en pareja.",
      "D) Un desarrollador supervisando a otro: Incorrecto. Ambos colaboran activamente."
    ]
  },
  {
    pregunta: "¿Cuál de los siguientes roles NO es un rol oficial en un equipo de XP?",
    opciones: [
      "A) Programador: Incorrecto. Es un rol esencial en XP.",
      "B) Cliente: Incorrecto. El cliente aporta requisitos y feedback constante.",
      "C) Tester: Correcto. Aunque se realizan pruebas, no es un rol oficial.",
      "D) Coach: Incorrecto. Ayuda al equipo a seguir las prácticas de XP."
    ]
  },
  {
    pregunta: "En XP, ¿qué práctica fomenta la mejora continua del código y la reducción de la deuda técnica?",
    opciones: [
      "A) Refactorización: Correcto. Mejora el código y reduce la deuda técnica.",
      "B) Documentación detallada: Incorrecto. No reduce la deuda técnica directamente.",
      "C) Desarrollo en cascada: Incorrecto. No permite mejoras iterativas.",
      "D) Pruebas de aceptación: Incorrecto. Valida requisitos pero no mejora la estructura del código."
    ]
  },
  {
    pregunta: "Una de las prácticas centrales de XP es la 'integración continua'. ¿Qué significa esto?",
    opciones: [
      "A) Liberar una versión del software al cliente cada trimestre: Incorrecto. No implica liberaciones periódicas.",
      "B) Integrar y probar el código frecuentemente: Correcto. Es el significado de integración continua.",
      "C) Implementar todas las características antes de realizar pruebas: Incorrecto. Las pruebas son constantes.",
      "D) Crear un entorno separado para cada integrante del equipo: Incorrecto. Se usa un entorno compartido."
    ]
  }
];

console.log(preguntasPMI);
console.log(preguntasXP);
const preguntasScrum = [
  {
    pregunta: "¿Qué es Scrum?",
    opciones: [
      "Un marco ágil para gestionar proyectos. ✅",
      "Un tipo de lenguaje de programación.",
      "Un software de desarrollo web.",
      "Una metodología tradicional para gestión de proyectos."
    ]
  },
  {
    pregunta: "¿Cuál es el principal rol del Scrum Master?",
    opciones: [
      "Facilitar el proceso Scrum y eliminar impedimentos. ✅",
      "Tomar todas las decisiones del equipo.",
      "Escribir el código del proyecto.",
      "Aprobar las entregas finales."
    ]
  },
  {
    pregunta: "¿Qué es un Sprint en Scrum?",
    opciones: [
      "Un período de tiempo fijo para completar un incremento del producto. ✅",
      "Una lista de tareas pendientes para el equipo.",
      "Un documento que describe el proyecto.",
      "Una herramienta de control de calidad."
    ]
  },
  {
    pregunta: "¿Qué artefacto de Scrum contiene todo el trabajo pendiente para el proyecto?",
    opciones: [
      "Product Backlog. ✅",
      "Sprint Backlog.",
      "Increment.",
      "Burndown Chart."
    ]
  },
  {
    pregunta: "¿Quién es responsable de maximizar el valor del producto en Scrum?",
    opciones: [
      "El Product Owner. ✅",
      "El Scrum Master.",
      "El Desarrollador.",
      "El Cliente."
    ]
  }
];

const preguntasKanban = [
  {
    pregunta: "¿Cuál es el principal objetivo del sistema Kanban?",
    opciones: [
      "Visualizar el flujo de trabajo y mejorar la eficiencia. ✅",
      "Maximizar las reuniones diarias.",
      "Aumentar la cantidad de tareas en curso al mismo tiempo.",
      "Implementar un control jerárquico estricto."
    ]
  },
  {
    pregunta: "¿Cuál de los siguientes elementos es esencial en un tablero Kanban?",
    opciones: [
      "Columnas que representan las etapas del flujo de trabajo. ✅",
      "Un cronómetro para cada tarea.",
      "Un gráfico de barras para medir ganancias financieras.",
      "Un botón para aprobar automáticamente las tareas completadas."
    ]
  },
  {
    pregunta: "¿Qué significa el término 'WIP' en Kanban?",
    opciones: [
      "Work in Progress (Trabajo en Progreso). ✅",
      "Workflow in Process (Flujo de Trabajo en Proceso).",
      "Work Improvement Plan (Plan de Mejora Laboral).",
      "Weekly Incremental Progress (Progreso Incremental Semanal)."
    ]
  },
  {
    pregunta: "¿Cuál es una de las reglas clave de Kanban?",
    opciones: [
      "Limitar la cantidad de trabajo en progreso. ✅",
      "Completar tareas sin seguir prioridades.",
      "Evitar cambios en el proceso de trabajo.",
      "Prohibir la colaboración entre equipos."
    ]
  },
  {
    pregunta: "¿De dónde proviene el concepto de Kanban?",
    opciones: [
      "De la filosofía ágil Scrum.",
      "De las prácticas de gestión de producción de Toyota. ✅",
      "De los modelos de gestión de empresas de Silicon Valley.",
      "De teorías modernas de inteligencia artificial."
    ]
  }
];

const preguntasPMI = [
  {
    pregunta: "¿Cuál de los siguientes documentos es publicado por el PMI y se considera una guía estándar para la gestión de proyectos?",
    opciones: [
      "PMBOK® Guide ✅",
      "Agile Manifesto",
      "Six Sigma Handbook",
      "ISO 9001"
    ]
  },
  {
    pregunta: "¿Qué certificación del PMI está orientada principalmente a la gestión de proyectos ágiles?",
    opciones: [
      "PMP® (Project Management Professional)",
      "CAPM® (Certified Associate in Project Management)",
      "PMI-ACP® (Agile Certified Practitioner) ✅",
      "PgMP® (Program Management Professional)"
    ]
  },
  {
    pregunta: "Según el PMI, un proyecto es exitoso si cumple con los siguientes tres criterios, EXCEPTO:",
    opciones: [
      "Cumplir con el alcance del proyecto",
      "Completar el proyecto a tiempo",
      "Maximizar la satisfacción del cliente ✅",
      "Ejecutar el proyecto dentro del presupuesto"
    ]
  },
  {
    pregunta: "¿Cuál de las siguientes áreas de conocimiento del PMBOK® Guide está relacionada con el proceso de identificar, analizar y responder a factores que pueden afectar al proyecto?",
    opciones: [
      "Gestión del cronograma",
      "Gestión de riesgos ✅",
      "Gestión de calidad",
      "Gestión de adquisiciones"
    ]
  },
  {
    pregunta: "En la metodología del PMI, el ciclo de vida de un proyecto generalmente incluye todas las siguientes fases, EXCEPTO:",
    opciones: [
      "Iniciación",
      "Planificación",
      "Ejecución",
      "Despliegue continuo ✅"
    ]
  }
];

console.log(preguntasScrum);
console.log(preguntasKanban);
console.log(preguntasPMI);
