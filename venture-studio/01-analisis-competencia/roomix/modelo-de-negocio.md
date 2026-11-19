# Roomix — Modelo de negocio aclarado: ¿buscador o bot de WhatsApp?

🟢 verificado · 🟡 declarado · 🔴 inferido

## Conclusión
**El motor de Roomix es el buscador web con IA (roomix.ai) para el consumidor final, gratis y alimentado por SEO.** Es lo que genera las visitas, los datos y los contactos. **El bot de WhatsApp (~US$30 por asesor) es la capa que monetizan, y por cómo se describe, es un copiloto del asesor inmobiliario**, no un bot que atiende al consumidor final. El activo que une las dos capas es el **índice de todas las propiedades del mercado** que arma su crawler.

## Las 3 capas

| Capa | Para quién | ¿Cobra? | Rol en el negocio | Evidencia |
|---|---|---|---|---|
| 1. Buscador web con IA | Consumidor final | No | **Adquisición**: tráfico SEO → contactos a inmobiliarias | "Somos un metabuscador, no un portal" 🟢; tráfico medido en visitas web 🟢 |
| 2. Perfil + herramientas IA gratis | Inmobiliaria | No | **Activación de la oferta** | "Reclamá tu perfil", herramientas gratis 🟢 |
| 3. Agente WhatsApp | **Asesor** de la inmobiliaria | Sí, ~US$30 por asesor por mes | **Monetización** (licencia de productividad por persona) | Ver la cita de abajo 🟢/🟡 |

## Por qué decimos que el bot es para el asesor

Página /para-inmobiliarios:
> *"Es un asistente de IA que funciona como un contacto de WhatsApp. **Le mandás** un audio, texto o foto y se encarga de buscar propiedades, arma colecciones, agenda visitas y hace seguimiento… como si fuera una persona en la oficina 24/7: busca en los portales, llena el CRM, maneja la agenda y las campañas."*

Forbes: *"un asistente disponible las 24 horas vía WhatsApp que busca propiedades **para sus clientes**, agenda visitas y registra el historial de cada interacción."*

- Quien le escribe al bot es el **asesor** ("le mandás un audio").
- El bot busca **en todos los portales** usando el índice del buscador.
- El precio es **por asesor**: es una lógica de licencia de software (SaaS por persona), no de pago por lead.

🔴 **No está confirmado** si el bot también responde al consumidor que le escribe a la inmobiliaria. Para resolverlo: **mystery shopping** (ver [pendientes](../../00-brain/pendientes-de-validar.md), punto 0).

## Cómo fluye el valor

```
Google ──► roomix.ai (buscador IA, gratis) ──► el usuario contacta a la inmobiliaria
                    │                                (12k contactos/mes, abr-26 🟡)
                    │ mismo índice de propiedades
                    ▼
     Asesor ◄──► Bot WhatsApp (US$30/asesor): busca, arma colecciones, agenda, carga Tokko
```

## Implicancias para nosotros
1. **Replicar las dos capas.** Sin buscador ni tráfico propio, un bot de WhatsApp es un commodity (ya existen Chatsell, BrokerCrew, Mirando.ai, LIDZ).
2. **Para constructoras, conviene más un bot que atienda al comprador** que un copiloto para el vendedor. Las desarrolladoras tienen equipos comerciales chicos y muchos leads de inversores que nadie atiende a tiempo. Un bot que **califique, mande planos y planillas de pago, y lleve hasta la reserva** se puede cobrar por resultado.
3. **El activo defendible es la base de datos**, no el chat. Nuestra base debe tener datos que Roomix no tiene: obra nueva, avance de obra, reputación de la desarrolladora, planillas de pago.
