# 🔥 Consistency Challenge Tracker

Jednostavna PWA aplikacija za praćenje dnevnih navika tokom 90-dnevnog izazova. Radi offline, instalira se na telefon kao prava aplikacija — bez hostinga, bez plaćanja.

---

## 📱 Funkcionalnosti

- **Dnevni checklist** — označi svaku naviku kao urađenu (✓) ili propuštenu (✕)
- **Quote of the day** — upiši svoju motivaciju za svaki dan ručno
- **Kalendar** — pregled svih dana u mesecu sa color-coded statusom
- **Statistike** — broj urađenih navika i procenat uspešnosti po danu
- **Upravljanje navikama** — dodaj ili ukloni navike po potrebi
- **Offline podrška** — radi bez interneta zahvaljujući Service Worker-u
- **Dark mode** — automatski prati sistemske postavke

---

## 🎯 Podrazumevane navike

| # | Navika |
|---|--------|
| 1 | Probudi se u 5:30 |
| 2 | Hidracija |
| 3 | Pospremi krevet |
| 4 | Molitva + zahvalnost |
| 5 | Sunce |
| 6 | Vežbanje |
| 7 | Hladan tuš |
| 8 | Rad |
| 9 | Bez junk hrane |
| 10 | 10.000+ koraka |
| 11 | Učenje (2 sata) |
| 12 | 2–3l vode |
| 13 | Čitanje 30 min |
| 14 | Nega kože |
| 15 | Planiranje sledećeg dana |
| 16 | Spavaj do 22h |

---

## 🚀 Instalacija na telefon

### Android (Chrome)
1. Otvori app u Chrome-u
2. Meni (⋮) → **Dodaj na početni ekran**
3. Potvrdi — ikonica se pojavljuje kao prava aplikacija

### iPhone (Safari)
1. Otvori app u Safari-u
2. Share dugme (↑) → **Dodaj na početni ekran**
3. Potvrdi

---

## 🛠️ Postavljanje na GitHub Pages

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/TVOJE_IME/NAZIV_REPO.git
git push -u origin master
```

Zatim u GitHub repozitorijumu:
**Settings → Pages → Source: Deploy from branch → master → Save**

App će biti dostupna na: `https://TVOJE_IME.github.io/NAZIV_REPO`

---

## 💾 Podaci

Svi podaci se čuvaju lokalno u `localStorage` na uređaju — nema servera, nema baze podataka, nema slanja podataka nigde. Brisanjem podataka browsera briše se i istorija.

---

## 📁 Struktura projekta

```
consistency-tracker/
├── index.html       # Glavna aplikacija
├── sw.js            # Service Worker (offline podrška)
├── manifest.json    # PWA manifest (naziv, ikonica, boje)
├── icon-192.png     # Ikonica za telefon
└── icon-512.png     # Ikonica za splash screen
```

---

*"It doesn't matter how many times you fall, but how much you get up."*
