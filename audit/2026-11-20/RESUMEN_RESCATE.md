# AB&A — Registro de respaldo de referencia (20-11-2026)

**Estado: COPIA DE REFERENCIA; NO ES UN BACKUP EXACTO DE PRODUCCIÓN.**

- Empresa: ARAUJO, BACALAO & ASOCIADOS (AB&A).
- Sitio: https://www.aba.com.ve
- Vercel: AI Mindset Agency, proyecto `aba-corporate-website`, ID `prj_5lO740kcHxAQ9xZ9zlFb0Zlea7ZR`.
- Despliegue observado: `dpl_5jLfoENndfxdH9QrLVojGBGuGrUa`, 19-11-2026, estado READY.
- Rama original GitHub: `main`, commit `d7d7367d3ec042f3f35b45649bbc755f14acc473` del 16-11-2026.
- Copias históricas completas recuperadas del 19-11-2026:
  - `ABA_Footer_V3_ES.html` (3 679 990 bytes), SHA256 `09590838f6f86d2ed1a3bdd5ed823e61d4b4510e369ad9a5b1b290a4ac2f0ffe`.
  - `ABA_Footer_V3_EN.html` (3 678 708 bytes), SHA256 `36a1b98ce9ad15e1328924ce30dda058f312d585934a6dca9a886e520a94f0d5`.
- 11 recursos gráficos recuperados. Sus SHA1 se corresponden con los identificadores de recursos incluidos en el inventario del despliegue vigente.

## Limitaciones
1. Los SHA1 de los HTML históricos **no coinciden** con los identificadores de los HTML del despliegue. No son una copia bit a bit certificada de producción.
2. El conector de Vercel trunca la recuperación de archivos HTML grandes.
3. Este commit **no incorpora esos HTML históricos ni el paquete ZIP**. El archivo externo `ABA_Backup_Referencia_Verificada_2026-11-20.zip` está disponible en la conversación del proyecto; debe conservarse externamente.
4. No se ha ejecutado una restauración real en Vercel Preview, por tanto no se ha acreditado recuperabilidad de producción.
5. Se ha prohibido el merge automático de esta rama a `main`. No publicar desde este archivo.

## Procedimiento siguiente
Recuperar los HTML completos de la fuente efectiva de despliegue, comprobar sus hashes, crear backup físico/externo, evaluar el contenido antes de subirlo al repositorio público y ensayar una restauración aislada. Solo entonces fusionar código validado previa aprobación.

Esta rama se creó para documentar la trazabilidad del respaldo sin modificar la web pública.