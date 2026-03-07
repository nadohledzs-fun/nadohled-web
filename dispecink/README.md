# nadohled.fun - GitHub Pages

## Struktura souborů

```
/
├── index.html          # Hlavní stránka nadohled.fun
├── CNAME               # Vlastní doména
├── dispecink/
│   └── index.html      # Divine Dispatch (https://nadohled.fun/dispecink/)
└── README.md           # Tento soubor
```

## Nasazení na GitHub Pages

### 1. Vytvořte nový repozitář na GitHubu
- Název: `nadohled.fun` nebo libovolný
- Public repozitář

### 2. Nahrajte soubory
Nahrajte všechny soubory z tohoto adresáře do repozitáře.

### 3. Aktivujte GitHub Pages
1. Jděte do **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **(root)**
4. Klikněte **Save**

### 4. Nastavte vlastní doménu
1. V **Settings** → **Pages** → **Custom domain**
2. Zadejte: `nadohled.fun`
3. Zaškrtněte **Enforce HTTPS**

### 5. DNS nastavení (u vašeho registrátora domény)

Přidejte tyto DNS záznamy:

```
Typ     Název    Hodnota
A       @        185.199.108.153
A       @        185.199.109.153
A       @        185.199.110.153
A       @        185.199.111.153
CNAME   www      <username>.github.io
```

### 6. Vytvořte soubor .nojekyll
V repozitáři vytvořte prázdný soubor `.nojekyll` (GitHub UI: Add file → Create new file → `.nojekyll`)

## Hotovo!

Po pár minutách bude dostupné:
- https://nadohled.fun → Hlavní stránka
- https://nadohled.fun/dispecink/ → Divine Dispatch

## API

Backend zůstává na Wixu:
- API URL: `https://www.divinedelivery.cz/_functions`
- CORS je již nastavený na `*` (povoluje všechny domény)

## Verze

- Divine Dispatch: v20.3
- Datum: Březen 2026
