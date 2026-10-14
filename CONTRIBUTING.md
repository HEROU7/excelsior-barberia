# Guía de Contribución — EXCELSIOR Barbería Clásica

¡Gracias por tu interés en colaborar con **EXCELSIOR Barbería Clásica de Autor**!

Este proyecto está diseñado bajo principios de **cero dependencias complejas (Vanilla JS + Tailwind CSS)** para maximizar la velocidad de carga, la fidelidad estética y la estabilidad en cualquier dispositivo móvil o de escritorio.

---

## 1. Principios de Desarrollo

- **Rendimiento ante todo:** Evita agregar paquetes pesados o librerías innecesarias de Node.js.
- **Estética de Autor:** Respeta la paleta noble (nogal oscuro, cuero envejecido, oro satinado y tonos crema).
- **Accesibilidad y Semántica:** Asegura etiquetas semánticas HTML5, contrastes WCAG AA y soporte completo para navegación táctil y por teclado.
- **Persistencia Confiable:** Cualquier mejora al motor de reservas debe mantener compatibilidad con `localStorage` y respetar la moneda dual (USD y RD$).

---

## 2. Flujo de Trabajo

1. **Haz un Fork** del repositorio.
2. **Crea una rama descriptiva** para tu mejora:
   ```bash
   git checkout -b feature/nueva-mejora
   ```
3. **Prueba localmente:**
   Puedes iniciar un servidor estático con Python o Node:
   ```bash
   python -m http.server 8000
   # o
   npx serve .
   ```
4. **Haz commit con mensajes claros:**
   ```bash
   git commit -m "feat: añade animación de transición en modales"
   ```
5. **Abre un Pull Request** detallando el propósito y capturas del cambio.

---

## 3. Reporte de Errores

Si encuentras algún problema o comportamiento inesperado, abre un [Issue](https://github.com/HEROU7/excelsior-barberia/issues) indicando:
- Dispositivo y navegador utilizado.
- Pasos para reproducir el error.
- Capturas de pantalla o mensajes de consola (si aplica).
