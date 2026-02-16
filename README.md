# maquila-trazabilidad-mvp
# 🐟 MVP Trazabilidad de Maquila

Este repositorio contiene el **Producto Mínimo Viable (MVP)** para la digitalización del proceso de recepción de materia prima en plantas de procesamiento de pescado. 

El objetivo principal es demostrar la viabilidad de la **captura de datos en entornos de baja conectividad** y la transición de registros manuales (papel) a una infraestructura digital estructurada.

---

## 🚀 Propósito del MVP
Actualmente, la planta opera con más de 50 planillas manuales, lo que genera riesgos en la integridad de los datos y retrasos en la obtención de certificaciones internacionales. Este MVP resuelve:
* **Captura Offline:** Permite registrar datos sin conexión a internet.
* **Persistencia Local:** Los datos se guardan en el dispositivo hasta que haya red disponible.
* **Estandarización:** Elimina la ambigüedad de la letra a mano mediante formularios táctiles.

## 🛠️ Funcionalidades Actuales
- [x] **Formulario de Recepción:** Registro de especie, peso, temperatura (Punto Crítico) y estado sensorial.
- [x] **Almacenamiento Local (Local Storage):** Persistencia de datos incluso si se cierra el navegador o se apaga el dispositivo.
- [x] **Contador de Registros:** Visualización en tiempo real de los datos pendientes por sincronizar.
- [x] **Exportación de Respaldo:** Capacidad de descargar un archivo JSON con la data capturada para auditoría inmediata.

## 📈 Hoja de Ruta (Roadmap)
Para llevar este MVP a una solución de producción completa (Módulo MT), se contemplan las siguientes fases:

### Fase 1: Sincronización Automática (Próximamente)
* Integración con base de datos centralizada cuando se detecte conexión Wi-Fi.
* Módulo de impresión de etiquetas QR para trazabilidad de lotes.

### Fase 2: Control de Calidad y Procesos
* Digitalización de los formatos Q01 a Q59 mencionados en el mapa de procesos.
* Registro de mermas y subproductos aprovechables en tiempo real.

### Fase 3: Dashboard Gerencial
* Visualización de KPIs de rendimiento de planta.
* Integración de alertas de temperatura y puntos críticos de control.

---

## 📱 Instrucciones para la Prueba
1. Abra el siguiente enlace en una tablet o smartphone: `https://jorgeivanojeda.github.io/maquila-trazabilidad-mvp/`
2. Active el **Modo Avión** del dispositivo.
3. Realice varios registros de prueba.
4. Cierre la pestaña del navegador y vuelva a abrirla: Notará que el contador de registros se mantiene.
5. Desactive el Modo Avión para simular el fin de turno y presione "Descargar Backup".

---

## ⚙️ Especificaciones Técnicas
* **Tecnología:** HTML5 / JavaScript (ES6+).
* **Estilos:** Tailwind CSS (vía CDN).
* **Arquitectura:** PWA (Progressive Web App) con enfoque en *Offline-First*.
* **Despliegue:** GitHub Pages con certificado SSL (HTTPS).

---
**Desarrollado por el equipo de Proyecto Maquila 2026.**
