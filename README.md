# E-Dent Labor - Tulajdonosi Útiterv

Modern, single-page weboldal fogtechnikai labor üzleti tervének bemutatására.

## 🎨 Design

- **Színvilág**: Kék-fehér professzionális téma
- **Tipográfia**: Inter font család
- **Stílus**: Modern, clean, üzleti megközelítés
- **Animációk**: Smooth scroll, fade-in effektek, hover állapotok

## 📁 Fájlstruktúra

```
edent-lab/
├── index.html      # Fő HTML fájl
├── style.css       # Stíluslapok
├── script.js       # JavaScript funkciók
└── README.md       # Dokumentáció
```

## 🚀 GitHub Pages Telepítés

### 1. GitHub Repository létrehozása

```bash
cd /home/ferko/Documents/edent-lab
git init
git add .
git commit -m "Initial commit: E-Dent Labor website"
```

### 2. GitHub-ra feltöltés

```bash
# Hozz létre egy új repository-t a GitHub-on (edent-lab néven)
git remote add origin https://github.com/FELHASZNALONEV/edent-lab.git
git branch -M main
git push -u origin main
```

### 3. GitHub Pages aktiválása

1. Menj a repository Settings oldalára
2. Válaszd a **Pages** menüpontot
3. Source: **Deploy from a branch**
4. Branch: **main** / **root**
5. Mentés

Az oldal 1-2 percen belül elérhető lesz: `https://FELHASZNALONEV.github.io/edent-lab/`

## 🛠️ Helyi Fejlesztés

Egyszerűen nyisd meg az `index.html` fájlt böngészőben, vagy használj egy egyszerű HTTP szervert:

```bash
# Python 3
python3 -m http.server 8000

# Vagy VS Code Live Server extension
```

## ✨ Funkciók

- **Reszponzív design** - mobil, tablet, desktop
- **Smooth scroll navigáció**
- **Interaktív idővonalas megjelenítés** (3 év)
- **Pénzügyi összefoglalók** évekre lebontva
- **Jövőkép szekció** hosszú távú tervekkel
- **Alapelvek bemutatása** kártyás elrendezésben
- **Scroll animációk** (fade-in, slide effektek)
- **Hover effektek** minden interaktív elemen

## 🎯 Tartalmi Szekciók

1. **Hero**: Címoldal statisztikákkal
2. **1. Év**: Túlélés és alapok
3. **2. Év**: Stabilitás és professzionalizáció
4. **3. Év**: Növekedés és pozicionálás
5. **Jövőkép**: 3. év utáni fejlődés
6. **Alapelvek**: 4 kulcsfontosságú elv

## 📝 Testreszabás

### Színek módosítása (CSS változók):

```css
:root {
    --primary-blue: #1E40AF;
    --light-blue: #3B82F6;
    --lighter-blue: #60A5FA;
    /* ... */
}
```

### Tartalom frissítése:

Az `index.html` fájlban könnyen szerkeszthetők a szövegek, számok és listák.

## 🔧 Későbbi Fejlesztési Lehetőségek

- [ ] Blog szekció hozzáadása
- [ ] Kapcsolat űrlap
- [ ] Többnyelvű támogatás (EN/HU)
- [ ] Dark mode
- [ ] Portfólió galéria
- [ ] Kalkulátor árajánlatokhoz
- [ ] Ügyfél testimonial-ok
- [ ] Google Analytics integráció

## 📱 Böngésző Támogatás

- ✅ Chrome/Edge (legújabb 2 verzió)
- ✅ Firefox (legújabb 2 verzió)
- ✅ Safari (legújabb 2 verzió)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## 📄 Licenc

Minden jog fenntartva © 2025 E-Dent Labor

---

**Készítette**: GitHub Copilot  
**Dátum**: 2025. november 12.
