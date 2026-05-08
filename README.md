# ¡TU AVENTURA! 🚀✨

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X41Z55AM)

**¡TU AVENTURA!** es una aplicación web interactiva y gamificada diseñada específicamente para ayudar a niños y niñas a establecer, seguir y completar sus rutinas diarias. Convierte las tareas cotidianas en una emocionante aventura de rol (RPG), donde cada tarea completada otorga puntos, experiencia (XP), niveles y ayuda a evolucionar a un divertido compañero virtual.

Desarrollada con un diseño premium y adaptada para dispositivos móviles y tablets, es la herramienta perfecta para que los más pequeños de la casa adquieran autonomía de una manera divertida y motivadora.

---

## 🌟 Características Principales

### ⚔️ Temas y Universos Interactivos
Los niños pueden elegir el universo en el que quieren jugar cada día. Cada tema cambia por completo la paleta de colores, las animaciones, el fondo y el tipo de mascota virtual:
*   **🚀 ESPACIO:** ¡Conviértete en astronauta y viaja por el cosmos!
*   **🌲 BOSQUE:** Explora la naturaleza y haz amigos salvajes.
*   **🏴‍☠️ PIRATAS:** ¡Surca los mares en busca de tesoros escondidos!
*   **🦁 SELVA:** Adéntrate en la vegetación y ruge con fuerza.
*   **🦖 DINOS:** Un viaje prehistórico alucinante en un mundo jurásico.
*   **🏎️ CARRERAS:** Siente la velocidad en el Gran Premio definitivo.
*   **🦸 HÉROE:** ¡Ponte la capa y salva el mundo!

### 🥚 Compañero Virtual Evolutivo (Pet Companion)
Cada aventura viene acompañada de un **Huevo Misterioso (`🥚`)** que irá eclosionando y evolucionando a medida que el niño consiga puntos y suba de nivel completando sus rutinas:
1.  **HUEVO MISTERIOSO** (`🥚`)
2.  **PEQUEÑO AMIGO** (`👶`/`🐥`/`🐢`/`🐒`/`🦖`/`🏎️`/`🐕`)
3.  **GRAN COMPAÑERO** (`🛸`/`🦊`/`🦜`/`🐆`/`🦕`/`🏎️`/`🦸`)
4.  **HÉROE LEGENDARIO** (`🛰️`/`🦌`/`🏴‍☠️`/`🦁`/`🐉`/`🏆`/`⚡`)

### 📋 Misiones y Rutinas Personalizables
La aplicación incluye por defecto una rutina base que cubre las principales tareas diarias de un niño:
*   **🧹 Recoger:** Ordenar la habitación y juguetes.
*   **🍳 Desayuno:** Alimentarse bien para empezar el día con energía.
*   **🪥 Dientes:** Mantener una sonrisa limpia y brillante.
*   **👚 Vestirse / Desvestirse:** Aprender a cambiarse de ropa de forma autónoma.
*   **🎒 Mochila:** Preparar todo el material escolar necesario.

### ⏱️ Reloj de Misión Inteligente
El juego permite configurar 3 tipos de gestión del tiempo para adaptarse a la velocidad del niño:
*   **Sin Tiempo:** Para realizar las tareas de forma relajada y sin presión.
*   **Cronómetro:** Mide cuánto tiempo tarda en completar su rutina para intentar superar su propio récord.
*   **Cuenta Atrás:** Establece un límite de tiempo (por ejemplo, 10 minutos) para añadir un divertido desafío de velocidad.

### 🔒 Control Parental (Setup Phase)
Cuenta con un panel de control protegido mediante un cerrojo parental (`🔒`/`🔓`). Los padres pueden:
*   Activar o desactivar fases de la rutina diaria.
*   Reordenar el orden de las tareas mediante botones de navegación.
*   Añadir nuevos pasos a la rutina desde el pool disponible.
*   Configurar los modos de tiempo y ajustar la duración en minutos.

---

## 🛠️ Detalles Técnicos y Arquitectura

*   **Aplicación Single-File (`index.html`):** Toda la lógica, diseño CSS y animaciones están contenidos en un único archivo. Esto garantiza una velocidad de carga instantánea y permite ejecutar la aplicación sin conexión a internet de forma local.
*   **Cero Dependencias Externas:** No requiere de servidores, bases de datos o instalaciones complejas. Utiliza únicamente fuentes optimizadas de Google Fonts.
*   **Interfaz Glassmorphic Premium:** El diseño emplea estilos fluidos similares a los de iOS/macOS, con gradientes vibrantes, bordes de cristal brillante, sombras dinámicas con efectos de luz de fondo (glow) y transiciones elásticas.
*   **Accesibilidad de Audio e Idioma:** Cuenta con síntesis de voz nativa del navegador (Web Speech API) para leer las misiones e instrucciones en voz alta en español, facilitando el juego a niños que aún no saben leer.
*   **Efectos Visuales Premium:** Sistema de partículas de confeti nativo (`HTML5 Canvas`) para celebrar la subida de nivel y la culminación con éxito de la rutina diaria.
*   **Persistencia Local:** Los datos de nivel, experiencia, estado del compañero virtual y rutinas configuradas se guardan de forma segura en el `localStorage` del navegador.

---

## 🚀 Cómo Ejecutar la Aplicación

Al ser una aplicación web estática pura de un solo archivo, ejecutarla es sumamente sencillo:

1.  **Doble Clic:** Simplemente haz doble clic en el archivo `index.html` para abrirlo directamente en tu navegador web favorito (Chrome, Safari, Firefox, Edge).
2.  **Servidor Local (Opcional):** Si prefieres servirlo mediante un entorno de desarrollo, puedes usar herramientas ligeras como `Live Server` en VS Code, o mediante la consola de comandos:
    ```bash
    # Usando Python
    python -m http.server 8000
    
    # O usando Node.js / npx
    npx serve .
    ```

---

## 🎨 Créditos y Soporte

Creado por **Sangar Studio** con mucho cariño para hacer que las mañanas y noches de las familias sean más divertidas y organizadas.

Si te gusta esta aplicación y quieres apoyar nuestro trabajo, puedes invitarnos a un café:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/X8X41Z55AM)

---
*© 2026 Sangar Studio. Todos los derechos reservados.*
