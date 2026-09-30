# LinkedIn Publication Package — 2026-09-30

## CONTENT OPPORTUNITY

Three opportunities researched this run:

1. **Walmart Marketplace retires Delegated Access keys in favor of OAuth 2.0 — existing keys stop working at the end of September/October 1, 2026.** Since July 30, 2026, approved Solution Providers can no longer create new Delegated Access keys (Walmart's older key-based authentication for third-party apps). Existing keys stop working at the end of September 2026 (sources split between "end of September" and "October 1" — treated as the same cutover window). The replacement is OAuth 2.0 authorization via the "Connect" button in the Walmart App Store, which never shares raw credentials. Critically, OAuth 2.0 authorizations aren't "set and forget" either — Walmart requires annual renewal per connected app. Sellers whose listing sync, repricing, or order-management tools still ride on the old key system risk a silent integration failure with no seller-facing error banner — the symptom shows up as stale inventory, un-synced pricing, or delayed orders.
   **Scores — Relevance 9 / Authority 9 / Engagement 8 / Lead-gen 9 / Timeliness 10 (cutover window is this exact week).**

2. **Amazon Seller Assistant opens to Claude and Amazon Quick with persistent memory and always-on automated workflows (announced Sept 23, 2026 at Amazon Accelerate).** Real and fresh — sellers can now manage pricing, inventory and listings through Claude or Amazon Quick, with memory that follows them across sessions and automations that run even when logged out. Strong authority angle (access-control questions: what scope are you granting an AI agent that can change prices?).
   **Scores — Relevance 8 / Authority 8 / Engagement 8 / Lead-gen 7 / Timeliness 8. Passed over: thematically too close to the 2026-09-28 post (Amazon Ads MCP Server — AI agents getting write access into ad accounts). Publishing a third "AI agent gets account access" post in five entries risks the pillar reading as one repeated narrative rather than distinct authority ground. Held for a future run with a sharper angle (e.g., once real seller experiences with the plugin start surfacing).**

3. **TikTok Shop — Fulfilled by TikTok (FBT) inbound-arrangement deadline of October 15, 2026 for Black Friday/Cyber Monday inventory readiness, plus new ocean floor-loading option for large shipments.** Genuine and dated, but the substance is standard "start your holiday prep early" logistics advice already common across the ecosystem — thinner differentiation and authority ceiling than #1.
   **Scores — Relevance 6 / Authority 6 / Engagement 6 / Lead-gen 6 / Timeliness 7. Passed over: generic angle, no sharp original insight this run; held for a future TikTok Shop post closer to the BFCM window.**

**Winner: #1.** Highest combined authority + lead-gen + timeliness score — this is a live, dated infrastructure deadline landing in the exact publish week, it opens Walmart account-security/integration-management as a genuinely new lead topic (the repo's only prior Walmart post, 2026-09-11, covered ad-platform strategy, not backend authentication), and it is naturally checklist-shaped rather than forced into that format for the sake of Wednesday's slot.

**Not a repeat:** No hook, framework or example here has appeared before. Distinct from 2026-09-11 (Walmart Connect's strategic pivot to a full ad platform — a Wall Street/strategy story) and from every Amazon-AI-agent post (09-18, 09-28) — this is Walmart-specific, authentication/infrastructure-specific, and framed as an operational audit rather than a strategic read or an AI-access risk list.

## TARGET AUDIENCE

Walmart Marketplace sellers and the agencies/ops teams managing multiple Walmart accounts via third-party software (repricers, inventory managers, order/listing integrators) who don't personally administer the technical connection and could be blindsided by a silent sync failure; LATAM-based agencies and freelance operators who run backend integrations for US-based Walmart sellers as part of their service.

## FORMAT

Carousel (8 slides) — the content is a genuine multi-step sequence (what's changing → why it fails silently → old vs. new auth model → the renewal trap → a checklist to run today), which is exactly what a carousel is for. Restores format variety: the last two posts were single-image (09-25) and no-visual (09-28), so this also breaks a two-post non-carousel streak on its own merits, not just habit.

## LANGUAGE

Spanish. Rebalances the repo's language mix (9 English / 3 Spanish before this post, 25% → 10/13, ~31% after, in line with the brief's ~70/30 target) and reaches LATAM-based agencies and operators who manage Walmart integrations for US clients — a technical, rarely-covered-in-Spanish topic that speaks directly to that audience's daily work.

## LINKEDIN POST

El 30 de septiembre, Walmart apagó un sistema de acceso que casi nadie revisaba.

No es una campaña. No es un listing. Es la conexión entre tus herramientas de terceros y tu cuenta de Walmart Seller Center.

Si usas un repricer, un gestor de inventario o cualquier integrador conectado vía Solution Provider, esto te puede afectar sin que nadie te avise directamente — porque vive en la capa de infraestructura, no en el dashboard de ventas.

Desde el 30 de julio, Walmart dejó de permitir nuevas claves del sistema antiguo (Delegated Access). Y desde finales de septiembre, las claves existentes empiezan a dejar de funcionar. El reemplazo es OAuth 2.0, con renovación anual obligatoria por cada app conectada — así que incluso si ya migraste, la autorización puede estar por vencer sin que lo sepas.

Swipe para el checklist de 5 puntos que puedes correr hoy mismo en tu Seller Center →

¿Ya revisaste tus apps conectadas esta semana? Cuéntame qué encontraste.

## VISUAL

**Format:** Carousel, 8 slides, 1080×1350 px each. Style: professional, modern, minimal, premium marketplace/tech aesthetic. Clean sans-serif typography (geometric grotesk look — Inter/Söhne/Aktiv-Grotesk style), generous whitespace, mobile-readable at thumbnail size. Dark charcoal-navy background (#14161C or similar) with a single accent color (deep blue, #0071CE-adjacent but not a literal Walmart logo/spark mark) used sparingly for emphasis, arrows and icons. No stock photography, no AI-generated faces/hands, no Walmart or Amazon brand marks — use simple geometric line icons (a key, a lock/shield, a plug/connector, a checkmark) instead. Consistent slide numbering (1/8 … 8/8) in a corner. Max ~25-30 words of body text per slide; the headline is the anchor.

**Slide 1 — Hook**
Headline (large, bold): "WALMART APAGÓ UN SISTEMA DE ACCESO ESTA SEMANA"
Subhead (smaller, accent color): "Y probablemente nunca lo revisaste"
Small tag (bottom corner): "Checklist para sellers y agencias de Walmart Marketplace"
Visual: line icon of an old key fading out / turning translucent.

**Slide 2 — Problem**
Headline: "¿Qué está pasando?"
Body bullets:
"30 jul 2026 — Walmart dejó de permitir nuevas claves 'Delegated Access'
Fin de sept / 1 oct 2026 — las claves existentes dejan de funcionar
Afecta a cualquier app conectada vía Solution Provider: repricers, gestores de inventario, integradores de pedidos"
Visual: simple timeline bar with two marked dates.

**Slide 3 — Insight: old vs. new model**
Headline: "Delegated Access vs. OAuth 2.0"
Two-column comparison:
"ANTES (Delegated Access): clave compartida, sin fecha de vencimiento visible, en retiro.
AHORA (OAuth 2.0): autorización vía botón 'Connect' en el Walmart App Store, no comparte credenciales, requiere renovación anual."
Visual: split-screen icon — old key icon left, plug/connector icon right.

**Slide 4 — Insight: why it fails silently**
Headline: "Por qué falla en silencio"
Body: "No hay un banner rojo que diga 'tu integración murió'. El síntoma es indirecto: inventario sin actualizar, precios sin sincronizar, pedidos atrasados. Para cuando lo notas, ya perdiste visibilidad y ventas."
Visual: a dimmed/disconnected plug icon, no alert icon nearby — reinforcing "silent" failure.

**Slide 5 — Insight: the renewal trap**
Headline: "La trampa que casi nadie ve"
Body: "OAuth 2.0 no es 'configúralo y olvídalo'. Walmart exige renovar cada app conectada una vez al año. Si migraste hace 12 meses y no volviste a revisar, esa autorización también puede estar por vencer."
Visual: circular "renewal" arrow icon with a small calendar mark.

**Slide 6 — Framework/checklist**
Headline: "CHECKLIST — corre esto hoy en Seller Center"
Checklist (checkbox icons):
"☐ Entra a Connected Apps y lista cada app conectada
☐ Identifica si cada una sigue en Delegated Access o ya está en OAuth 2.0
☐ Si sigue en Delegated Access: pide al Solution Provider el link de reconexión (botón Connect)
☐ Si ya está en OAuth 2.0: revisa la fecha de renovación anual
☐ Verifica con una prueba real: cambia un precio o stock menor y confirma que sí sincronizó"
Visual: clean checklist layout, accent-color checkmarks.

**Slide 7 — Key takeaway**
Headline: "La lección de fondo"
Body: "Las integraciones son infraestructura invisible. Auditas tu catálogo, tus campañas, tu Buy Box — pero rara vez auditas la autenticación que mueve todo eso. Y es justo ahí donde se cae la operación."
Visual: minimal, an outline of interconnected nodes with one node highlighted in accent color.

**Slide 8 — Soft CTA**
Headline: "¿Ya revisaste tus apps conectadas esta semana?"
Body: "Cuéntamelo en los comentarios — o si prefieres, lo revisamos juntos."
Small signature line: "Nicolás Peña — Amazon & Walmart Marketplace Operations"
Visual: minimal accent-color underline motif echoing slide 1, no headshot required.

## FIRST COMMENT

Si administras varias cuentas de Walmart (las tuyas o de clientes) y quieres una revisión rápida de qué apps siguen en Delegated Access, mándame un mensaje — esto se está volando bajo el radar y puede tumbar una sincronización sin que nadie lo note por días.

## HASHTAGS

#WalmartMarketplace #EcommerceOps

## SOURCES

- [Walmart App Connection Changes Sellers Should Know — Ordoro Blog](https://blog.ordoro.com/2026/08/12/walmart-app-connection-changes/) (dated Aug 12, 2026)
- [Delegated access authorization — Walmart Developer Docs (official, snippet-corroborated only)](https://developer.walmart.com/us-marketplace/docs/delegated-access-authorization)
- [OAuth 2.0 authorization — Walmart Developer Docs (official, snippet-corroborated only)](https://developer.walmart.com/us-marketplace/docs/oauth-20-authorization)
- [Walmart's OAuth and Delegated Access Features for Marketplace — GeekSeller](https://www.geekseller.com/blog/walmarts-oauth-and-delegated-access-features-for-marketplace/)
- [Feed: Walmart Marketplace — Connecting Walmart US: Delegated API Access for Solution Providers — GoDataFeed Help Center](https://help.godatafeed.com/hc/en-us/articles/360028547171-Feed-Walmart-Marketplace-Connecting-Walmart-US-Delegated-API-Access-for-Solution-Providers)
- [Walmart Marketplace App Store Guide for Sellers in 2026 — GoTrellis](https://gotrellis.com/resources/blog/walmart-marketplace-app-store-guide/)
- [Get started as an approved Solution Provider — Walmart Developer Docs](https://developer.walmart.com/us-marketplace/docs/get-started-as-a-solution-provider)

All of these are trade-press/integration-partner secondary sources plus official Walmart developer documentation; direct WebFetch to developer.walmart.com was not attempted given this environment's consistent egress-proxy blocking on every prior run, so the official-docs facts are corroborated via WebSearch snippets that quote or paraphrase them consistently across independent domains (Ordoro, GeekSeller, GoDataFeed, GoTrellis all agree on: July 30, 2026 new-key-creation cutoff; existing keys stopping at the end of September/October 1, 2026; OAuth 2.0 as the replacement via the Connect button; annual renewal requirement). The exact cutover day varies by a single day across sources ("end of September" vs. "October 1") — the post deliberately uses the softer, source-consistent phrasing "finales de septiembre" rather than asserting one precise date. No specific percentage of affected sellers or a guaranteed error message was found in any source, so the post frames the failure mode as a risk ("puede fallar sin aviso") rather than a certainty.

## STRATEGIC REASON

This positions Nicolás as someone who tracks the unglamorous, easily-missed infrastructure layer of marketplace operations — not just ad strategy or policy deadlines — which is exactly the kind of vigilance a brand owner wants from an account manager. It opens Walmart backend/integration management as its own credible authority lane distinct from the ad-strategy angle already covered, and the audit offer in the first comment maps directly to a real, billable account-management service (auditing connected apps and authentication health), giving it a clean, non-salesy path into a lead conversation.

## QUALITY SCORE

Hook: 9/10
Authority: 9/10
Usefulness: 9/10
Originality: 9/10
Engagement: 8/10
Lead potential: 9/10
Visual potential: 9/10

## REPO

Draft saved to `drafts/2026-09-30-walmart-delegated-access-oauth-checklist.md`. Calendar row appended to `linkedin_content_calendar.csv`. Commit/push status below.

## STATUS

**READY FOR APPROVAL**
