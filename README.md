# Show Planner Spain — nueva plataforma web

Este repositorio contiene exclusivamente la nueva web de Show Planner Spain en fase de pruebas. La web actual https://www.showplannerspain.es/ sigue alojada en IONOS y no se modificará su DNS hasta terminar las comprobaciones.

Páginas: Inicio, Catálogo de espectáculos, Quiénes somos, Contacto, Espacio Cliente (maqueta). La maqueta no tiene autenticación ni solicita datos de clientes. No conectar a clientes reales mientras esté en pruebas.

## Publicación en GitHub Pages

Configuración deseada: Settings → Pages → Build and deployment → Source: GitHub Actions. Dirección de pruebas prevista: https://flamencoevents.github.io/Show-Planner-Spain-/ . No introducir Custom domain ni CNAME hasta el lanzamiento definitivo.

## Pendientes antes del lanzamiento

- Recuperar imágenes y logotipo originales desde la web/IONOS y verificar derechos y calidad.
- Completar aviso legal y privacidad con datos reales, revisar cumplimiento RGPD y adaptar el futuro formulario.
- Implementar autenticación real y aislamiento de datos en Supabase para un espacio cliente independiente del de Flamenco Events.
- Validar solicitudes comerciales y selección de leads en Celebrents sin compra ni acceso automático.
- Auditar MX/TXT/SPF/DKIM de Show Planner Spain y preservar el correo antes de cambiar DNS.
- Redirecciones de las URL antiguas y SEO, eliminar noindex exclusivamente tras validación.

## Pruebas

Ejecutar: `python3 validate_show_planner.py`.

Contacto actual mostrado en la web original: +34 615 438 693 y nachomarroco@gmail.com; revisar antes de publicar definitivamente.
