# El tiempo invisible del agro

Observatorio del **uso del tiempo rural** en el Perú, con datos oficiales de la **Encuesta Nacional de Uso del Tiempo (ENUT) 2024 — INEI**.

El enfoque es el ángulo agrario: la ENUT mide el **trabajo agropecuario para autoconsumo** y el **trabajo doméstico y de cuidados no remunerado** —justo lo que las estadísticas agrarias (CENAGRO, encuestas de producción) no capturan— y revela que la **mujer rural** soporta la mayor carga total de trabajo del país.

## Datos (ENUT 2024, población 12+ años, horas:minutos por día)

| Indicador (día de semana) | Mujer rural | Hombre rural | Mujer urbana | Hombre urbano |
|---|---|---|---|---|
| Trabajo no remunerado | 5 h 26 m | 2 h 06 m | 5 h 02 m | 2 h 10 m |
| Trabajo en la ocupación | 4 h 43 m | 7 h 28 m | 7 h 12 m | 9 h 07 m |

Carga global nacional (trabajo total): mujeres 8 h 53 m / hombres 8 h 25 m en día de semana.

**Fuente única:** INEI — ENUT 2024, Principales Resultados (cuadros III.4.2 y III.5.2).
https://www.gob.pe/institucion/inei/campañas/99771-resultados-de-la-encuesta-nacional-de-uso-del-tiempo-enut

**Regla:** no se inventa ninguna cifra. Las "cargas totales" que suman dos series están marcadas como cálculo del observatorio.

## Stack
Sitio estático (HTML + ECharts), pensado para GitHub Pages. Sin build.

## Desarrollo local
```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```
