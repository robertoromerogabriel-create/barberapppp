# LEGACY BARBER – Club & Barbershop
Gestor de turnos y administración. Sitio estático (un único `index.html`).
- Datos persistidos en localStorage (navegador). Ver sección "Backend" abajo.
- Deploy: Vercel (Framework Preset: Other, sin build, sin output directory).
## Backend
`apiGet/apiPost/apiPut/apiDelete` están al inicio del <script>. Para multi-dispositivo, reemplazar sus cuerpos por `fetch('/api/<coleccion>')`.
