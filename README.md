lonar el repositorio
git clone https://github.com/usuario/mercantilismo-global.git
cd mercantilismo-global

2. Instalar dependencias
npm install

3. Variables de entorno

Crea un archivo .env en la raíz con los valores requeridos:

DATABASE_URL=postgres://usuario:password@localhost:5432/mercantilismo
JWT_SECRET=supersecreto
PORT=3000

4. Ejecutar el entorno de desarrollo
npm run dev

5. Construir para producción
npm run build
npm start

📁 Estructura del proyecto
/src
  /client       # Frontend React
  /server       # API Rest Node.js
  /database     # Migraciones y seeds
  /visuals      # Gráficos, mapas y simulaciones
/public
.env
README.md

🗺️ Funcionalidades clave del sistema mercantilista

Índice de Competitividad Mercantilista (ICM): métrica exclusiva del proyecto.

Alertas de déficit comercial: el sistema detecta desequilibrios significativos.

Historial de tratados comerciales: exploración cronológica interactiva.

Rutas marítimas y terrestres: visualización dinámica en el mapa.

🤖 API REST (Resumen)
Método	Ruta	Descripción
GET	/api/countries	Lista todos los países
GET	/api/trade/:pair	Devuelve relaciones comerciales entre dos países
POST	/api/simulate	Ejecuta una simulación mercantilista
GET	/api/history/:country	Información histórica del país
🧪 Tests
npm run test


Incluye pruebas unitarias para el backend y pruebas de integración para el frontend.

🧑‍💻 Contribuciones

Las contribuciones son bienvenidas.
Por favor, abre un issue o envía un pull request con una explicación clara de tus cambios.

📜 Licencia

Este proyecto ficticio utiliza la licencia MIT. Puedes usarlo y modificarlo libremente.

Si quieres, puedo generar también:

✅ Logo del proyecto
✅ Documentación más técnica
✅ Mockups de la web
✅ Arquitectura del sistema
✅ Un pitch o presentación
