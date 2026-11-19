# SEO programático: cómo replicar (y superar) el motor de Roomix

## Conclusión
Roomix ganó con una fórmula simple: **barrio × perfil × tipología** = miles de páginas de long tail. Nosotros replicamos la mecánica pero con **otras variables (obra nueva, desarrolladora, inversión)** y con **un dato único por página**. Así, el objetivo de la fase 1 son **~3.000 páginas de alta calidad** 🔴, no 20.000 de relleno.

> ⚠️ **No tenemos volúmenes de búsqueda reales.** El conector de Ahrefs falló en esta sesión. Todos los volúmenes de este documento son hipótesis 🔴 hasta validarlos con Ahrefs, Semrush o Google Keyword Planner (pendiente #10).

## 1. La fórmula de Roomix vs. la nuestra

| | Roomix | Nosotros |
|---|---|---|
| Variables | barrio × perfil × tipología × operación | **zona × etapa de obra × tipología** + **desarrolladora** + **emprendimiento** + **herramienta** |
| Intención | Alquilar (búsqueda rápida, bajo valor) | Invertir o comprar (alto valor, YMYL) |
| Diferencial por página | Precios de los avisos crawleados | Avance de obra, historial de entregas, planilla de pago, rentabilidad calculada |
| Riesgo | Contenido masivo de bajo valor → meseta | Mitigado con datos propios y revisión humana |

## 2. Plantillas de página (templates)

| # | Plantilla | Patrón de keyword (ejemplos) | Fórmula de páginas | Páginas estimadas 🔴 | Embudo |
|---|---|---|---|---|---|
| T1 | **Emprendimiento** | "{nombre emprendimiento}", "{nombre} precio", "{nombre} entrega" | 1 por emprendimiento activo | 1.000–3.000 | Fondo |
| T2 | **Desarrolladora** | "{desarrolladora} opiniones", "{desarrolladora} es confiable", "{desarrolladora} obras" | 1 por desarrolladora | 300–1.500 | Medio |
| T3 | **Zona × etapa** | "departamentos en pozo en {zona}", "emprendimientos en construcción {zona}", "a estrenar {zona}" | ~150 zonas × 3 etapas | ~450 | Medio |
| T4 | **Zona × tipología × etapa** | "monoambiente en pozo {zona}", "2 ambientes en pozo {zona}" | 150 × 4 × 3 | ~1.800 (publicar solo donde hay inventario) | Medio-fondo |
| T5 | **Rentabilidad por zona** | "rentabilidad alquiler {zona} 2027", "conviene invertir en {zona}" | 1 por zona | ~150 | Medio |
| T6 | **Herramientas** | "calculadora cuotas pozo", "pozo vs plazo fijo", "índice CAC cuotas" | ~10 herramientas + variantes por zona | 10–160 | Medio-fondo |
| T7 | **Guías evergreen** | "qué es un fideicomiso al costo", "cómo comprar en pozo sin riesgos", "boleto de compraventa en pozo" | Editorial | 50–100 | Alto (inicio del embudo) |
| T8 | **Comparativas** | "{desarrolladora A} vs {desarrolladora B}", "fideicomiso vs compra en pozo" | Selectivas | 50–200 | Medio |
| T9 (B2B) | **Factibilidad / terreno** | "código urbanístico {barrio}", "qué se puede construir en {zona}", "costo de construcción m² 2027" | Por barrio o zonificación | 100–300 | B2B |
| T10 (B2B) | **Mercado para desarrolladoras** | "absorción {zona}", "oferta de obra nueva {ciudad}" | Por ciudad o zona | ~50 | B2B |

**Por qué T1 y T2 son la joya:** son **keywords de marca** (nombre del emprendimiento o de la desarrolladora). Tienen poca competencia, intención altísima, y hoy las responde solo la web de la propia desarrolladora o un aviso de portal. Si somos la página más completa (avance + reputación + precio), ganamos el clic.

## 3. Qué tiene que tener cada página (reglas de calidad)
1. **Al menos un dato único**: avance de obra con fecha, historial de entregas, precio por m² vs. la zona, rentabilidad calculada.
2. **Autor y metodología visibles** (por ser YMYL): quién revisó y de dónde salen los datos.
3. **Datos estructurados** (schema): `Product` / `Offer` / `Place` / `Organization` / `FAQPage`. Ayudan en Google y en los buscadores de IA.
4. **CTA a WhatsApp** contextual: "Preguntale al asistente por las cuotas de {emprendimiento}".
5. **Enlazado interno en malla**: emprendimiento ↔ desarrolladora ↔ zona ↔ herramienta.
6. **No publicar páginas vacías**: si una combinación no tiene inventario, no se crea (es la lección de Roomix).
7. **Actualización automática** (precios, avance) → señal de frescura.

## 4. Fuentes de datos (para construir el foso)

| Dato | Fuente posible | Estado |
|---|---|---|
| Emprendimientos activos | Sección emprendimientos de portales (como referencia), webs de desarrolladoras, **carga directa de la desarrolladora** | 🔴 a relevar |
| Avance de obra | Fotos o reportes de la desarrolladora, visitas propias, Street View histórico | 🔴 |
| Permisos de obra | Datos abiertos del GCBA (permisos y obras registradas) y municipios | 🔴 verificar disponibilidad |
| Código urbanístico | Ciudad 3D / Código Urbanístico CABA (público) | 🔴 verificar |
| Costo de construcción | Índice CAC (Cámara Argentina de la Construcción), INDEC ICC | 🟢 públicos |
| Reputación | Reseñas propias, registros de entregas, antigüedad (fecha de constitución) | 🔴 |

## 5. Distribución del contenido más allá de Google
- **Buscadores de IA:** contenido en formato pregunta-respuesta, datos con fecha y fuente, y páginas de metodología. Hay que medir si nos citan en ChatGPT y Perplexity.
- **Prensa:** un índice trimestral ("Índice m² pozo vs. terminado") con nota de prensa → backlinks (igual que el Índice Roomix).
- **LinkedIn:** cada dato nuevo → post del fundador dirigido a desarrolladoras.
- **Newsletter / canal de WhatsApp:** "Oportunidades en pozo de la semana" → audiencia propia, sin depender de Google.

## 6. Rampa de publicación sugerida 🔴

| Mes | Páginas acumuladas | Foco |
|---|---|---|
| 1 | 100 | T7 guías + T6 (3 calculadoras) + T3 en CABA |
| 2 | 500 | T1/T2 para 100 emprendimientos y 50 desarrolladoras (CABA + GBA Norte) |
| 3 | 1.200 | T4 donde hay inventario + T5 |
| 4–6 | 3.000 | Córdoba y Rosario + T9 B2B |

Referencia: Roomix pasó de 5k a ~250k–500k visitas en ~12–20 meses 🟡. **Nuestra meta conservadora es 10k visitas a 90 días y 100k a 12 meses** 🔴. Nuestro nicho tiene menos volumen pero mucho más valor por visita.
