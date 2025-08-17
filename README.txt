Město RPG 3D – nasazení (www)
==============================

1) Vytvoř složku 'www' a vlož do ní:
   - index.html  (plná verze)
   - README.txt  (tento soubor)

2) ZIP složku 'www' do archivu mesto_rpg_www.zip.

Nasazení na Netlify (nejjednodušší):
- Otevři https://app.netlify.com/drop  (přihlaš se).
- Přetáhni soubory nebo složku 'www' do okna.
- Netlify ti automaticky nasadí stránku a dá veřejný odkaz.

Nasazení na GitHub Pages:
- Vytvoř repo na GitHub (např. mesto-rpg).
- Nahraj soubory z 'www' do rootu repozitáře.
- V repo: Settings -> Pages -> Source: main / (root).
- Po pár minutách bude stránka na https://<uzivatel>.github.io/<repo>/

Poznámky:
- Hra načítá Three.js z CDN (internet nutný). Pokud chceš offline, přibal three.min.js lokálně.
- Pro přidání na plochu (Android): otevři stránku v Chrome -> menu -> Přidat na plochu.
