# PRD — Osobní web Zdeněk Suchý

**Verze:** 0.1 (draft k doplnění)
**Datum:** 2026-04-29
**Autor:** Zdeněk Suchý

---

## 1. Cíl a kontext

Osobní web prezentující profesní profil Zdeňka Suchého — seniora s 16+ lety v automotive a výrobním průmyslu, nyní rozšiřujícího záběr do IT/SW projektů. Web slouží dvěma segmentům:

- **Recruiters & headhunters** — rychlé posouzení profilu, stažení/prohlédnutí CV, kontakt
- **Potenciální klienti** — konzultační a projektové spolupráce (interim management, PM, change management)

---

## 2. Struktura webu

### 2a. Landing page (stručná)

| Sekce | Obsah | Stav |
|---|---|---|
| Hero | Jméno, headline, CTA (kontakt / blog) | `[DOPLNIT: Q1 — headline]` |
| O mně | 3–4 věty, kdo jsem a co řeším | `[DOPLNIT: Q2]` |
| Co umím | 4–6 karet kompetencí s ikonou | `[DOPLNIT: Q3 — priorita]` |
| Vybrané projekty | 2–3 highlight cards s výsledky | CanCom (delay→0), ZF (OEE 10→75%), TRW (1.8M EUR CM) |
| Kontaktní formulář | Jméno, email, zpráva, odeslat | `[DOPLNIT: Q8 — doména a cílový email]` |
| Footer | LinkedIn, telefon, email | linkedin.com/in/zdenek-suchy |

### 2b. Blog / Case studies

| Sekce | Obsah | Stav |
|---|---|---|
| Přehled článků | Card grid s tagy a perexem | — |
| Článek / Case study | Kontext → Problém → Přístup → Výsledek | `[DOPLNIT: Q6 — první téma]` |
| Tagy / Kategorie | PM / Change Mgmt / Lean / Automotive / IT | `[DOPLNIT: Q5 — upřesnit]` |

---

## 3. Technický stack

**Podmínka:** 100% free (hosting + build + formulář)

**Doporučení:** Astro + Netlify *nebo* Next.js + Vercel

| Vrstva | Nástroj | Cena |
|---|---|---|
| Framework | Astro nebo Next.js | Free |
| Hosting | Netlify nebo Vercel | Free tier |
| Blog/obsah | Markdown soubory nebo Decap CMS | Free |
| Kontaktní formulář | Netlify Forms nebo Resend | Free (3k emailů/měsíc) |
| Analytika | Plausible (self) nebo Umami | Free (self-hosted) |

`[DOPLNIT: Q7 — preferuješ psaní v Markdownu nebo CMS panel?]`

---

## 4. Design

- **Tón:** kreativně technický — konkrétní čísla, výsledky, žádný corporate bullshit
- **Jazyk webu:** `[DOPLNIT: Q4 — CS / EN / dual]`
- **Doména:** `[DOPLNIT: Q8]`
- **Vizuální inspirace:** `[DOPLNIT: Q9]`
- **Mobilní zobrazení:** povinné
- **SEO:** základní (meta tagy, OG pro LinkedIn sdílení)

---

## 5. Obsah — co víme z CV

### Pracovní zkušenosti (16+ let)

| Firma | Role | Období | Klíčový výsledek |
|---|---|---|---|
| CanCom Czech Republic | Project Manager | 2024 – nyní | Delay 1 rok → 0; CM profitabilita 60 % |
| ZF Electronics | Production Unit Manager | 2021 – 2024 | OEE 10 % → 75 % za 3 roky; 200+ lidí; 200M EUR obrat |
| ZF Electronics | Project Manager | 2020 – 2021 | SOP splněn (Mercedes, Maserati) během COVID |
| Bosal | Program Manager | 2018 – 2020 | ROS +19 %, ROI +8 %; portfolio VW 5 projektů |
| TRW | Manufacturing Engineering Manager | 2015 – 2018 | Kvalita 12 % → <1,2 % vad; 0 nálezů při auditech |
| TRW | Senior Change Manager | 2014 – 2015 | Přínos 1,8M EUR za 6 měsíců; best in TRW audit |
| Connectronics NV | Production Engineering Leader | 2011 – 2014 | DPMO 34 000 → 1 300 |
| Connectronics NV | Senior Product Engineer | 2011 | 74 produktů zavedeno v termínu |
| Panasonic | NPI Technician | 2008 – 2010 | — |

### Certifikace & vzdělání

- Prince2
- Lean Six Sigma — Green Belt
- GRID Leadership
- ESD Coordinator
- SPŠ Elektrotechnická Plzeň

---

## 6. Otevřené otázky (dotazník)

Toto jsou otázky k zodpovězení před finalizací PRD. Označeny jako `Q1`–`Q9` a odkazovány výše.

### Q1 — Headline

> Na webu bude věta hned pod jménem. Z CV mám: *"Experienced and people-oriented manager with a good technical background"* — to je generická CV fráze.
>
> **Co ty umíš, co jiný senior manager neumí? Za čím tě mají headhunter nebo klient zavolat?**
>
> *(příklady: "Dostávám rozbité projekty do kondice." / "Stavím výrobu od nuly na výsledek." / "Propojuji svět výroby a IT.")*

### Q2 — O mně

> Máš 16 let napříč automotive, elektronikou a IT. Co tě na té cestě bavilo nejvíc? Kde se cítíš nejvíc doma — v hale, v projektové kanceláři, u zákazníka?
>
> A: **Kde chceš být za 3 roky?** (Interim manager? Konzultant? Vedoucí divize?)

### Q3 — Kompetence na web (priorita)

> Z CV: Project Management, Change Management, Production Operations (P&L/CAPEX/OPEX), Lean/Six Sigma, KPI design, mezinárodní týmy, automotive electronics.
>
> **Která 3–4 chceš mít nejvíce vidět?** Je něco, co nechceš zdůrazňovat?

### Q4 — Jazyk webu

> Česky / anglicky / dual-language?
>
> *(Tip: pro CZ recruitery stačí čeština. Pro korporáty nebo mezinárodní klienty — angličtina nebo obojí.)*

### Q5 — Témata blogu

> Co z toho tě láká?
> - Jak jsem zachránil projekt rok v prodlení (CanCom)
> - Jak se buduje OEE od 10 % na 75 % na omezeném budgetu (ZF)
> - Proč change management buď vydělává, nebo je ztráta času (TRW)
> - Jak vést 200 lidí, aby KPI nebylo jen papír na nástěnce
> - Rozdíl mezi PM v automotiveu a v IT
>
> **Co dalšího? Témata, ke kterým máš silný názor?**

### Q6 — První case study

> **Který projekt chceš rozebrat jako první** a proč — co je na něm nejzajímavější?

### Q7 — Správa obsahu

> - **Markdown** (píšeš text, commitneš na GitHub → web se sám nasadí) — techničtější, rychlejší
> - **CMS panel** (Decap CMS / Sanity) — formulář v prohlížeči, bez kódu
>
> Jsi ochoten pracovat s GitHubem a textovým editorem?

### Q8 — Doména a formulář

> - Máš doménu (zdeneksuchy.cz nebo jiná)?
> - Kam má jít email z kontaktního formuláře?
> - Chceš ochranu proti spamu (CAPTCHA)?

### Q9 — Vizuální inspirace

> Nasdílej 1–3 weby, které se ti líbí — design, tón, rozložení. Nebo popiš slovně:
> tmavý / světlý? Minimalistický / bohatý? Hodně bílého prostoru / hutné informace?

---

*PRD bude aktualizován po obdržení odpovědí na Q1–Q9.*
