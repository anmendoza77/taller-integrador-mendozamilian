# Taller Integrador — Calculadora de Promedio

**Autor:** Andrés Felipe Mendoza Milián

## Descripción
Sitio web que calcula el promedio de tres notas e indica si el estudiante
aprueba o reprueba, corregido siguiendo buenas prácticas de desarrollo.

## Tabla de hallazgos

| Defecto encontrado | Por qué era un problema | Cómo lo corregí |
|---|---|---|
| Nombres de archivo con espacios y mayúsculas | Dificulta rutas y no sigue convención | Renombrados a minúsculas con guiones |
| Variables `a`, `b`, `c` | No indican qué almacenan | Renombradas a `nota1`, `nota2`, `nota3` |
| Número mágico `x = 3` | No explica su propósito | Reemplazado por constante `CANTIDAD_NOTAS` |
| Variable `TempValue2` | Nombre sin sentido | Renombrada a `promedio` |
| Función `calc()` | No describe qué hace | Renombrada a `calcularPromedio()` |
| IDs `n1, n2, n3, r, r2` | Poco descriptivos | Renombrados a `nota1, nota2, nota3, resultadoPromedio, resultadoEstado` |
| Título de pestaña `pagina` | No describe el sitio | Cambiado a `Calculadora de Promedio` |
| `console.log` y código comentado | Ruido innecesario en producción | Eliminados |

## Sitio publicado
