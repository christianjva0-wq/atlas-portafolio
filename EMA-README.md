# EMA Psicología — demo

Concepto de demostración no oficial para Mtra. Erika Mota Alvarez. Un archivo autónomo: `ema-psicologia.html`; CSS, JavaScript e imágenes incluidos. Fuentes web opcionales con tipografías de respaldo. Sin dependencias JavaScript, cookies ni almacenamiento de solicitudes.

## Agenda

El calendario permite proponer una fecha futura hasta cinco meses después del mes actual, modalidad y horario preferido. La fecha actual se calcula en America/Tijuana. No representa disponibilidad real. La solicitud se revisa, se copia y se envía manualmente mediante el WhatsApp oficial. No se envía información automáticamente, no confirma reservas, no cobra y no recopila datos clínicos. Para reservas sincronizadas de producción hace falta autorización y acceso al calendario real de la profesional.

## Fuentes consultadas

- https://www.doctoralia.com.mx/erika-mota-alvarez/psicologo/tijuana
- https://linktr.ee/ema.psic
- https://www.instagram.com/ema_psicologia/
- WhatsApp oficial: https://wa.me/message/RLVHF2ZXZYRNB1

Datos: nombre, cédula 12291168, formación y domicilio de perfil profesional público. Imágenes procedentes de los perfiles públicos Doctoralia/Linktree. Se requiere aprobación de la profesional para lanzamiento oficial y uso definitivo de identidad e imágenes. No se reproducen testimonios de pacientes. Textos de presentación son propuesta editorial.

Calendly histórico no utilizado (404); Doctoralia no ofrece reserva online en los domicilios consultados. No se muestran tarifas ni horarios como información oficial.

## Accesibilidad y rendimiento

Diseño adaptable, campos etiquetados, estados de selección accesibles, foco visible, compatibilidad con movimiento reducido. Animaciones CSS y revelados observados una sola vez; sin WebGL, vídeos ni bucles continuos de JavaScript.

## Revisión 2 — escultura y profundidad

Esta revisión usa `ema-motion.js` (Three.js 0.170.0, licencia MIT adjunta) para renderizar una escultura paramétrica original: nudo de toro cerámico y aro metálico. Sin modelos descargados ni HDRI externos. La iluminación de entorno se genera con RoomEnvironment. El giro responde al scroll, puntero y botón; render bajo demanda, sin animación continua. DPR máximo 1.6 escritorio/1.25 móvil. Fallback CSS cuando WebGL no esté disponible. Control de pausa y prefers-reduced-motion.

Capítulo en perspectiva: 200svh escritorio/175svh móvil, pin nativo de un viewport, paneles con separación reversible al desplazarse. Mapa Google Maps integrado por domicilio; su disponibilidad depende de Google. Nuevo diseño de portada, agenda, retratos y contacto.
