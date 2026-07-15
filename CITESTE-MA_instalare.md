# APARM Diriginte — Kit PWA (instalare pe telefon, tabletă și PC)

## Ce conține kitul
- `index.html` — aplicația completă
- `manifest.webmanifest` — cartea de identitate a aplicației (nume, iconițe, culori)
- `sw.js` — motorul offline (service worker)
- `icons/` — iconițele generate din logo-ul APARM

## PASUL 1 — Găzduire gratuită pe GitHub Pages (o singură dată, ~15 min)
1. Creează cont gratuit pe **github.com** (dacă nu ai).
2. Sus dreapta: **+** → **New repository** → nume: `aparm-app` → bifează **Public** → **Create repository**.
3. Pe pagina repository-ului: **uploading an existing file** → trage TOATE fișierele și folderul `icons` din acest kit → **Commit changes**.
   (Dacă folderul icons nu se urcă tras direct: intră în repo → Add file → Upload files → trage cele 3 PNG-uri, iar la numele fiecăruia scrie `icons/` în față, ex: `icons/icon-192.png`.)
4. **Settings** → meniul din stânga **Pages** → la „Branch" alege **main** și **/ (root)** → **Save**.
5. După 1–2 minute, sus îți apare adresa aplicației, de forma:
   `https://NUMELE-TAU.github.io/aparm-app/`
   Deschide-o — aplicația ta e live.

## PASUL 2 — Instalarea
- **Android (telefon/tabletă):** deschide adresa în Chrome → apare bannerul „Adaugă APARM pe ecranul de pornire" sau meniul ⋮ → **Instalează aplicația**. Gata: iconiță, ecran complet, merge OFFLINE.
- **Windows (PC):** deschide adresa în Chrome sau Edge → în bara de adresă apare iconița de instalare (monitor cu săgeată) → **Instalare**. Aplicația apare în Start Menu, cu fereastra ei proprie.
- **iPhone/iPad:** Safari → Partajare → **Adaugă la ecranul principal**.

## PASUL 3 — Mutarea datelor existente (o singură dată)
Datele din varianta veche (fișierul local) NU se mută singure — browserul le ține separat pe „adrese" diferite:
1. În varianta VECHE: Setări → **Backup complet (.zip)** → salvează fișierul.
2. În varianta INSTALATĂ: Setări → **Restaurează backup complet** → alege zip-ul.
Repetă pentru fiecare șantier. De acum lucrezi doar în varianta instalată.

## PASUL 4 (opțional) — APK real pentru Android
1. Intră pe **pwabuilder.com** → lipește adresa ta `https://...github.io/aparm-app/` → **Start**.
2. **Package for stores** → **Android** → descarcă pachetul (conține APK-ul semnat + instrucțiuni).
3. Trimite APK-ul pe telefon și instalează-l (acceptă „surse necunoscute" la prima instalare).
   Play Store (dacă vei dori vreodată distribuție publică): cont Google Play Console, taxă unică 25$.

## Actualizări viitoare
Când primești o versiune nouă a aplicației: în GitHub → deschide `index.html` → iconița creion NU e necesară — mai simplu: **Add file → Upload files** → urci noul `index.html` peste cel vechi → Commit. Toate dispozitivele instalate primesc automat versiunea nouă la următoarea deschidere cu internet. Datele NU se pierd la actualizări (stau în dispozitiv, nu în fișier).

## De reținut
- Public pe GitHub e doar PROGRAMUL (gol). Datele șantierelor tale rămân exclusiv pe dispozitivele tale.
- Backup-ul complet .zip rămâne obiceiul de aur — mai ales înainte de a schimba telefonul.
