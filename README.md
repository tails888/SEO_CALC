# SEO cenu kalkulators

Šī ir gatava statiska webhost versija. Nav vajadzīgs build process.

## Faili

- `index.html` - kalkulatora app.
- `site.webmanifest` - Android/PWA homescreen dati.
- `assets/icons/` - browser tab, Android un iPhone homescreen ikonas.

## Kā publicēt

Uploadot visu mapes saturu uz webhost root direktoriju.

Svarīgi: `index.html`, `site.webmanifest` un `assets/` mapei jāpaliek vienā līmenī.

## Lokāla pārbaude

```bash
python3 -m http.server 8021
```

Tad atvērt:

```text
http://127.0.0.1:8021/
```
