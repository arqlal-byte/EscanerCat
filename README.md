# EscanerCat — Prueba de lector

Prototipo independiente de la aplicación de Iniciación Cristiana. **No escribe ni consulta registros reales en Google.**

## Flujo

1. Seleccionar evento de prueba.
2. Abrir cámara del celular.
3. Leer códigos QR o de barras consecutivamente.
4. Ver el identificador leído y el contador de códigos únicos.
5. Cambiar de evento para detener la cámara.

Los eventos disponibles son ficticios y únicamente permiten probar el flujo. Los códigos se procesan dentro del navegador; no se envían a servidores.

## Publicar en GitHub Pages

Desde este repositorio, abrir **Settings > Pages**. Elegir **Deploy from a branch**, rama `main`, carpeta `/(root)` y guardar.

El navegador debe solicitar permiso de cámara sobre una página HTTPS. Probar en iPhone/Android con gafetes reales.

## Integración futura con Google Apps Script

Antes de activar el guardado de asistencias, faltan el enlace de implementación de Apps Script, el catálogo de actividades reales, la validación de coordinadores y una API que registre la combinación evento + identificador sin duplicados. No publicar credenciales privadas en este repositorio público.
