# Segítség — ismertető oldal

Ez a tároló **egyetlen weboldalt** tartalmaz: a `Segítség` nevű ingyenes,
Android-os segélyhívó alkalmazás ismertetőjét, magyar, német és angol
nyelven.

👉 **[Az oldal megtekintése](https://peterkurtosi.github.io/segitseg/)**

📲 **[Letöltés a Google Playről](https://play.google.com/store/apps/details?id=hu.segitseg.segitseg)** — ingyen
(2026. október 21. óta nyilvános, 1.0.0)

---

## Mi ez az alkalmazás

Nagy gombos segélyhívó telefon-alkalmazás. Az édesanyámnak készült, aki
2026 májusában eltévedt, és nem tudta elmondani, hol van.

- Hat nagy fényképes csempe — a fénykép maga a gomb
- Egy piros gomb, ami SMS-t küld a családnak **a pontos helyzettel**
- A hivatalos segélyhívó számok
- Kapcsolható „nagyi mód": az alkalmazás lesz a kezdőképernyő

**Ingyenes, és az is marad.** Nincs szerver, nincs fiók, nincs
adatgyűjtés: az alkalmazásnak nincs internet-engedélye, és a rendszer
automatikus felhő-mentése is ki van kapcsolva rá.

Az alkalmazás a **Google Play Áruházból** tölthető le (Android 7.0 vagy
újabb). Ebből a tárolóból nem: itt csak az ismertető oldal van.

---

## Ami ebben a tárolóban van

| fájl | mi ez |
|---|---|
| `index.html` | maga az oldal — egyetlen önálló fájl, külső szkript nélkül |
| `LICENSE.md` | licenc (PolyForm Noncommercial 1.0.0) |
| `play/` | a Google Play hivatalos jelvényei (hu/de/en) és a bolti lap QR-kódja |

⚠️ Az `index.html` **generált fájl.** A forrása és az azt előállító
script a projekt saját mappájában él (`10-WEBSITE/index.html` +
`keszit.py`). **Ezt a fájlt itt ne szerkeszd kézzel** — a következő
generálás felülírná.

---

## GitHub Pages beállítása

1. **Settings → Pages**
2. *Source:* **Deploy from a branch**
3. *Branch:* `main`, mappa: `/ (root)` → **Save**
4. Kb. egy perc, és él a fenti cím

---

© 2026 Kürtösi Péter
