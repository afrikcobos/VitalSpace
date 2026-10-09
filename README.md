# 🏥 VitalSpace — MedTech Web Platform

**VitalSpace** es una plataforma web moderna diseñada para la gestión integral de servicios de salud, perfiles médicos, reserva de citas y promociones clínicas. El proyecto combina estándares visuales de **UI/UX centrados en el paciente** con una arquitectura web nativa limpia, accesible y responsiva.

![Netlify Status](https://img.shields.io/badge/Deploy-Netlify-00C7B7?style=flat-square&logo=netlify)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## Demo en Vivo
Puedes explorar la plataforma desplegada en tiempo real:
 **[VitalSpace en Netlify](https://vitalspacex.netlify.app/)**

---

##  Características de Diseño & UI/UX

- **Diseño Limpio y Profesional:** Uso de la paleta institucional médica con tonos azules, neutros y acentos para guiar la atención del usuario sin fatiga visual.
- **Sistema de Variables CSS (`:root`):** Centralización de colores, sombras (`box-shadow`), bordes redondeados tipo *Pill* y escala tipográfica (Google Font *Nunito*).
- **Layout Responsivo:** Maquetación flexible construida con **CSS Grid** y **Flexbox**, adaptable desde smartphones hasta pantallas de escritorio de alta resolución.
- **Microinteracciones y Feedback:** Animaciones suaves al pasar el cursor (`hover`), estados de botones y tarjetas interactivas para promociones médicas y laboratorios.
- **Sin Scroll Vertical Innecesario (*Dashboard View*):** Optimización del espacio en pantalla para mostrar la información clave sin fricción de navegación.

---

## Tecnologías Utilizadas

- **HTML5 Semántico:** Estructura limpia y accesible.
- **CSS3 Vanilla:** Arquitectura CSS modular sin librerías externas para máximo rendimiento e independencia.
- **JavaScript ES6+:** Manipulación dinámica del DOM (selección de horarios, conmutación de pestañas y modales).
- **Git & GitHub:** Control de versiones e integración continua.

---

## Estructura del Proyecto

```text
VitalSpace/
├── index.html              # Pantalla de bienvenida y landing
├── login.html              # Autenticación y selección de roles
├── perfilUsuario.html      # Dashboard del usuario y resumen de citas
├── doctores.html           # Directorio y filtro de médicos especialistas
├── clinicas.html           # Directorio de clínicas por estado
├── perfil-clinica.html     # Perfil detallado de clínica/laboratorio y ofertas
├── detalle-oferta.html     # Tarjeta detallada de promociones médicas
├── agendar-cita.html       # Selección de fechas y bloques de horarios
├── pagar-servicio.html     # Módulo y pasarela de pago simplificada
├── style.css               # Hoja de estilos centralizada y variables
└── README.md               # Documentación del proyecto