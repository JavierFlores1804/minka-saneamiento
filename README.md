# Minka Saneamiento: Módulo de Alertas Tempranas y Monitoreo Participativo

Prototipo funcional desarrollado en el marco de la **Hackatón Transformagob 2026** para atender el desafío del Ministerio de Vivienda, Construcción y Saneamiento (MVCS): *"Más agua, menos retrasos: innovación para llevar servicios de agua y saneamiento a más familias de manera oportuna"*.

## 📋 Descripción del Proyecto
Minka Saneamiento es un componente digital modular e interoperable diseñado para mitigar, prevenir y visibilizar la paralización de obras de agua y alcantarillado en las zonas periféricas de Piura. La solución cruza indicadores de ejecución presupuestal y física con reportes comunitarios en tiempo real, desplegando un panel dinámico de semaforización orientada a la toma de decisiones preventivas por parte de los funcionarios del Estado.

## 🛠️ Arquitectura y Tecnologías
Este repositorio ha sido estructurado bajo los lineamientos del **Artículo 29 de la Ley de Gobierno Digital (Decreto Legislativo N.º 1412)**, garantizando el uso de estándares abiertos, interoperabilidad y componentes reutilizables sin dependencias propietarias:

- **Frontend:** HTML5, CSS3, JavaScript (ES6) - Interfaz de carga ultra ligera optimizada para entornos con conectividad móvil restringida.
- **Visualización Georreferenciada:** Leaflet.js / OpenStreetMap (Librerías de código abierto para el mapeo interactivo de proyectos).
- **Esquema de Ingesta (Simulado):** Arquitectura modular preparada para conectarse mediante servicios REST/APIs a las plataformas de datos abiertos del Estado (Infobras / SEACE).
- **Despliegue:** Configuración base lista para empaquetamiento en contenedores (Docker), asegurando la portabilidad del módulo en servidores institucionales.

## 📦 Estructura del Repositorio
```text
├── /data            # Datasets sintéticos y simulados de proyectos de agua en Piura (formatos JSON/CSV).
├── /src             # Código fuente de la interfaz del mapa y del formulario ciudadano de reportes.
├── LICENSE          # Licencia abierta MIT de uso público.
└── README.md        # Documentación técnica e instrucciones generales.
