# Conversor de Monedas

![Conversor de Monedas](./screenshot.png) <!-- opcional: captura de tu app -->

## Descripción

Aplicación web para convertir monedas de forma rápida y precisa, con tasas de cambio actualizadas en tiempo real. La interfaz es moderna, sencilla y responsive, funcionando correctamente en computadoras y dispositivos móviles.

**Características principales:**
- Conversión entre más de 150 monedas
- Interfaz limpia y fácil de usar
- Botón para intercambiar monedas rápidamente
- Actualización de tasas en tiempo real
- Compatible con dispositivos móviles y escritorio

---

## Estructura del proyecto
currency-converter/
│
├── index.html # Archivo principal de la web
├── css/
│ └── style.css # Estilos de la aplicación
├── js/
│ └── app.js # Lógica de conversión
├── manifest.json # (Opcional) para PWA
└── service-worker.js # (Opcional) para PWA offline


---

## Cómo usar

1. Abrir `index.html` en un navegador web moderno.
2. Seleccionar la moneda de origen y la moneda de destino.
3. Introducir la cantidad a convertir.
4. Hacer clic en el botón **Convertir** para ver el resultado.
5. (Opcional) Hacer clic en el icono de intercambio para cambiar las monedas rápidamente.

---

## Cómo publicar la web

### GitHub Pages
1. Crear un repositorio en GitHub y subir todos los archivos.
2. Activar Pages en `Settings → Pages → Branch: main → /root`.
3. Acceder a la web en `https://tuusuario.github.io/currency-converter/`.

### Netlify
1. Ir a [Netlify](https://www.netlify.com/) y crear un sitio.
2. Arrastrar toda la carpeta del proyecto.
3. Acceder a la URL generada por Netlify.

---

## Convertir a app móvil

- **PWA**: Solo agrega `manifest.json` y `service-worker.js`. La web se podrá instalar como app.
- **Cordova / Capacitor**: Copia la carpeta `currency-converter` dentro de `/www` del proyecto y compila para Android/iOS.

---

## Tecnologías usadas

- HTML5
- CSS3
- JavaScript (Vanilla)
- APIs de conversión de monedas (si aplicas tasas reales)

---

## Contribuciones

Si quieres mejorar el proyecto, puedes:
- Añadir soporte para más monedas
- Mejorar el diseño o la experiencia en móviles
- Integrar nuevas APIs de tasas en tiempo real

---

## Autor

**Alex R.**  
Proyecto personal de aprendizaje y práctica web.


