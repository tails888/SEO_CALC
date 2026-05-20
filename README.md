# SEO cenu kalkulators

Vienkāršs SEO cenu kalkulators, ko var ātri atvērt un izmantot sarunā ar klientu.

Kalkulators palīdz ātri saprast aptuveno cenu par SEO darbu, bez liekas rēķināšanas ar kalkulatoru vai pierakstiem.

## Ko ar šo var izdarīt

Ar kalkulatoru var:

- izvēlēties vienreizēju SEO darbu vai mēneša sadarbību;
- norādīt darba apjomu stundās;
- rēķināt arī 30 minūtes kā mazāko darba apjomu;
- izvēlēties klienta tipu: jauns klients vai esošs klients;
- esošam klientam automātiski iedot sākuma atlaidi;
- pašam regulēt atlaidi līdz 90%;
- pielikt prioritātes uzcenojumu, ja darbs ir steidzams;
- pievienot papildopcijas, piemēram, Google Business Profile postus, Search Console setup, Schema markup, landing page un citus darbus;
- uzreiz redzēt gala cenu;
- nokopēt klientam vienkāršu tekstu ar cenu un īsu paskaidrojumu.

## Kam tas ir domāts

Šis kalkulators ir domāts SEO speciālistam, freelancerim vai aģentūrai, lai ātri nosauktu cenu klientam.

Galvenais mērķis nav izveidot sarežģītu finanšu sistēmu. Galvenais mērķis ir ātri, saprotami un profesionāli parādīt cenu.

## Dizains

Kalkulators ir veidots kā melnbalta, minimālistiska web app.

Desktop versijā ir plašs app izkārtojums ar kalkulatoru kreisajā pusē un kopsavilkumu labajā pusē.

Mobilajā versijā kalkulators ir sadalīts ērtās kartēs, lai to var lietot no iPhone vai Android telefona.

## Webhost struktūra

Publicēšanai vajadzīgi šie faili:

```text
index.html
site.webmanifest
assets/
```

`index.html` ir galvenais kalkulatora fails.

`site.webmanifest` palīdz telefonam un pārlūkam saprast, kā šo lapu rādīt kā app.

`assets/` mapē ir ikonas browser tabam, Android un iPhone home screen ikonai.

## Kā publicēt

Ja izmanto Hostinger vai citu parastu webhostingu, ieliec šos failus `public_html` mapē:

```text
index.html
site.webmanifest
assets/
```

Pēc tam atver savu domēnu. Kalkulatoram vajadzētu atvērties automātiski.

## Telefona ikona

Kalkulatoram ir sagatavotas ikonas:

- browser tab ikonai;
- iPhone Add to Home Screen ikonai;
- Android home screen ikonai.

Lai tas strādātu, `site.webmanifest` un `assets/` mapei jāpaliek blakus `index.html`.

## Pašreizējais statuss

Kalkulators jau ir gatavs lietošanai kā statiska web lapa.

Nav vajadzīgs backend, datubāze vai build process. Pietiek ar parastu webhostingu.

## Repo links

https://github.com/tails888/SEO_CALC
