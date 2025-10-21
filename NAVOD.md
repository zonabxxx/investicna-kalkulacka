# 📖 NÁVOD: Ako zdieľať investičnú kalkulačku

## ❌ Prečo to nefunguje cez Google Drive?
Google Drive **neotvorí HTML súbor ako webovú stránku**, ale len zobrazí kód. Potrebujete použiť webhostingovú službu.

---

## ✅ RIEŠENIE 1: NETLIFY DROP (⚡ NAJRÝCHLEJŠIE - 30 sekúnd!)

### Postup:
1. Otvorte: **https://app.netlify.com/drop**
2. Pretiahnite súbor `investicna-kalkulacka.html` do okna prehliadača
3. Netlify vám vytvorí link typu: `https://your-site-123456.netlify.app`
4. Zdieľajte tento link komukoľvek! ✅

### Výhody:
- ✅ Žiadna registrácia
- ✅ Okamžité (30 sekúnd)
- ✅ Zadarmo navždy
- ✅ Automatický HTTPS
- ✅ Rýchle, profesionálne

---

## ✅ RIEŠENIE 2: GITHUB PAGES (🏆 Najlepšie pre dlhodobé projekty)

### Postup:

#### Krok 1: Vytvorte GitHub účet
1. Choďte na **https://github.com**
2. Kliknite **Sign up** (Registrácia zadarmo)
3. Vytvorte účet (email, heslo, používateľské meno)

#### Krok 2: Vytvorte nový repozitár
1. Po prihlásení kliknite na zelené tlačidlo **"New"** (alebo ⊕ vpravo hore → New repository)
2. **Repository name:** `investicna-kalkulacka` (alebo hocičo)
3. Označte **Public** (verejný)
4. Zaškrtnite **"Add a README file"**
5. Kliknite **"Create repository"**

#### Krok 3: Nahrajte HTML súbor
1. V repozitári kliknite **"Add file"** → **"Upload files"**
2. Pretiahnite súbor `investicna-kalkulacka.html` do okna
3. **DÔLEŽITÉ:** Premenujte súbor na `index.html` (musí sa volať presne takto!)
4. Kliknite **"Commit changes"**

#### Krok 4: Zapnite GitHub Pages
1. Kliknite na **"Settings"** (nastavenia repozitára)
2. V ľavom menu nájdite **"Pages"**
3. V sekcii **"Source"** vyberte **"main"** branch
4. Kliknite **"Save"**
5. Po chvíli (1-2 minúty) sa zobrazí zelený banner s vašou URL:
   ```
   https://vase-meno.github.io/investicna-kalkulacka/
   ```

#### Krok 5: Zdieľajte link!
- Tento link môžete poslať komukoľvek
- Funguje na všetkých zariadeniach
- Je to zadarmo navždy! ✅

### Výhody GitHub Pages:
- ✅ Zadarmo navždy
- ✅ Vlastný pekný link
- ✅ Profesionálne
- ✅ Môžete kedykoľvek aktualizovať
- ✅ Automatický HTTPS
- ✅ Funguje na mobile/tablete/PC

---

## ✅ RIEŠENIE 3: VERCEL (Alternatíva k Netlify)

### Postup:
1. Otvorte: **https://vercel.com**
2. Zaregistrujte sa (zadarmo)
3. Kliknite **"Add New"** → **"Project"**
4. Nahrajte súbor alebo prepojte GitHub
5. Dostanete link typu: `https://investicna-kalkulacka.vercel.app`

---

## 🎯 AKÉ RIEŠENIE ZVOLIŤ?

| Riešenie | Rýchlosť | Ťažkosť | Odporúčanie |
|----------|----------|---------|-------------|
| **Netlify Drop** | ⚡ 30 sekúnd | ⭐ Najľahšie | ✅ Pre rýchle zdieľanie |
| **GitHub Pages** | 🕐 5 minút | ⭐⭐ Stredné | ✅ Pre dlhodobé projekty |
| **Vercel** | 🕐 3 minúty | ⭐⭐ Stredné | ✅ Alternatíva |

---

## 💡 BONUS TIP: Lokálne zdieľanie

Ak chcete zdieľať len lokálne (v rovnakej sieti):

### Možnosť A: Python server (ak máte Python)
```bash
# V priečinku so súborom spustite:
python3 -m http.server 8000

# Potom otvorte v prehliadači:
http://localhost:8000/investicna-kalkulacka.html
```

### Možnosť B: Jednoducho poslať súbor emailom
Ak im pošlete súbor emailom, stačí aby si ho stiahli a otvorili dvojklikom v prehliadači.

---

## 📞 KONTAKT / POMOC

Ak máte problém:
1. Skúste najprv **Netlify Drop** (najrýchlejšie)
2. Ak to nefunguje, napíšte mi

---

**Autor:** Investičná kalkulačka  
**Posledná aktualizácia:** Október 2025

