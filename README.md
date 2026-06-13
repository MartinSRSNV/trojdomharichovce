# Trojdom Harichovce — Alpha Reality

Jednostránkový web pre projekt **Trojdom Harichovce** (Alpha Reality, Spišská Nová Ves).

## 🚀 Ako to nahodiť na GitHub Pages

1. Vytvor nový repozitár na GitHube (napr. `trojdom-harichovce`).
2. Nahraj doň **všetky súbory** z tohto priečinka (zachovaj štruktúru priečinkov `assets/`).
3. V repozitári klikni na **Settings → Pages**.
4. Pri "Source" vyber **Deploy from a branch**, branch `main`, priečinok `/ (root)`.
5. Ulož — o minútu bude web dostupný na adrese
   `https://<tvoje-meno>.github.io/trojdom-harichovce/`

### Alternatíva — nahranie cez webové rozhranie (bez Gitu)
- Na GitHube klikni **Add file → Upload files**
- Pretiahni sem celý obsah priečinka (vrátane `assets/` podpriečinka so všetkým obsahom)
- Commit → potom pokračuj krokom 3 vyššie

## 📁 Štruktúra

```
index.html          ← celá stránka (jeden súbor)
assets/
  style.css         ← štýly (farby, typografia, layout)
  img/              ← všetky fotky, logo, favicon
```

## ✏️ Čo môžeš jednoducho zmeniť

- **Texty a ceny** — priamo v `index.html`, sekcie sú oznámkované komentármi (`<!-- PAGE ... -->`).
- **Farby** — na začiatku `assets/style.css` v `:root { ... }` (gold, anthracite atď.).
- **Mapa lokality** — sekcia `#lokalita` používa Google Maps embed pre "Harichovce". Presný pin
  na projekt nájdeš cez tlačidlo "Otvoriť presnú lokalitu v Google Mapách" (odkaz v `index.html`).
- **Fotky** — nahraď súbory v `assets/img/` rovnakým názvom, alebo zmeň `src="..."` v HTML.

## 🌐 Vlastná doména (voliteľné)

Ak chceš pripojiť `www.alphareality.sk` alebo subdomain, v GitHub Pages settings zadaj
"Custom domain" a pridaj DNS CNAME záznam smerujúci na `<tvoje-meno>.github.io`.
