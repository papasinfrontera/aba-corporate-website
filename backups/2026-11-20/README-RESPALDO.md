# AB&A — Respaldo de referencia 2026-11-20

**Propósito:** conservación y recuperación; esta carpeta NO está conectada al despliegue de producción.

## Procedencia y alcance
- Proyecto: Vercel cuenta AI Mindset Agency (#2), `aba-corporate-website`.
- Producción observada: `dpl_5jLfoENndfxdH9QrLVojGBGuGrUa` (READY; 2026-11-19).
- Los archivos `es/index.html` y `en/index.html` de ESTA carpeta proceden de los documentos fuente Footer V3 creados el 19-11-2026. **No se ha probado igualdad byte a byte con los HTML de producción.**
- La carpeta `assets/` contiene 11 imágenes binarias extraídas de dichos HTML. Sus nombres son SHA-1 de los bytes de imagen y coinciden con los identificadores registrados en el inventario de archivos de Vercel.
- `legal-review/` conserva las cuatro páginas legales bilingües aprobadas como versión de revisión, **no** páginas publicadas.
- Los archivos de raíz de la rama (sitio de noviembre 16) se heredaron de `main` al crear la rama; NO son automáticamente idénticos a producción.
- El repositorio es **público**; no guardar contraseñas, tokens, registros privados o capturas de credenciales.

## Inventario del respaldo nuevo
- `es/index.html`: 3,679,990 bytes (SHA-256 `09590838f6f86d2ed1a3bdd5ed823e61d4b4510e369ad9a5b1b290a4ac2f0ffe`).
- `en/index.html`: 3,678,708 bytes (SHA-256 `36a1b98ce9ad15e1328924ce30dda058f312d585934a6dca9a886e520a94f0d5`).
- `assets/`: 11 imágenes binarias; los hashes SHA-1 se encuentran en los nombres.
- `legal-review/es/terminos-y-condiciones/index.html`: 2,115,031 bytes (SHA-256 `82d0f5abbaa0b52e6d6a2cf76387dd496430dc7eaa9b4740f6aa995740c9cd39`).
- `legal-review/en/terms-and-conditions/index.html`: 2,114,146 bytes (SHA-256 `fd2b566d4c67ebe0ff2c6dec4581197749503fce0f290505aa3a0aa6ee4464d7`).
- `legal-review/es/privacidad-y-cookies/index.html`: 2,117,403 bytes (SHA-256 `c4a3487d3a4b6d424d969e960415b0f095fd3c8c6e525f8450db814e6953c1d4`).
- `legal-review/en/privacy-and-cookies/index.html`: 2,116,568 bytes (SHA-256 `58949d2fe19b347aaa35e9c3ec43b7b18f63d3b2351ce56e24a62fedf1c916ec`).

## Restauración segura (NO automática)
1. Descargar esta rama y comprobar los SHA-256; verificar los 11 archivos de imagen según sus nombres SHA-1.
2. Antes de cualquier despliegue, comparar el HTML recuperado con los archivos íntegros de Vercel y corregir valores de marcador `YOUR-PRODUCTION-DOMAIN` si los hubiera. No asumir que esta revisión sea el código actual.
3. Construir un despliegue Preview **aislado** en la Cuenta #2; comprobar ambas versiones, QR, enlaces, imágenes, móviles, WhatsApp y formularios.
4. No modificar `main`, aliases, DNS ni producción sin nueva aprobación del usuario.
5. Conservar una copia adicional fuera de GitHub. El historial Git no es un respaldo único suficiente.

## Estado
Respaldo de referencia copiado en GitHub; **pendiente** certificación exacta HTML producción y prueba de restauración en Preview.
