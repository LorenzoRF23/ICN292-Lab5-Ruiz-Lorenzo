# ICN292-Lab5-Ruiz-Lorenzo

Entrega del Laboratorio 5 de ICN-292 (Sistemas de Información para la Gestión), USM, 2026-2. Lorenzo Ruiz Flandez.

El laboratorio pide armar en MySQL 8 la base `andesbike` de Andes Bike, una cadena de tiendas de bicicletas con locales en Providencia, Maipú, Concepción y La Serena. El script crea las cuatro tablas (`tiendas`, `vendedores`, `bicicletas` y `ventas`), carga los datos oficiales del enunciado y responde 10 consultas.

## Qué hay en el repo

| Archivo | Contenido |
| --- | --- |
| `ICN292-Lab5-Ruiz-Lorenzo.sql` | creación de las tablas, carga de datos y las 10 consultas |
| `ICN292-Lab5-Ruiz-Lorenzo.tex` | informe en LaTeX |
| `ICN292-Lab5-Ruiz-Lorenzo.pdf` | el mismo informe en PDF |
| `imagenes/` | logos y capturas que usa el `.tex` |
| `ICN292-Lab5-Ruiz-Lorenzo.png` | modelo entidad-relación (Reverse Engineer de Workbench) |

## Cómo leerlo

El informe tiene una portada y después una sección por consulta, con el código tal como se ejecutó y la captura de lo que devolvió Workbench. Las consultas 4, 8 y 10 llevan además una línea de explicación: dónde puse la condición del mes, de dónde sale el promedio del catálogo ($657.490) y por qué dos vendedores aparecen con NULL en vez de cero.

## Para correrlo

Abrir el `.sql` en MySQL Workbench y ejecutarlo. Como empieza con `DROP DATABASE IF EXISTS andesbike`, se puede correr las veces que haga falta y siempre parte de cero. Ninguna consulta modifica los datos, así que se pueden correr en cualquier orden. Sobre la carga completa, las 18 ventas suman 16.969.650.
