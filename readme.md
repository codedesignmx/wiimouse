# WiiMote Mouse Controller

Este script permite utilizar un control **WiiMote** como un mouse para tu computadora. El movimiento del puntero se controla mediante el sensor infrarrojo del WiiMote, y los botones **A** y **B** están asignados para simular clic izquierdo y clic derecho, respectivamente.

---

## 🎮 Funcionalidades

- **Mover el puntero del mouse** usando el puntero IR del WiiMote.
- **Clic izquierdo** con el botón **A** del WiiMote.
- **Clic derecho** con el botón **B** del WiiMote.

---

## 🧩 Código del Script

Este script puede usarse en herramientas como [GlovePIE](http://glovepie.org) u otros programas compatibles con scripts para WiiMote:

```javascript
mouse.x = wiimote.PointerX
mouse.y = wiimote.PointerY

// Clic izquierdo con botón A
mouse.LeftButton = wiimote.A

// Clic derecho con botón B
mouse.RightButton = wiimote.B