# SEO_CALC

Šis ir vienkāršs SEO cenu kalkulators.

Tu atver lapu, saliec klienta situāciju, un kalkulators uzreiz parāda cenu.

Tas ir domāts ātrai sarunai ar klientu, nevis sarežģītai grāmatvedībai.

Repo links: https://github.com/tails888/SEO_CALC

## Īsā versija

Ja gribi tikai palaist kalkulatoru webhostingā, dari šādi:

1. Atver hostingā `public_html` mapi.
2. Ieliec tur šos failus:

```text
index.html
site.webmanifest
assets/
```

3. Atver savu domēnu.
4. Kalkulatoram jāparādās automātiski.

## Mindmap tree

```text
SEO_CALC
├── index.html
│   ├── galvenais kalkulators
│   ├── dizains
│   ├── slīdņi
│   ├── cenas
│   └── kopēšanas poga klienta tekstam
│
├── site.webmanifest
│   ├── app nosaukums telefonā
│   ├── Android home screen info
│   ├── app krāsas
│   └── norāde, ar kuru lapu app sākas
│
└── assets/
    └── icons/
        ├── browser tab logo
        ├── iPhone home screen logo
        ├── Android 192x192 logo
        └── Android 512x512 logo
```

## Kas ir šis kalkulators

Tas ir web kalkulators SEO pakalpojumu cenu aprēķinam.

Ar to var ātri nosaukt cenu par:

- nelielu SEO darbu;
- SEO auditu;
- Google Business Profile darbu;
- landing page vai service page darbu;
- mēneša SEO sadarbību;
- papildus SEO opcijām.

## Kā viņu izmantot ikdienā

1. Atver kalkulatora linku.
2. Izvēlies, vai tas ir vienreizējs darbs vai mēneša sadarbība.
3. Izvēlies klienta tipu:

```text
Jauns klients
Esošs klients
```

4. Ar slīdni izvēlies darba apjomu.
5. Ja vajag, pieliec papildopcijas.
6. Ja darbs ir steidzams, pieliec prioritātes uzcenojumu.
7. Ja gribi iedot labāku cenu, noregulē atlaidi.
8. Skaties gala cenu.
9. Spied `Kopēt klientam`.
10. Ielīmē tekstu WhatsApp, e-pastā vai čatā ar klientu.

## Kā publicēt uz Hostinger vai cita webhosta

Tev nav vajadzīgs nekāds build process.

Tev nav vajadzīgs backend.

Tev nav vajadzīga datubāze.

Vienkārši ieliec failus webhostā.

Pareizā struktūra hostingā:

```text
public_html/
├── index.html
├── site.webmanifest
└── assets/
    └── icons/
        ├── apple-touch-icon.png
        ├── favicon-32x32.png
        ├── icon-192.png
        ├── icon-512.png
        └── seo-calc-logo.png
```

Svarīgi: `index.html`, `site.webmanifest` un `assets` mapei jābūt vienā līmenī.

Ja `assets` mape ir ielikta citur, logo var nerādīties.

## Kā pārbaudīt, vai viss ir pareizi

Pēc upload hostingā:

1. Atver savu domēnu.
2. Ja kalkulators parādās, `index.html` ir pareizā vietā.
3. Paskaties browser tab. Tur jāparādās mazajam logo.
4. Telefonā atver lapu un pārbaudi, vai dizains izskatās normāli.
5. Pamēģini uzlikt lapu uz iPhone home screen.

## Kā pievienot uz iPhone Home Screen

Šādi kalkulatoru var lietot kā mazu app ikonu telefonā.

1. Atver Safari uz iPhone.
2. Ievadi kalkulatora web adresi.
3. Kad lapa atveras, spied `Share` pogu.

Tā ir poga ar kvadrātu un bultiņu uz augšu.

4. Ritini uz leju.
5. Spied `Add to Home Screen`.
6. Pārbaudi nosaukumu. Tam vajadzētu būt `SEO_CALC`.
7. Spied `Add`.
8. Tagad iPhone sākuma ekrānā būs kalkulatora ikona.

Pēc tam vari atvērt kalkulatoru kā parastu app.

## Ja iPhone ikona nerādās pareizi

Pārbaudi šīs lietas:

```text
index.html
site.webmanifest
assets/icons/apple-touch-icon.png
```

Visiem šiem failiem jābūt pareizā vietā.

`index.html` failā ir šī rinda:

```html
<link rel="apple-touch-icon" href="assets/icons/apple-touch-icon.png" sizes="180x180">
```

Ja `apple-touch-icon.png` nav tajā vietā, iPhone nevarēs paņemt pareizo ikonu.

## Kā pievienot uz Android Home Screen

1. Atver kalkulatoru Chrome pārlūkā.
2. Spied trīs punktus augšā.
3. Izvēlies `Add to Home screen` vai `Install app`.
4. Apstiprini.
5. Android sākuma ekrānā parādīsies SEO_CALC ikona.

Android izmanto `site.webmanifest` failu un ikonas no `assets/icons/` mapes.

## Biežākās kļūdas

### Lapa neatveras

Visticamāk `index.html` nav ielikts `public_html` mapē.

### Logo nerādās browser tabā

Pārbaudi, vai eksistē:

```text
assets/icons/favicon-32x32.png
```

### iPhone nerāda pareizo ikonu

Pārbaudi, vai eksistē:

```text
assets/icons/apple-touch-icon.png
```

### Android neuzvedas kā app

Pārbaudi, vai eksistē:

```text
site.webmanifest
assets/icons/icon-192.png
assets/icons/icon-512.png
```

### Dizains izskatās salūzis

Visticamāk nav uploadota visa `assets` mape vai faili nav vienā līmenī ar `index.html`.

## Kas jāatceras

Šis projekts ir statiska mājaslapa.

Tas nozīmē:

- nav servera koda;
- nav datubāzes;
- nav instalācijas;
- nav build komandas;
- var hostot gandrīz jebkurā webhostingā.

Vienkārši upload failus un atver domēnu.
