# ¡Hola! Soy Martín Mazini 👋

**Analista en Informática** (2026) y estudiante de 4.° año de **Ingeniería en Informática** en UADE. Me apasiona el análisis de datos, la automatización de sistemas, el desarrollo de software y el *sports analytics*. 

- 🎯 En búsqueda de oportunidades como **Data Analyst** o **Desarrollador Backend / Full Stack**.
- 📊 Enfocado en transformar datos complejos en decisiones estratégicas y construir arquitecturas escalables.

---

### 🛠️ Stack Tecnológico y Herramientas

**Lenguajes y Análisis de Datos**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks y Desarrollo**
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)

**Bases de Datos (SQL, NoSQL & Grafos) y Cloud**
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Apache Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=for-the-badge&logo=apache-cassandra&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 🚀 Proyectos Destacados

<table>
  <thead>
    <tr>
      <th colspan="2" align="left">
        🏁 <b>Ecosistema GrandPrix Tracker</b> <i>(2026) — Arquitectura distribuida & Microservicios</i><br/>
        <sub>Plataforma integral para la gestión y compra de paquetes de Fórmula 1 (entradas, vuelos y alojamiento). Diseñada con un backend central en <b>Spring Boot</b>, persistencia en <b>Supabase</b>, patrones de diseño (<i>Adapter, Observer, Strategy</i>) y manejo estandarizado de errores bajo <b>RFC 9457</b>.</sub>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="32%">
        🎟️ <a href="https://github.com/MartinMF24/microservice_ticketing_gp"><b>Microservicio de Ticketería</b></a><br/>
        <code>Microservice</code> <code>Supabase</code> <code>Cron</code>
      </td>
      <td>
        Puente de integración para la gestión de entradas de cada Gran Premio. Sincroniza el inventario disponible hacia <b>Supabase</b> mediante <i>cron jobs</i> automatizados y ejecuta validaciones sincrónicas de stock y reservas durante el <i>checkout</i>.
      </td>
    </tr>
    <tr>
      <td>
        🧼 <a href="https://github.com/MartinMF24/Soap_Ticketing_F1"><b>Ticketera Legacy SOAP</b></a><br/>
        <code>SOAP</code> <code>XML / WSDL</code> <code>Legacy</code>
      </td>
      <td>
        Sistema externo simulado basado en protocolo <b>SOAP</b> que actúa como proveedor oficial de tickets de F1. Administra la emisión, bloqueo y validación transaccional de entradas consumidas por el microservicio de ticketería.
      </td>
    </tr>
    <tr>
      <td>
        ✈️ <a href="https://github.com/MartinMF24/MicroService_Booking_flights_GT"><b>Microservicio de Vuelos</b></a><br/>
        <code>ETL</code> <code>API Integration</code> <code>Supabase</code>
      </td>
      <td>
        Servicio independiente que opera como proceso <b>ETL</b> (<i>Extract, Transform, Load</i>) consumiendo APIs externas de aerolíneas para normalizar e inyectar rutas, escalas y tarifas en <b>Supabase</b> bajo demanda, evitando latencias al usuario final.
      </td>
    </tr>
    <tr>
      <td>
        🏨 <a href="https://github.com/MartinMF24/MicroService_Booking_hotels_GT"><b>Microservicio de Hoteles</b></a><br/>
        <code>ETL</code> <code>API Integration</code> <code>Supabase</code>
      </td>
      <td>
        Microservicio <b>ETL</b> dedicado a la extracción y actualización de disponibilidad hotelera cercana a los circuitos. Mantiene la consistencia de precios y habitaciones en la base de datos central de forma desacoplada.
      </td>
    </tr>
  </tbody>
</table>

* 🏎️ **[F1 Comparator](https://github.com/mate58/f1-comparator)** *(2026)*: Proyecto de análisis de datos, minería y *clustering* desarrollado durante 6 meses con **Python y Pandas** para predecir el rendimiento de pilotos de Fórmula 1 utilizando datasets históricos.
<table>
  <thead>
    <tr>
      <th colspan="2" align="left">
        📱 <b>PoleBid</b> <i>(2026) — Aplicación Móvil de Subastas en Tiempo Real (6 meses)</i><br/>
        <sub>Desarrollo <i>end-to-end</i> en un equipo ágil de 4 personas para la gestión y participación interactiva en subastas móviles, abarcando desde el prototipado UI/UX en <b>Figma</b> hasta la arquitectura cliente-servidor y sincronización en vivo.</sub>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="32%">
        🎨 <a href="https://github.com/ericzager0/PoleBid_FRONT"><b>PoleBid Mobile (Frontend)</b></a><br/>
        <code>React Native</code> <code>Android Studio</code> <code>Figma</code>
      </td>
      <td>
        Aplicación móvil nativa que implementa 10 pantallas interactivas diseñadas en <b>Figma</b>. Gestiona la navegación, el catálogo de lotes, el flujo de pujas en vivo y las actualizaciones dinámicas de estado para el usuario.
      </td>
    </tr>
    <tr>
      <td>
        ⚙️ <a href="https://github.com/ericzager0/PoleBid"><b>PoleBid Server (Backend)</b></a><br/>
        <code>Backend API</code> <code>Supabase</code> <code>Real-Time</code>
      </td>
      <td>
        Servicios de backend e infraestructura de datos apoyados en <b>Supabase</b>. Administra la lógica de negocio de las subastas, la autenticación de usuarios, el cierre de lotes y la sincronización en tiempo real de las ofertas entre clientes.
      </td>
    </tr>
  </tbody>
</table>

* 🎓 **[ProfeRank](https://github.com/mate58/ProfeRank)** *(2025)*: Plataforma web colaborativa para la calificación de profesores universitarios (desarrollo de 4 meses con **Firebase y Supabase**).
---

### 📈 Mis Estadísticas y Rachas en GitHub

<div align="center">
  <!-- Racha de días pusheando y mejor racha histórica -->
  <img src="https://streak-stats.demolab.com?user=MartinMF24&theme=tokyonight&hide_border=true&locale=es" height="165" alt="GitHub Streak" />
</div>

<br/>

<div align="center">
  <!-- Estadísticas generales de GitHub -->
  <img src="https://github-readme-stats.vercel.app/api?username=MartinMF24&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165" alt="GitHub Stats" />
  <!-- Porcentaje de lenguajes más usados -->
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MartinMF24&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" height="165" alt="Top Languages" />
</div>

---

### 📫 Contacto

<div align="left">
  <a href="https://www.linkedin.com/in/martin-mazini-fanti/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:martinmazini@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>
