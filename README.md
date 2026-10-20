# Proyecto Django u4s7 — [Arturo Vazquez Diaz]

## Demo en vivo (producción)
https://u4s7-vazquez-diaz-arturo.onrender.com

## Panel de administración
https://u4s7-vazquez-diaz-arturo.onrender.com/admin

## Cómo correrlo localmente
1. Crear y activar un entorno virtual
2. pip install -r requirements.txt
3. Copiar .env.example a .env y completar con credenciales propias de Aiven, más SECRET_KEY, DEBUG y ALLOWED_HOSTS
4. python manage.py migrate
5. python manage.py runserver

## Semana 7 — Pulido funcional, UX y simulacro de defens
Modelo Servicio migrado a MySQL, Web Service publicado en Render,
5 registros reales cargados desde /admin.

## Evidencia
Ver capturas de `migrate` y de las tablas en Aiven en la carpeta /evidencias.
