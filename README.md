# GraffSystem
Juego multijugador de Roblox centrado en **graffiti urbano** sobre **trenes y entornos de ciudad**, con un sistema de pintura avanzado, cámara inmersiva y un **sistema profesional de reporte de errores y exploits**.
## 🧩 Características principales

### 🖌️ Sistema de pintura (Graffiti System)
- Pintura en tiempo real sobre trenes y estructuras urbanas
- Diferentes tipos de spray (materiales, tamaños, estilos)
- Control de distancia, suavizado y precisión
- Eraser con efecto visual tipo *halo* (sin borrar agresivo)
- Compresión y gestión eficiente de trazos
- Compatible con móvil, PC y VR (cámara híbrida)

### 🎥 Cámara inmersiva
- Cámara dinámica tipo *focus mode*
- Bloqueo automático al pintar
- Suavizado configurable
- Compatible con touch / mouse / gamepad

### 📸 Sistema de cámara y álbum (en progreso)
- Herramienta de cámara equipable
- Captura de fotos dentro del juego
- Álbum personal por jugador
- Galería pública (opcional)



## 🛡️ Sistema Reporter (Errores & Seguridad)

Sistema propio para **detectar, agrupar y reportar errores** tanto de **cliente** como de **servidor**, sin spam y con rate limiting.

### ✔️ Qué hace
- Captura errores de scripts (client & server)
- Envía reportes agregados a Discord / Telegram
- Detecta patrones sospechosos de exploit
- Agrupa errores iguales (evita spam)
- Rate limit por jugador
- Logs claros y organizados

### ❌ Qué NO hace
- No ejecuta código remoto
- No usa APIs de exploit en cliente
- No afecta al rendimiento del juego
