# 🏭 Plastic Industrie Utrecht BV — Website

Gebouwd als statische site met **Decap CMS** voor eenvoudig zelfbeheer.

---

## 📁 Mappenstructuur

```
piu-site/
├── index.html          ← Hoofdpagina (niet aanpassen)
├── netlify.toml        ← Netlify configuratie (niet aanpassen)
├── css/
│   └── style.css       ← Alle stijlen
├── js/
│   └── app.js          ← Website logica
├── admin/
│   ├── index.html      ← CMS beheerpaneel
│   └── config.yml      ← CMS configuratie
├── content/            ← ✏️ HIER past u content aan
│   ├── instellingen.json   ← Bedrijfsgegevens
│   ├── home.json           ← Home pagina content
│   ├── over.json           ← Over Ons pagina
│   ├── diensten.json       ← Diensten pagina
│   ├── contact.json        ← Contact pagina
│   └── portfolio/          ← Portfolio projecten (1 bestand per project)
│       ├── behuizing-pa66.md
│       └── ...
└── images/
    └── uploads/        ← Geüploade afbeeldingen via CMS
```

---

## 🚀 Stap-voor-stap live zetten (gratis, 15 minuten)

### Stap 1 — GitHub account aanmaken
1. Ga naar **github.com** en maak een gratis account aan
2. Klik op **"New repository"** (groene knop rechtsboven)
3. Geef het de naam `piu-website`
4. Kies **Public** (gratis)
5. Klik **"Create repository"**

### Stap 2 — Bestanden uploaden naar GitHub
1. Klik in uw nieuwe repository op **"uploading an existing file"**
2. Sleep alle bestanden en mappen uit de `piu-site` map naar het venster
3. Klik **"Commit changes"**

### Stap 3 — Netlify koppelen
1. Ga naar **netlify.com** en maak een gratis account aan
2. Klik **"Add new site"** → **"Import an existing project"**
3. Kies **GitHub** en selecteer uw `piu-website` repository
4. Alles staat al goed ingesteld — klik **"Deploy site"**
5. Na 1–2 minuten is de site live op een gratis `.netlify.app` adres

### Stap 4 — CMS inloggen activeren (Netlify Identity)
1. Ga in Netlify naar **Site settings** → **Identity**
2. Klik **"Enable Identity"**
3. Ga naar **Identity** → **"Invite users"** en voer uw e-mailadres in
4. U ontvangt een uitnodiging per e-mail — klik de link en stel een wachtwoord in
5. Ga naar **Identity** → **Services** → **Git Gateway** → klik **"Enable Git Gateway"**

### Stap 5 — Eigen domein koppelen (optioneel)
1. Ga in Netlify naar **Domain management** → **"Add custom domain"**
2. Voer `piu.nl` in (of `www.piu.nl`)
3. Volg de instructies om uw DNS aan te passen bij uw domeinprovider
4. Netlify regelt automatisch een gratis SSL-certificaat

---

## ✏️ Content beheren

Ga na activering naar: **uwsite.netlify.app/admin**
(of **piu.nl/admin** als u uw eigen domein heeft gekoppeld)

Log in met uw e-mailadres en wachtwoord.

### Wat u kunt aanpassen:
| Sectie | Wat u kunt wijzigen |
|---|---|
| ⚙️ Site-instellingen | Telefoonnummer, e-mail, adres, social links |
| 🏠 Home pagina | Hero tekst, voordelen, testimonials, statistieken |
| 👥 Over Ons | Verhaal, tijdlijn, missie, onderscheidende punten |
| 🔧 Diensten | Alle 6 diensten + FAQ vragen en antwoorden |
| 📁 Portfolio | Nieuwe projecten toevoegen, bewerken, verwijderen |
| 📬 Contact | Hero tekst, Formspree ID voor formulierverzending |

---

## 📬 Contactformulier instellen (gratis)

1. Ga naar **formspree.io** en maak een gratis account aan
2. Klik **"New Form"** — geef het de naam "PIU Contact"
3. Kopieer uw **Form ID** (bijv. `xrgvpkqb`)
4. Ga in het CMS naar **Contact pagina** → plak het ID bij "Formspree formulier ID"
5. Sla op — het formulier stuurt nu e-mails naar uw inbox

Formspree gratis plan: 50 berichten per maand. Ruim genoeg voor MKB.

---

## 🔄 Updates doorvoeren

Na elke wijziging in het CMS:
- Decap CMS slaat automatisch op in GitHub
- Netlify merkt de wijziging en herbouwt de site (duurt ~30 seconden)
- De site is automatisch bijgewerkt

---

## 📞 Hulp nodig?

Bij vragen over de website: neem contact op met uw webontwikkelaar.
