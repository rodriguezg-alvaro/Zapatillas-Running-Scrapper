# Zapatillas-Running-Scrapper

Herramienta de *web scraping* para recopilar, comparar y analizar información sobre **zapatillas de running** de distintas tiendas online.

## 🎯 Objetivo

Encontrar la mejor zapatilla al mejor precio sin tener que revisar decenas de webs a mano. El proyecto extrae automáticamente los datos de producto, los normaliza y los guarda en un formato fácil de analizar.

## ✨ Funcionalidades

- 🔍 **Extracción de datos** de tiendas de running: marca, modelo, precio, descuento, tallas disponibles, peso, drop, tipo de pisada y valoraciones.
- 💶 **Comparativa de precios** del mismo modelo entre distintas tiendas.
- 📉 **Seguimiento histórico** de precios para detectar bajadas y ofertas.
- 🧹 **Limpieza y normalización** de los datos (nombres de modelos, tallas, monedas).
- 💾 **Exportación** a CSV / Excel / JSON para su análisis posterior.
- 🔔 *(Próximamente)* Alertas cuando un modelo baja de un precio objetivo.

## 🛠️ Tecnologías

- **Python 3**
- `requests` + `BeautifulSoup` para páginas estáticas
- `Selenium` / `Playwright` para páginas con contenido dinámico
- `pandas` para el tratamiento y análisis de los datos

## 📁 Estructura del proyecto

```
Scrapear_Zapatillas_Running/
├── scrapers/        # Un scraper por tienda
├── data/            # Datos extraídos (CSV, JSON)
├── notebooks/       # Análisis exploratorio
├── utils/           # Funciones de limpieza y helpers
├── main.py          # Punto de entrada
├── requirements.txt
└── README.md
```

## 🚀 Instalación y uso

```bash
git clone https://github.com/<tu-usuario>/Scrapear_Zapatillas_Running.git
cd Scrapear_Zapatillas_Running
pip install -r requirements.txt
python main.py
```

## ⚖️ Uso responsable

Este proyecto tiene fines educativos y de uso personal. Respeta siempre los `robots.txt` y los términos de uso de cada web, limita la frecuencia de las peticiones y no utilices los datos con fines comerciales sin permiso.

## 🤝 Contribuciones

¿Quieres añadir una nueva tienda o mejorar un scraper? ¡Los *pull requests* son bienvenidos!

## 📄 Licencia

MIT
