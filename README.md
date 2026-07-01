# 🚀 Space Shooter - Prototipo Multiplataforma

![Space Shooter Demo](https://img.shields.io/badge/status-alpha-yellow) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![Gamepad](https://img.shields.io/badge/Gamepad-Supported-brightgreen)

**Un shooter espacial ligero y adictivo, con controles adaptados para móvil, PC y gamepad.**

---

## 📝 Descripción

**Space Shooter** es un prototipo de juego de naves desarrollado en **HTML5, CSS y JavaScript puro** (sin librerías externas). Su diseño está pensado para ser **ultraligero, responsive y multiplataforma**, funcionando tanto en navegadores de escritorio como en dispositivos móviles.

### 🎮 Características actuales

- **Navegación fluida** con joystick táctil, teclado (WASD/Flechas) o gamepad (stick izquierdo).
- **Sistema de disparo** con cooldown y efecto de partículas.
- **Enemigos variados**: normales (1 golpe) y tanques (3 golpes) con barra de vida.
- **Dificultad progresiva** que aumenta con la puntuación.
- **Sistema de combo** que se acumula al destruir enemigos y se reinicia al recibir daño.
- **Partículas explosivas** en impactos, destrucciones y disparos.
- **Fondo dinámico** con estrellas en movimiento.
- **Game Over** con resumen de puntuación y mejor combo.
- **Controles híbridos**: funcionan simultáneamente táctil, teclado y gamepad.

---

## 🖥️ Controles

| Plataforma | Movimiento | Disparo |
|------------|------------|---------|
| **Móvil** | Joystick táctil (esquina inferior izquierda) | Botón rojo (esquina inferior derecha) |
| **PC (Teclado)** | WASD o Flechas | Espacio |
| **PC (Mouse)** | No soportado (usar teclado o gamepad) | - |
| **Gamepad** | Stick izquierdo (con deadzone) | Botón A, X o Bumper derecho |

> 💡 **Nota:** El juego detecta automáticamente si hay un gamepad conectado y muestra un indicador en pantalla.

---

## 🚀 Cómo jugar

1. **Descarga o clona** el repositorio.
2. Abre el archivo `index.html` en tu navegador favorito.
3. ¡Disfruta!

---

## 📱 Compatibilidad

| Dispositivo | Estado |
|-------------|--------|
| **Navegadores de escritorio** (Chrome, Firefox, Edge, Safari) | ✅ Total |
| **Móviles y tablets** (Android, iOS) | ✅ Total (con controles táctiles) |
| **Gamepads** (USB, Bluetooth) | ✅ Compatible (estándar XInput/DirectInput) |
| **Pantallas táctiles** | ✅ Prevención de zoom y desplazamiento |

---

## 🛠️ Tecnologías utilizadas

- **HTML5** con `canvas` para renderizado.
- **CSS3** para estilos y diseño responsive.
- **JavaScript (ES6)** para toda la lógica del juego.
- **Gamepad API** para soporte nativo de mandos.
- **Web Audio API** (próximamente para efectos de sonido).

---

## 📂 Estructura del proyecto
SpaceShooter/
├── index.html # Código completo (HTML + CSS + JS)
├── README.md # Este archivo

---

## 🔮 Futuras mejoras (hoja de ruta)

- [ ] **Menú principal** con pantalla de título y opciones.
- [ ] **Gestor de escenas** (menú, juego, pausa, game over).
- [ ] **Nuevos tipos de enemigos** (zigzagueantes, buscadores, jefes).
- [ ] **Power-ups** (disparo triple, escudo, velocidad, bomba).
- [ ] **Plataformas y exploración** (scroll horizontal, gravedad, coleccionables).
- [ ] **Banda sonora y efectos 8-bit** (con Web Audio API).
- [ ] **High score persistente** (localStorage).
- [ ] **Port a C++ con SDL2** (para builds nativas en Windows, Linux y macOS).
- [ ] **Versión para Android** (con WebView o SDL2).

---

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Si quieres mejorar el juego o añadir nuevas funcionalidades:

1. Haz un fork del repositorio.
2. Crea una rama para tu feature (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva funcionalidad'`).
4. Sube tu rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Si lo usas o modificas, menciona la autoría (¡aunque no es obligatorio, se agradece!).

---

## 👤 Autor

**Epics Box Studio**  
- GitHub: [@tusuario](https://github.com/EpicsBoxStudio)  
- Email: 10jpineda9@gmail.com  

---

## 🌟 Agradecimientos

- Inspirado en los clásicos *Space Invaders*, *Galaga* y *R-Type*.
- Gracias a la comunidad de desarrolladores indie por su apoyo y recursos.
- Mención especial a **Irisbell** (por la inspiración espiritual en otros aspectos creativos).


## 🎯 Estado del proyecto

**Versión actual:** 0.5.0 (alpha)  
**Última actualización:** Julio 2026  
**Próximo hito:** Implementación de menú y gestor de escenas.

---

¡Gracias por probar **Space Shooter**! Si te gusta, no olvides darle una ⭐ al repositorio. 🚀✨
