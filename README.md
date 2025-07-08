# Propuesta_Portafolio
Este trabajo tiene como objetivo crear una pagina web ficticia  utilizando una plantilla de boostsrap


---

## Descripción del proyecto

### Menús principales

- **Inicio**  
  Presentación personal y bienvenida.

- **Trayectoria**  
  Formación académica y experiencia profesional.

- **Lenguajes**  
  Habilidades y lenguajes de programación.

- **Proyectos**  
  Galería de proyectos desarrollados, con tecnologías utilizadas.

- **Contacto**  
  Formulario para enviar mensajes y redes sociales.

---

### Plantilla y tecnologías

- **Bootstrap 5**  
- **HTML5 y CSS3 personalizados**
- **JavaScript**
- **Bootstrap Icons**

---

### Detalle de secciones

- **Inicio**:  
  Banner con foto, nombre, especialidad y botones de contacto rápido (email, GitHub, LinkedIn).

- **Trayectoria**:  
  - **Formación Académica**:  
    - Instituto Tecnológico de Oaxaca – Ingeniería en Sistemas Computacionales (2019–2024)
    - COBAO 44 – Técnico en TICS (2016–2019)
    - Secundaria Técnica 20 (2013–2016)
  - **Experiencia Profesional**:  
    - Google – Desarrollador de Software (2023–Actualidad)
    - Globant – Full Stack Developer (2022–2023)
    - IBM México – Backend Developer (2021–2022)
    - Megacable Oaxaca – Soporte Técnico y Desarrollador Jr. (2020–2021)

- **Lenguajes y skills**:  
  Barras de progreso para JavaScript, Python, Java (Spring Boot), PHP, HTML, CSS, Bootstrap, MySQL, UI/UX, etc.

- **Proyectos destacados**:  
  - App de Gestión y Recordatorio de Medicación
  - Punto de Venta Panadería Bambi Oaxaca
  - Microservicios para Google
  - API REST para Reservaciones
  - Plataforma de Renta de Viviendas “RentNow”
  - Dashboard para Monitoreo Escolar
  - Chatbot para Atención Médica Virtual
  - Portal de Noticias Locales “OaxacaPress”

- **Contacto**:  
  Formulario visual para contacto y enlaces a correo, GitHub y LinkedIn.

---
## Capturas de Pantalla

### Vista principal  
![Vista principal](./Captura%20de%20pantalla%202025-07-07%20081444.png)

### Sección Proyectos  
![Sección Proyectos](./Captura%20de%20pantalla%202025-07-07%20081520.png)

### Formulario de Contacto  
![Formulario de Contacto](./Captura%20de%20pantalla%202025-07-07%20081543.png)


*(Puedes reemplazar estos nombres de archivo por los de tus propias capturas.)*

---

## GitHub Pages

El portafolio está publicado en **GitHub Pages**:  
👉 [Ver portafolio en línea](https://josemanuelcruzcristales-777.github.io/Propuesta_Portafolio/)

---

## Notas Importantes
```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>José Manuel Cruz Cristales | Portafolio</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.css">
  <link rel="stylesheet " href="css/estilo1.css">
  
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg mb-0">
  <div class="container">
    <a class="navbar-brand" href="#">JMCC</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mainNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="mainNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#inicio">Inicio</a></li>
        <li class="nav-item"><a class="nav-link" href="#trayectoria">Trayectoria</a></li>
        <li class="nav-item"><a class="nav-link" href="#skills">Lenguajes</a></li>
        <li class="nav-item"><a class="nav-link" href="#proyectos">Proyectos</a></li>
        <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero" id="inicio">
  <div class="container text-center">
    <img src="img/perfil.jpg" alt="Foto Perfil">
    <h1>José Manuel Cruz Cristales</h1>
    <p class="mb-3">Ingeniero en Sistemas Computacionales | Desarrollador de Software | Especialista en TICS</p>
    <div>
      <a href="mailto:manu@email.com" class="btn btn-light btn-sm rounded-pill me-2"><i class="bi bi-envelope-fill"></i> Email</a>
      <a href="https://github.com/tuusuario" class="btn btn-light btn-sm rounded-pill me-2" target="_blank"><i class="bi bi-github"></i> GitHub</a>
      <a href="https://linkedin.com/in/tuusuario" class="btn btn-light btn-sm rounded-pill" target="_blank"><i class="bi bi-linkedin"></i> LinkedIn</a>
    </div>
  </div>
</section>

<!-- TRAYECTORIA -->
<!-- TRAYECTORIA ACADÉMICA Y PROFESIONAL -->
<section class="container main-content" id="trayectoria">
  <div class="section-title">Trayectoria Académica y Profesional</div>
  <div class="row">
    <!-- Formación Académica -->
    <div class="col-md-6 mb-4">
      <h4 class="mb-3" style="color: #e9b000;">Formación Académica</h4>
      <ul class="timeline list-unstyled">
        <li class="mb-4">
          <span class="fw-bold">2019 – 2024</span><br>
          <b>Instituto Tecnológico de Oaxaca</b><br>
          Ingeniería en Sistemas Computacionales<br>
          Especialidad: Desarrollo de Software con Tecnologías Actuales
        </li>
        <li class="mb-4">
          <span class="fw-bold">2016 – 2019</span><br>
          <b>COBAO Plantel 44 San Antonio de la Cal</b><br>
          Técnico en TICS (Tecnologías de la Información y Comunicación)
        </li>
        <li class="mb-4">
          <span class="fw-bold">2013 – 2016</span><br>
          <b>Secundaria Técnica 20, Oaxaca</b><br>
          Certificado de Estudios Secundarios
        </li>
      </ul>
    </div>
    <!-- Formación Profesional -->
    <div class="col-md-6 mb-4">
      <h4 class="mb-3" style="color: #e9b000;">Experiencia Profesional</h4>
      <ul class="timeline list-unstyled">
        <li class="mb-4">
          <span class="fw-bold">2023 – Actualidad</span><br>
          <b>Desarrollador de Software para Google <span class="text-muted" style="font-weight:normal">(Proyecto externo)</span></b><br>
          Desarrollo de microservicios y aplicaciones web escalables (Spring Boot y React).
        </li>
        <li class="mb-4">
          <span class="fw-bold">2022 – 2023</span><br>
          <b>Full Stack Developer – Globant</b><br>
          Creación de plataformas para e-commerce y dashboards de análisis en tiempo real (Node.js y React).
        </li>
        <li class="mb-4">
          <span class="fw-bold">2021 – 2022</span><br>
          <b>Desarrollador Backend – IBM México</b><br>
          Automatización de procesos y servicios internos en Java y Python. Integración de APIs corporativas.
        </li>
        <li class="mb-4">
          <span class="fw-bold">2020 – 2021</span><br>
          <b>Soporte Técnico y Desarrollador Jr. – Megacable Oaxaca</b><br>
          Atención a usuarios y desarrollo de herramientas internas en PHP y MySQL.
        </li>
      </ul>
    </div>
  </div>
</section>


<!-- LENGUAJES Y SKILLS -->
<section class="container main-content" id="skills">
  <div class="section-title">Lenguajes de Programación & Habilidades</div>
  <div class="row g-4">
    <div class="col-md-6">
      <label>JavaScript</label>
      <div class="progress mb-2"><div class="progress-bar bg-warning" style="width:85%">Avanzado</div></div>
      <label>Python</label>
      <div class="progress mb-2"><div class="progress-bar bg-primary" style="width:75%">Intermedio</div></div>
      <label>Java (Spring Boot)</label>
      <div class="progress mb-2"><div class="progress-bar bg-success" style="width:75%">Intermedio</div></div>
      <label>PHP</label>
      <div class="progress mb-2"><div class="progress-bar bg-info" style="width:65%">Intermedio</div></div>
    </div>
    <div class="col-md-6">
      <label>HTML5 & CSS3</label>
      <div class="progress mb-2"><div class="progress-bar bg-success" style="width:90%">Avanzado</div></div>
      <label>Bootstrap</label>
      <div class="progress mb-2"><div class="progress-bar bg-danger" style="width:85%">Avanzado</div></div>
      <label>MySQL</label>
      <div class="progress mb-2"><div class="progress-bar bg-success" style="width:70%">Intermedio</div></div>
      <label>UI/UX</label>
      <div class="progress mb-2"><div class="progress-bar bg-warning" style="width:68%">Intermedio</div></div>
    </div>
  </div>
</section>

<!-- PROYECTOS -->


<!-- PROYECTOS -->
<section class="container main-content" id="proyectos">
  <div class="section-title">Proyectos de Desarrollo</div>
  <div class="row g-4">

    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-capsule"></i> App de Gestión y Recordatorio de Medicación</h5>
          <p class="card-text">Aplicación móvil para el tratamiento y recordatorio de la medicación para adultos mayores. Permite registrar horarios, tipos de medicamento y notificaciones automáticas.<br>
          <span class="badge bg-info text-dark">React Native</span>
          <span class="badge bg-warning text-dark">Firebase</span>
          <span class="badge bg-success">Android/iOS</span></p>
        </div>
      </div>
    </div>

    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-shop"></i> Punto de Venta Panadería Bambi Oaxaca</h5>
          <p class="card-text">Desarrollo de un sistema de punto de venta personalizado para la panadería Bambi, Oaxaca. Incluye inventario, caja, reportes y gestión de clientes. Uso de Python, Spring Boot y MySQL.<br>
          <span class="badge bg-success">Python</span>
          <span class="badge bg-secondary">Spring Boot</span>
          <span class="badge bg-info text-dark">MySQL</span></p>
        </div>
      </div>
    </div>

    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-google"></i> Microservicios para Google</h5>
          <p class="card-text">Participación en equipo para desarrollar microservicios y soluciones en la nube, integrando APIs RESTful y componentes escalables.<br>
          <span class="badge bg-secondary">Spring Boot</span>
          <span class="badge bg-warning text-dark">Java</span>
          <span class="badge bg-info text-dark">Google Cloud</span></p>
        </div>
      </div>
    </div>

    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-terminal"></i> API REST para Reservaciones</h5>
          <p class="card-text">API RESTful para la gestión de reservaciones de restaurantes, autenticación JWT y roles de usuario.<br>
          <span class="badge bg-dark">Node.js</span>
          <span class="badge bg-success">Express</span>
          <span class="badge bg-info text-dark">MongoDB</span></p>
        </div>
      </div>
    </div>

    <!-- Proyecto 5 -->
    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-house"></i> Plataforma de Renta de Viviendas “RentNow”</h5>
          <p class="card-text">Desarrollo de una plataforma web para la búsqueda y renta de viviendas en Oaxaca, con filtros inteligentes y panel de administración.<br>
          <span class="badge bg-success">Laravel</span>
          <span class="badge bg-warning text-dark">JavaScript</span>
          <span class="badge bg-info text-dark">Bootstrap</span></p>
        </div>
      </div>
    </div>

    <!-- Proyecto 6 -->
    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-bar-chart-steps"></i> Dashboard para Monitoreo Escolar</h5>
          <p class="card-text">Plataforma web para visualizar asistencia y calificaciones de alumnos, panel docente y notificaciones automáticas.<br>
          <span class="badge bg-warning text-dark">Bootstrap</span>
          <span class="badge bg-secondary">Python</span>
          <span class="badge bg-info text-dark">Flask</span></p>
        </div>
      </div>
    </div>

    <!-- Proyecto 7 -->
    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-robot"></i> Chatbot para Atención Médica Virtual</h5>
          <p class="card-text">Desarrollo de un chatbot inteligente para responder dudas básicas de salud y agendar citas, con integración a WhatsApp.<br>
          <span class="badge bg-success">Python</span>
          <span class="badge bg-info text-dark">Dialogflow</span>
          <span class="badge bg-dark">Twilio API</span></p>
        </div>
      </div>
    </div>

    <!-- Proyecto 8 -->
    <div class="col-md-6">
      <div class="card h-100">
        <div class="card-body">
          <h5 class="card-title"><i class="bi bi-globe2"></i> Portal de Noticias Locales “OaxacaPress”</h5>
          <p class="card-text">Desarrollo de un portal informativo con panel de periodistas, editor visual y sección de comentarios en tiempo real.<br>
          <span class="badge bg-info text-dark">PHP</span>
          <span class="badge bg-warning text-dark">JavaScript</span>
          <span class="badge bg-primary">MySQL</span></p>
        </div>
      </div>
    </div>

  </div>
</section>


<!-- CONTACTO -->
<section class="container main-content" id="contacto">
  <div class="section-title">Contacto</div>
  <div class="row justify-content-center">
    <div class="col-md-6">
      <form>
        <div class="mb-3">
          <label for="nombre" class="form-label">Nombre</label>
          <input type="text" class="form-control" id="nombre" placeholder="Escribe tu nombre">
        </div>
        <div class="mb-3">
          <label for="correo" class="form-label">Correo electrónico</label>
          <input type="email" class="form-control" id="correo" placeholder="ejemplo@email.com">
        </div>
        <div class="mb-3">
          <label for="mensaje" class="form-label">Mensaje</label>
          <textarea class="form-control" id="mensaje" rows="4" placeholder="Escribe tu mensaje"></textarea>
        </div>
        <button type="submit" class="btn btn-primary w-100" disabled>Enviar (Demo Visual)</button>
      </form>
      <div class="text-center mt-3 social-icons">
        <a href="mailto:manu@email.com" title="Correo"><i class="bi bi-envelope-fill"></i></a>
        <a href="https://github.com/tuusuario" target="_blank" title="GitHub"><i class="bi bi-github"></i></a>
        <a href="https://linkedin.com/in/tuusuario" target="_blank" title="LinkedIn"><i class="bi bi-linkedin"></i></a>
      </div>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer class="footer">
  <div>© 2025 José Manuel Cruz Cristales | Portafolio Profesional</div>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```
## Recursos Utilizados

- **HTML5**: estructura semántica de la página.
- **Bootstrap 5**: estilos, grillas responsivas y componentes modernos.
- **Bootstrap Icons**: iconos para botones y secciones.
- **CSS personalizado (`estilo1.css`)**: colores y detalles visuales propios.
- **Imágenes**: foto de perfil y logotipos en `/img`.

---

## Secciones Principales

- **Navbar**: menú de navegación fijo y responsivo.
- **Inicio**: presentación personal con enlaces de contacto.
- **Trayectoria**: formación académica y experiencia profesional.
- **Lenguajes y habilidades**: barras de progreso para skills.
- **Proyectos**: tarjetas visuales con mis desarrollos destacados.
- **Contacto**: formulario básico y enlaces rápidos.
- **Footer**: derechos reservados.

---

## Propiedades clave

- **Clases Bootstrap**: para layout, botones, cards y responsividad.
- **Atributos HTML**: `alt`, `placeholder`, `required`, `target="_blank"`.
- **IDs**: para navegación entre secciones.

---
