# Trabajo 01 (Individual) — Teoría de la Decisión bajo Incertidumbre

Trabajo individual de la asignatura **Teoría de la Decisión** (Grado en Estadística,
Universidad de Sevilla). Consiste en **inventar dos problemas de decisión bajo
incertidumbre**, enunciarlos y resolverlos con las funciones R de la asignatura.

## Contenido del repositorio

| Fichero | Descripción |
|:--------|:------------|
| `Trabajo01_individual_enunciados.qmd` | **Documento 1 de 2.** Enunciados de los dos problemas y sus cinco preguntas de verdadero o falso por problema. |
| `Trabajo01_individual_soluciones.qmd` | **Documento 2 de 2.** Los mismos enunciados con la resolución paso a paso (cálculo manual + código R + salidas) y las respuestas verdaderas marcadas. |
| `Trabajo01_individual_enunciados.html` / `.pdf` | Versiones generadas del documento 1 (HTML y PDF con Typst). |
| `Trabajo01_individual_soluciones.html` / `.pdf` | Versiones generadas del documento 2 (HTML y PDF con Typst). |

Cada documento está disponible en **dos formatos**: `html` (navegable, con índice) y
`pdf` (generado con **Typst**).

## Los dos problemas

**Problema 1 — datos inventados.** Una empresa ficticia debe decidir en qué ciudad abrir
una nueva delegación. Se resuelve **criterio por criterio** (Wald, Optimista, Hurwicz,
Savage, Laplace y Punto Ideal), tanto en **situación favorable** (apartado a: tabla de
beneficios) como en **situación desfavorable** (apartado b: tabla de costes), incluyendo
el estudio completo del criterio de Hurwicz en todo el rango.

**Problema 2 — situación real.** Una empresa de distribución de alimentación congelada
decide cómo gestionar su flota de reparto (flota propia, renting o subcontratación). Se
resuelve con la función `criterio.Todos`, que devuelve la resolución de **todos los
métodos en una única tabla**.

Cada problema termina con **cinco preguntas de verdadero o falso**, con al menos una
verdadera y al menos una falsa; las respuestas correctas están marcadas al final de cada
problema en el documento de soluciones.

## Cómo reproducir los resultados

Las funciones utilizadas están en el paquete R **`TDecisionCodigo`**, desarrollado en
<https://github.com/calote/TDecisionCodigo>. Se instala y carga así:

```r
#install.packages("remotes")
remotes::install_github("calote/TDecisionCodigo")

library(TDecisionCodigo)
```

## Autoría

- **Autor:** Esteban Blanco Díaz (GitHub: [`eblancod27`](https://github.com/eblancod27))
- **Asignatura:** Teoría de la Decisión — Universidad de Sevilla
- **Fecha de entrega:** 23 de octubre de 2026
