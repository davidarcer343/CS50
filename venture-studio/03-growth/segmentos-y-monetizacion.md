# Segmentos de demanda y cómo cobrar por cada uno

> 🌎 **Actualización (19-nov-2026):** lanzamos en **Colombia + USA**. Las referencias a Argentina (CABA, CEDU, CAMARCO, Tokko, índice CAC, CNV) son ejemplos del modelo. Los equivalentes para nuestros mercados están en [`02-mercado/`](../02-mercado/README.md) y en el [plan Colombia + USA](plan-colombia-usa.md).


*19-nov-2026* · 🟢 verificado · 🟡 declarado · 🔴 hipótesis a validar

## Conclusión
1. **Roomix validó la adquisición (tráfico SEO para buscar propiedades), no la monetización.** Con 400k visitas por mes siguen con una lista de espera y un MRR estimado bajo 🔴. El modelo de buscador atrae gente; **cómo se le cobra a la oferta sigue sin resolverse**, y ahí es donde podemos ganar.
2. **Dos segmentos de demanda con economías distintas:** el **inversor** (decide con números, puede comprar varias unidades y volver a comprar) y el **comprador para vivienda** (decisión emocional que depende de un crédito, de vender su casa o de la familia).
3. **No cobrar lo mismo por los dos.** Al inversor se lo puede cobrar **por lead calificado**. Al comprador para vivienda conviene cobrarlo **por un evento más avanzado del embudo** (visita agendada o reserva), porque muchos de sus leads se caen aunque el servicio haya sido bueno.

> Nota de términos: lo que se pierde entre lead y compra es **tasa de caída** o **conversión**, no *churn*. *Churn* es cuando un **cliente que paga** (la desarrolladora) cancela. Las dos métricas importan: si cobramos por leads que no convierten, sube el churn de las desarrolladoras.

## Los dos segmentos

| | Inversor | Comprador para vivienda |
|---|---|---|
| Motivación | Rentabilidad y resguardo de valor | Vivir ahí |
| Cómo decide | Con números (precio por m², cuotas, renta) | Emoción + financiación + timing familiar |
| Dependencias | Pocas (suele tener el capital) | Crédito hipotecario, vender su propiedad actual |
| Unidades | Puede comprar 1 o más y repetir | 1, cada muchos años |
| Valor a largo plazo para nosotros | Alto: vuelve en el próximo emprendimiento | Bajo: una sola vez |
| Riesgo de que el lead se caiga | Medio 🔴 | Alto 🔴 |
| Modelo de cobro sugerido | **Por lead calificado** (premium) | **Por visita agendada o reserva** |

⚠️ Tasas de conversión reales por segmento: **no tenemos datos**. Hay que preguntarlas en las 20 entrevistas a desarrolladoras (costo actual por lead, % de leads que llegan a visita, % de visitas que llegan a reserva).

## Escalera de cobro por evento del embudo

| Evento | Qué lo define | Para qué segmento | Riesgo para la desarrolladora | Riesgo para nosotros |
|---|---|---|---|---|
| Lead | Dejó sus datos | — (no recomendado; es commodity) | Alto | Bajo |
| **Lead calificado** | Presupuesto, plazo y forma de pago confirmados por el agente IA | **Inversor** | Medio | Medio |
| **Visita agendada / realizada** | Fue al showroom o a la obra | **Vivienda** (y también inversor) | Bajo | Medio |
| **Reserva** | Firmó la reserva o el boleto | Los dos (success fee) | Muy bajo | Alto (cobramos tarde) |

**Modelo híbrido recomendado 🔴:** fee base por emprendimiento publicado (cubre el costo y filtra a quien no está comprometido) + cobro variable por evento según el segmento: lead calificado para inversores, visita para vivienda, y un success fee por reserva opcional.

## Inversores: contenido y SEO ("cómo invertir en bienes raíces")
Es un cluster clásico de inicio del embudo, con mucho volumen 🔴 y competencia de medios financieros e influencers. **Nuestra ventaja: datos y herramientas** (los medios tienen opinión, nosotros tenemos números en vivo).

| Subcluster | Ejemplos de keywords | Formato |
|---|---|---|
| Cómo invertir | "cómo invertir en bienes raíces", "invertir en ladrillos", "invertir con poco dinero" | Guía + calculadora |
| En pozo | "invertir en pozo conviene", "riesgos de comprar en pozo" | Guía + reputación de desarrolladoras |
| Rentabilidad | "rentabilidad alquiler {zona}", "cuánto rinde un departamento" | Página por zona con datos |
| Instrumentos | "fideicomiso al costo", "cocheras como inversión", "alquiler temporario rentabilidad" | Guía comparativa |
| Comparativas | "ladrillo vs plazo fijo", "pozo vs terminado" | Calculadora |
| Inversor del exterior | "invertir en propiedades en Argentina desde el exterior" | Guía (a validar demanda) |

**Cómo se convierte un inversor:** contenido → calculadora → "ver emprendimientos que cumplen tu objetivo de rentabilidad" → el agente de WhatsApp lo califica → lead calificado a la desarrolladora. Además, se suscribe al newsletter o canal "Oportunidades en pozo" para que vuelva en el próximo emprendimiento.

## Inversión fraccionada: fase futura, no ahora
- Es atractiva para el inversor chico, pero en Argentina **está regulada** (la CNV regula el financiamiento colectivo y los fideicomisos financieros) 🔴. Hay que consultarlo con un abogado antes de cualquier movimiento.
- Por ahora, solo contenido educativo (por ejemplo "qué es la inversión fraccionada") para captar esa demanda y medirla.

## Desarrolladoras grandes vs. medianas
| | Grandes | Medianas |
|---|---|---|
| Qué aportan | Inventario, marca, credibilidad para el buscador | Ingresos (necesitan ventas y no tienen un gran equipo comercial) |
| Competencia | LIDZ.ai ya trabaja con varias 🟡 | Menos atendidas 🔴 |
| Estrategia | **Publicación gratis o con condiciones preferenciales** para tener su inventario | **Clientes que pagan** con el modelo híbrido |
