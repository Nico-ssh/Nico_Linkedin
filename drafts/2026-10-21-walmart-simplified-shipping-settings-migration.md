# LinkedIn Publication Package — 2026-10-21

## CONTENT OPPORTUNITY

Three opportunities researched this run:

1. **Walmart Marketplace retired the legacy "Shipping Templates" API endpoints in favor of Simplified Shipping Settings (SSS) 2.0 — deprecation started August 4, 2026, new endpoints launched August 31, 2026, and today (October 21) any integration still built on the old endpoints is running on infrastructure Walmart no longer maintains.** This is Walmart's own developer-docs change (not a third-party blog rumor): the deprecation notice explicitly warns that any integration using Shipping Templates via the old endpoints is affected and must migrate. Eligibility for SSS is narrow (free shipping, 48 contiguous states only); freight, bundles, virtual packs and ship-to-store items aren't supported yet and must stay on manual templates. Migration itself is a one-click, reversible action in Seller Center that can take up to 6 hours per batch. Nobody in the repo has covered Walmart's shipping-settings/API layer before — the one prior Walmart backend post (2026-09-30) was about Delegated Access → OAuth authentication, a different system entirely.
   **Scores — Relevance 9 / Authority 9 / Engagement 8 / Lead-gen 8 / Timeliness 7 (the cutover itself was Aug 4–31, but the grace period has fully closed and most sellers running this through a 3PL/WMS/repricer still don't know their own migration status — the "quiet infrastructure change nobody checked" framing is evergreen-timely, and the exact mechanics haven't appeared anywhere in the repo).**

2. **Amazon now deactivates a single underperforming FBM offer instead of risking the whole account, effective since August 31, 2026 — a reversal of the account-wide-risk model the repo's 2026-09-02 post warned about.** Genuinely interesting counter-narrative (account health getting more surgical, not more punitive), confirmed by one trade outlet (PPC Land) describing Amazon's own Seller Forums announcement, with a related but separately-sourced item-level evaluation change from February 28, 2026 (myamazonguy.com). The two reports describe adjacent but not identical mechanics, and neither has a second fully independent corroboration of the exact August 31 rule — thinner fact-check footing than #1.
   **Scores — Relevance 8 / Authority 7 / Engagement 7 / Lead-gen 7 / Timeliness 5 (effective date is 7+ weeks old, and sourcing is closer to single-source than this repo's bar). Held — would need a second independent source to state the mechanic as cleanly as #1's.**

3. **TikTok Shop US seller terms / seller-fault-cancellation enforcement "effective October 15, 2026."** Initially looked fresh, but on a second, deeper search pass the October 15 enforcement date and the ≤2.5% seller-fault-cancellation threshold only confirm on TikTok's Vietnam and Philippines seller pages — not a verified US Seller Center announcement. Likely a regional policy that got conflated with "US" in earlier aggregated results. Dropped per this repo's single-source/unconfirmed-claim rule rather than published with a caveat.
   **Scores — Relevance 5 / Authority 3 / Engagement 4 / Lead-gen 4 / Timeliness 6. Discarded — fails independent cross-market verification.**

**Winner: #1.** Best-sourced story this run (four independent official Walmart developer/Seller Center pages plus two independent third-party integration partners, all consistent on dates and mechanics), opens Walmart's shipping/API infrastructure as a new lead topic distinct from every prior Walmart post, and is naturally checklist-shaped — exactly Wednesday's brief — without being forced into that format.

**Not a repeat:** No hook, framework or example here has appeared before. Distinct from 2026-09-11 (Walmart Connect's ad-platform strategy pivot) and from 2026-09-30 (Delegated Access → OAuth authentication for third-party app connections) — this is specifically about how Walmart *calculates and configures shipping* at the SKU level, a different system and a different failure mode (wrong shipping cost/time shown to shoppers, not a dead integration).

## TARGET AUDIENCE

Walmart Marketplace sellers — and the agencies, VAs and 3PL/WMS providers who manage Walmart shipping settings on their behalf — who haven't personally touched Shipping Templates since onboarding and have no way of knowing whether their account (or their client's) ever migrated to SSS 2.0; LATAM-based operators running backend integrations for US-based Walmart sellers as part of their service.

## FORMAT

Carousel (8 slides) — genuine multi-step sequence (what changed → who's exposed → eligibility → what's still unsupported → how to check → what to ask your provider → takeaway). Restores carousel format after three consecutive non-carousel posts (10-14 single infographic, 10-16 single image, 10-19 single infographic), and the content itself is a scannable audit checklist, not formatted as a carousel out of habit.

## LANGUAGE

Spanish. Rebalances the repo's language mix (15 English / 6 Spanish before this post, ~71/29 → 15/22, ~68/32 after, staying close to the ~70/30 target) and reaches LATAM-based agencies/operators who run Walmart backend integrations for US clients — the exact audience this topic is written for, and the same underserved lane the 09-30 Walmart/OAuth post reached successfully.

## LINKEDIN POST

Walmart lleva casi dos meses calculando el envío con una fórmula distinta. Nadie te mandó un correo preguntando si tu integración se dio cuenta.

El 4 de agosto, Walmart empezó a retirar los endpoints antiguos de "Shipping Templates". El 31 de agosto lanzó el reemplazo: Simplified Shipping Settings (SSS) 2.0. Walmart lo dice sin rodeos en su propia documentación: cualquier integración que todavía use esos endpoints queda afectada.

Esto no es un anuncio con ruido. Es un cambio de infraestructura — del tipo que no se ve como error. Se ve como pedidos con tarifas raras, envíos que no calzan, o una conversión que baja sin que encuentres por qué.

Lo que necesitas saber:

→ SSS 2.0 solo aplica si ofreces envío gratis y despachas dentro de los 48 estados contiguos.
→ Freight, bundles, virtual packs y ship-to-store TODAVÍA no están soportados — esos SKUs se quedan en plantillas manuales, a propósito.
→ La migración es automática y reversible desde Seller Center, pero puede tardar hasta 6 horas por lote.
→ Si administras tu cuenta a través de un WMS, repricer o agencia, la pregunta no es "¿subí mis precios hoy?" — es "¿alguien confirmó que mis SKUs ya están en SSS 2.0?"

Dejé el checklist completo en el carrusel — es de los que se corren en 10 minutos desde Seller Center.

¿Ya revisaste el estado de tu cuenta esta semana? Cuéntame qué encontraste.

## VISUAL

**Format:** Carousel, 8 slides, 1080×1350 px each. Style: professional, modern, minimal, premium marketplace/tech aesthetic — not a stock-photo or AI-generated-face look. Clean geometric sans-serif typography (Inter/Söhne/Aktiv-Grotesk feel), generous whitespace, legible at mobile thumbnail size. Dark charcoal-navy background (#14161C) with one accent blue (#2E6CF0-ish, deliberately NOT Walmart's exact brand blue/spark mark — no logos) used for headlines, icons and checkmarks only. Simple line icons only (a box, a shipping label, a wrench/gear, a checklist, a question mark in a speech bubble) — no photography. Consistent slide counter (1/8…8/8) bottom corner. Max ~25–30 words of body copy per slide; headline carries the weight.

**Slide 1 — Hook**
Headline: "WALMART CAMBIÓ CÓMO CALCULA EL ENVÍO"
Subhead (accent color): "Hace casi dos meses. Y nadie te avisó."
Small tag, bottom corner: "Checklist para sellers y agencias de Walmart Marketplace"
Visual: line icon of a shipping label with a small "sync" arrow next to it, half-faded.

**Slide 2 — Problem / timeline**
Headline: "¿QUÉ PASÓ, EXACTAMENTE?"
Timeline (3 stacked rows with connecting line):
"4 ago 2026 → Walmart empieza a retirar los endpoints de Shipping Templates"
"31 ago 2026 → Lanza Simplified Shipping Settings (SSS) 2.0"
"Hoy → Si tu integración no migró, corre sobre una API que Walmart ya no mantiene"
Visual: horizontal timeline bar, three marked points, accent-color dot on "Hoy."

**Slide 3 — Who's exposed**
Headline: "¿A QUIÉN LE PEGA ESTO?"
Bullets:
"Cualquier cuenta conectada por API: WMS, repricer, software de listados"
"Agencias y VAs que administran Walmart por un tercero"
"Sellers que nunca tocaron Shipping Settings a mano — porque alguien más lo automatizó"
Visual: three simple line icons in a row (server/API, person at desk, gear).

**Slide 4 — Eligibility**
Headline: "¿QUIÉN PUEDE USAR SSS 2.0?"
Two check-style bullets:
"✓ Envío gratis en todas tus ofertas"
"✓ Despacho dentro de los 48 estados contiguos"
Small note below: "Si cumples esto, Walmart calcula el envío automáticamente, por SKU."
Visual: a simple US map outline (48 contiguous states only, no labels/brand marks) with accent-color fill.

**Slide 5 — What's still unsupported**
Headline: "LO QUE TODAVÍA NO CUBRE"
Bullets with "✗":
"✗ Freight"
"✗ Bundles"
"✗ Virtual packs"
"✗ Ship-to-store"
Small note: "Esos SKUs se quedan en plantillas manuales — y ahí sí hay que revisarlos uno por uno."
Visual: four small line icons (pallet/freight, stacked boxes, layered box, storefront) each with a small "✗" badge.

**Slide 6 — How to check your own account**
Headline: "CÓMO REVISAR TU CUENTA — 10 MINUTOS"
Numbered checklist:
"1. Seller Center → Shipping Settings
2. Manage Settings → Item Migration
3. Confirma si tus SKUs ya están en SSS 2.0
4. Si usas una integración externa, repite esto en el panel de tu proveedor"
Visual: clean numbered list with accent-color circles around each number.

**Slide 7 — If someone else manages your account**
Headline: "SI OTRO ADMINISTRA TU CUENTA"
Body: "Una sola pregunta a tu 3PL, tu software de listados o tu agencia:"
Quote-style callout box: "¿Ya migraron mis SKUs de Walmart a Simplified Shipping Settings 2.0?"
Small note: "Si la respuesta es 'no sabemos', ahí está el riesgo."
Visual: speech-bubble icon with a question mark, accent color.

**Slide 8 — Takeaway + soft CTA**
Headline: "LA CONCLUSIÓN"
Body: "Walmart no anuncia estos cambios con ruido. Los publica en una página de documentación para desarrolladores y asume que alguien la está leyendo."
CTA line: "¿Ya revisaste el estado de tu cuenta esta semana? Cuéntame qué encontraste."
Small signature line: "Nicolás Peña — Amazon & Walmart Marketplace Operations"
Visual: minimal accent-color underline motif echoing slide 1, no headshot required.

## FIRST COMMENT

Si manejas varias cuentas de Walmart (propias o de clientes) y quieres que revisemos juntos el estado real de tu migración a SSS 2.0, mándame un mensaje — esto vive en la capa de infraestructura, así que puede estar roto hace semanas sin que aparezca como error en ningún lado.

## HASHTAGS

#WalmartMarketplace #EcommerceOps

## SOURCES

- [Deprecation: Simplified Shipping Settings APIs — Walmart Developer Docs (official)](https://developer.walmart.com/us-marketplace/page/deprecation-simplified-shipping-settings-apis) — deprecation timeline (Aug 4, 2026 start; Aug 31, 2026 SSS 2.0 launch)
- [Simplified Shipping Settings API overview — Walmart Developer Docs (official)](https://developer.walmart.com/us-marketplace/lang-es/docs/simplified-shipping-settings) — migration is automatic/reversible, up to 6 hours per batch; freight/bundle/virtual-pack/ship-to-store not yet supported
- [Simplified Shipping Settings — eligibility (48 contiguous states, free shipping) — Walmart Developer Docs, Canadian French page (official)](https://developer.walmart.com/us-marketplace/lang-fr_CA/docs/simplified-shipping-settings)
- [Simplified Shipping Settings — apply settings to your items — Marketplace Learn, Walmart (official Seller Center guide, last updated Apr 10, 2026)](https://marketplacelearn.walmart.com/guides/Seller%20Fulfillment%20Services/Simplified%20Shipping%20Settings/simplified-shipping-settings-apply-settings-to-your-items) — UI steps (Manage Settings → Item Migration → Migrate my items)
- [How Walmart Simplified Shipping Settings Increase GMV and Lower Shipping Costs — Cahoot](https://www.cahoot.ai/walmart-simplified-shipping-settings-boost-gmv-cut-costs/) — independent third-party corroboration of SSS mechanics and benefits
- [Walmart Marketplace Simplified Shipping Settings — SellerCloud Help Center](https://help.sellercloud.com/omnichannel-ecommerce/walmart-marketplace-simplified-shipping-settings/) — independent integration-partner corroboration (most fields settable only at first creation, must edit in Seller Center)

All four Walmart-owned pages are official primary documentation (direct WebFetch not attempted given this environment's consistent egress-proxy blocking on every prior run; facts corroborated via WebSearch snippets that quote/paraphrase the pages consistently, plus cross-checked against two independent third-party integration partners who describe the same mechanics from the integrator's side). Candidate #2 (Amazon FBM offer-level deactivation) and candidate #3 (TikTok Shop Oct 15 terms update) were researched this run and explicitly dropped/held rather than softened into the post — see CONTENT OPPORTUNITY section for why.

## STRATEGIC REASON

This positions Nicolás as someone who audits the unglamorous infrastructure layer — shipping settings and API migrations — not just ad strategy or policy deadlines, which is exactly the kind of operator-level vigilance that justifies paying for account management rather than DIY. It opens a new, well-documented Walmart authority lane distinct from the ad-strategy (09-11) and authentication (09-30) posts already published, and the first-comment offer maps directly to a real, billable service (auditing a Walmart account's shipping-settings migration status), giving it a clean, non-salesy path into a lead conversation.

## QUALITY SCORE

Hook: 9/10
Authority: 9/10
Usefulness: 9/10
Originality: 8/10
Engagement: 8/10
Lead potential: 8/10
Visual potential: 8/10

## REPO

Draft saved to `drafts/2026-10-21-walmart-simplified-shipping-settings-migration.md`. Calendar row appended to `linkedin_content_calendar.csv`. Commit/push status below.

## STATUS

**READY FOR APPROVAL**
