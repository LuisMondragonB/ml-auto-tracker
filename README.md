🚗 MercadoLibre Auto Tracker
App de escritorio que monitorea precios de autos en MercadoLibre y notifica cuando encuentra ofertas.
Características

✅ Búsqueda automática cada 3 horas
✅ Notificaciones de escritorio cuando hay ofertas
✅ Base de datos local SQLite
✅ Interfaz gráfica con Electron + React
✅ Se minimiza al system tray
✅ Historial de precios con gráficos

Instalación
bashgit clone https://github.com/tu-usuario/ml-auto-tracker.git
cd ml-auto-tracker
npm install
npm start
Estructura del Proyecto
.
├── src/
│   ├── main/
│   │   ├── index.js        # Proceso principal Electron
│   │   ├── database.js     # SQLite local
│   │   ├── scraper.js      # Web scraping con Puppeteer
│   │   └── scheduler.js    # Tareas programadas
│   └── renderer/
│       ├── index.html
│       ├── App.jsx         # Interfaz React
│       └── styles.css
├── package.json
└── README.md
