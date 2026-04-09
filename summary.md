# MOVYSAM — Progress Summary

## Stav: v1.0 — LIVE

**GitHub:** https://github.com/supercigan/movysam
**Vercel:** automatický deploy z master branch

---

## Zdrojový web

**URL:** https://www.movysam.cz/
**Firma:** MOVYSAM — Vodo Topo Plyn
**Majitel:** Milan Vyorálek
**Lokace:** Kněžpole, Uherské Hradiště, Zlín a okolí
**Email:** info@movysam.cz
**Gienger partner:** ano

---

## Fonty

| Role     | Font          | Weights | Důvod výběru |
|----------|---------------|---------|--------------|
| Nadpisy  | Space Grotesk | 700/800 | Geometrický, technický, moderní — sedí k řemeslné firmě |
| Text     | Inter         | 400/500 | Nejčitelnější webfont, professionální |

---

## Barevná paleta

| Proměnná      | Hex       | Použití                        |
|---------------|-----------|--------------------------------|
| --navy        | #1A2B4A   | Primární — nav, hero bg        |
| --navy-dark   | #0F1F38   | Footer, hero tmavší            |
| --orange      | #F97316   | Akcent — CTA, hover, highlight |
| --cyan        | #0891B2   | Voda — sekundární akcent       |
| --light       | #F8FAFC   | Střídavé bg sekcí              |
| --text        | #0F172A   | Základní text                  |
| --muted       | #64748B   | Popisné texty                  |

---

## Sekce webu (v pořadí)

1. **Nav** — sticky, blur backdrop, logo s ikonou, hamburger na mobilu
2. **Hero** — full-height, gradient bg, nadpis + CTA + 4 hero cards + trust strip
3. **O nás** — grid 1:1, checklist, CTA, year badge
4. **Služby** — 3×2 grid karet s hover animací + top border efekt
5. **Proč my** — tmavá sekce, 4 ikony výhod
6. **Gienger partner** — banner s logem partnera
7. **Kontakt** — kontaktní info + Google Maps + formulář
8. **Footer** — logo, navigace, copyright

---

## Responsivita (dle CLAUDE.md checklistu)

- [x] html + body mají overflow-x: hidden
- [x] font-size minimum 16px na všech breakpointech
- [x] všechny CTA mají min-height: 44px
- [x] 640px: hamburger, services → 1 sloupec, hero-actions → column
- [x] 428px: menší padding sekcí
- [x] 375px: container padding 1rem, h1 menší
- [x] 320px: h1 1.75rem, logo-sub skrytý, nav padding 1rem

---

## Animace

- Scroll reveal (IntersectionObserver) — fade + translateY
- Hero: fadeInUp + fadeInRight pro jednotlivé prvky
- Nav: blur + box-shadow při scrollu
- Service cards: hover lift + orange top border
- Hero cards: hover lift

---

## TODO pro příští iteraci

- [ ] Přidat reálné fotografie realizací
- [ ] Přidat telefonní číslo (zákazník nedodal)
- [ ] Přidat sekci reference / galerie
- [ ] Napojit formulář na backend / Formspree
