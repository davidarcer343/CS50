# Roomix (roomix.ai) — Análisis de competencia desde Growth Comercial

*Fecha de corte: 19-nov-2026 · Autor: Growth Lead (Venture Studio) · Formato: consultoría (conclusiones → razones → por qués)*

Leyenda de confianza: 🟢 verificado · 🟡 declarado por la empresa · 🔴 inferido por nosotros

---

## 1. Conclusiones ejecutivas

1. **Roomix es un metabuscador B2C de propiedades que cobra a las inmobiliarias (B2B), no a las constructoras.** Junta los avisos de Zonaprop, Argenprop, Mercado Libre, Properati y portales regionales en un solo lugar, los ordena con IA y cobra a las inmobiliarias un asistente de IA por WhatsApp a **~US$30 por asesor** 🟡. **No tiene oferta visible para desarrolladoras ni constructoras** (emprendimientos en pozo, preventa, gestión de unidades). **Ese es nuestro hueco más claro.**

2. **Su ventaja es el SEO, no la venta.** Pasaron de ~5.000 visitas/mes (jul-2024) a 380k–500k+ visitas/mes (mediados 2026) 🟡, casi todo con SEO orgánico: más de **2.138 artículos** de blog 🟢 (guías por barrio × perfil × tipología, comparativas contra Zonaprop, un "Índice Roomix" de precios). Ahrefs publicó su caso de éxito ("x100 en un año"). **El tráfico es su activo y su argumento de venta a las inmobiliarias.**

3. **Su monetización todavía es incipiente.** Equipo de 5 personas 🟢, más de 200 inmobiliarias "reclamaron perfil" y están en **lista de espera** para el agente IA 🟡 (la prensa habla de ~600 interesadas 🟡). Con US$30/asesor, aunque convirtieran 600 inmobiliarias × 3 asesores, serían **~US$54k de MRR** 🔴. **Hoy son una empresa de tráfico que recién empieza a cobrar.**

4. **Levantaron US$500K, no US$10M.** Todas las fuentes públicas (prensa, Dealroom, PitchBook y el anuncio de la propia empresa) dicen **pre-seed de US$500.000**, cerrada entre feb y abr de 2026 y anunciada en mayo de 2026 🟢, más una mini-ronda previa de ~US$45K de Picante.fund 🟡. **No encontramos ninguna referencia pública a US$10M.** Si ese dato viene de una fuente privada, hay que documentarla (ver [pendientes](../../00-brain/pendientes-de-validar.md)).

5. **Su red de inversores ángeles es muy fuerte y le da prensa gratis.** Guillermo Rauch (CEO de Vercel), Adam D'Angelo (Quora, directorio de OpenAI), Charlie Songhurst (directorio de Meta), Cocos Capital y Picante.fund 🟢. La historia "un pibe de 24 años de Mar del Plata convenció a Rauch" salió en Forbes, La Nación, iProUP, Ámbito, Mercado y medios locales. **Su relato de fundador funciona como canal de adquisición.**

6. **El crecimiento se está desacelerando.** El equipo declara un crecimiento de ~26% mensual 🟡, pero entre abr-2026 (250k) y jul/ago-2026 (380k) el crecimiento implícito es de **~11% mensual** 🔴. Para llegar a su meta declarada de 1M de visitas a fin de 2026 tendrían que volver a crecer ~27% por mes 🔴. **El SEO de contenido en volumen empieza a saturarse. Ahí entra un competidor nuevo.**

7. **Su dependencia es un riesgo.** Su inventario viene de los portales que indexa (Zonaprop, Argenprop, MeLi). Si los portales bloquean el crawling o Google penaliza el contenido masivo hecho con IA, su principal canal se cae. **Nosotros tenemos que tener inventario propio y relación directa con quien genera la oferta: el desarrollador.**

### Recomendación en una línea
> **No competir de frente como "otro buscador".** Atacar el lado de la oferta que Roomix no cubre: **constructoras y desarrolladoras** (ticket alto, pocas cuentas, ventas de unidades de US$80k–300k+). Copiar lo que les funciona (SEO programático + relato de fundador + producto con WhatsApp) pero aplicado a **"emprendimientos / inversión en pozo"**, y cobrar por resultados (leads calificados, unidades vendidas) en lugar de por asesor. Detalle en [cómo ganarle](como-ganarle.md).

---

## 2. Qué es y qué hace

| Dimensión | Hallazgo | Conf. |
|---|---|---|
| Categoría | Metabuscador / "AI OS for real estate". *"Somos un metabuscador, no un portal"* | 🟢 |
| Propuesta al usuario final | Búsqueda en lenguaje natural, todo el inventario en un lugar, ranking por relevancia, filtro de fotos retocadas con IA (oct-2026), "mudanza virtual" (amoblado virtual) | 🟢 |
| Propuesta a la inmobiliaria | Publicar gratis; herramientas IA gratis (descripciones a partir de fotos, sugerencia de precio por comparables, detección de duplicados, priorización de leads); **Agente IA por WhatsApp** pago: busca propiedades, arma colecciones, agenda visitas, carga el CRM, maneja campañas | 🟢/🟡 |
| Integraciones | **Tokko Broker** (directa); evaluando otros CRM | 🟢 |
| Ranking | "No ordena por quién paga más sino por mejor presentación y reputación" (crítica directa al modelo de Zonaprop) | 🟡 |
| Geografía | Argentina (fuerte en CABA). Interés declarado en **México y España** | 🟢 |
| Base | Mar del Plata (legal) / Buenos Aires (equipo) | 🟢 |
| Equipo | 5 personas (ago-2026) | 🟢 |
| App móvil | Anunciada para agosto 2026 | 🟡 |

## 3. Cómo atacan el mercado (marketplace de dos lados)

```
          DEMANDA (gratis)                         OFERTA (paga)
  Google SEO ──► roomix.ai (buscador IA) ──► leads ──► Inmobiliaria
  (2.138 artículos, barrios,                 12k contactos/mes   │
   comparativas, índice de precios)          (abr-2026) 🟡       ▼
                                                         "Reclamá tu perfil" (gratis)
  PR / Founder story ──┘                                         │
                                                                 ▼
                                                   Herramientas IA gratis
                                                                 │
                                                                 ▼
                                                 Lista de espera ► Agente WhatsApp
                                                                  US$30/asesor/mes
```

**Por qué funciona:** crawlean los avisos de todas las inmobiliarias → las inmobiliarias reciben leads desde Roomix sin haber pagado nada → les ofrecen "reclamar su perfil" → herramientas gratis → upsell al agente pago. **Adquieren la oferta con el tráfico que consiguen gratis por SEO.** CAC de la oferta casi cero.

**Por qué es frágil:** (a) el valor depende del tráfico y el tráfico depende de Google; (b) el ticket por asesor es bajo (US$30) en un mercado de pymes muy sensibles al precio; (c) compiten con decenas de chatbots de WhatsApp para inmobiliarias (Chatsell, BrokerCrew, Mirando.ai, etc.) que también se integran con Tokko.

## 4. A quién se dirigen (y a quién no)

| Segmento | ¿Lo atacan? | Evidencia |
|---|---|---|
| Inquilinos en CABA (2-amb, temporario, amoblado, habitaciones compartidas) | **Sí, principal** | La mayoría de los artículos del blog son de alquiler en CABA |
| Expatriados / nómadas | Sí | "Alquilar en Villa Urquiza para expatriados" |
| Inversores minoristas | Sí, de forma liviana | "Alquilar en Almagro para inversores" |
| Compradores | Sí | Comparativas de precios de venta |
| Inmobiliarias pymes (con Tokko) | **Sí, cliente que paga** | Página /para-inmobiliarios, integración con Tokko |
| **Desarrolladoras / constructoras** | **No visible** | No hay página, plan ni caso público |
| Bancos / financiación hipotecaria | No | — |

## 5. Tiempo en el mercado y crecimiento

- Los cofundadores se conocen en **feb-2024**; la empresa se funda en **abr-2024**. **Llevan ~2 años y 7 meses** 🟢.
- Pivot: de tesis sobre IA para fotos / tours virtuales → a buscador (feb-2025, tras una aceleradora suiza) 🟢.
- Tráfico: 5k (jul-24) → 250k sesiones (abr-26) → 380k (jul/ago-26) → "400k+" (su web) / "500k+" (Ahrefs) / "600k" (Yahoo) 🟡.
- Detalle mes a mes, curvas y cálculos en [metricas-y-timeline.md](metricas-y-timeline.md).

> ⚠️ **No hay datos públicos de crecimiento mes a mes auditados.** Lo que tenemos son puntos sueltos declarados en prensa. Para tener la serie mensual hay que usar SimilarWeb, Semrush o Ahrefs (el conector de SimilarWeb falló en esta sesión; queda pendiente).

## 6. Documentos de soporte

- [Métricas y timeline](metricas-y-timeline.md)
- [Inbound y SEO](inbound-y-seo.md)
- [Fundadores e inversores](fundadores-e-inversores.md)
- [Proceso comercial y clientes potenciales](proceso-comercial-y-clientes.md)
- [Cómo ganarle — estrategia + plan de 90 días](como-ganarle.md)
- [Fuentes](fuentes.md)
