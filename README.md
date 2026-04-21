# Teknisk dokumentation – [Alimento]

## Om projektet

Dette projekt er lavet som en del af Tema 9.
Vi har lavet et dynamisk website med Astro framework, hvor indholdet bliver hentet fra et API vi selv har bygget gennem supabase.

Sitet består af flere sider, hvor brugeren kan:

- se en liste med indhold
- klikke sig videre til en detaljeside

## Links

- GitHub repository: [https://github.com/A-good-case/astro-kode]
- Netlify link: []
- Figma: [https://www.figma.com/design/hLchNMK4Xjs8yALe4gdsPU/A-good-case?m=auto&t=cEvGFVv7HI2vtIBL-6]
- Trello: [https://trello.com/b/07dF6W8A/tema-9-a-good-case]

---

## Projektstruktur

Projektet er i Astro filer. Components, Layout og Pages.

```
Astro-kode/
├── Pages/
├── index.astro
├── productlist.astro
├── productdetails.astro
├── Components/
│   ├── button.astro
│   ├── footer.astro
│   ├── header.astro
│   └──hero.astro
    └──infogrid.astro
    └──udvalgteprodukter.astro
├── layouts/
│   ├── layout.astro
└── README.md
```

### Filbeskrivelser

- **pages** – bruges til at bygge de enkelte sider op
- **components**- Bruges til at bygge elementer som så kan placeres i layout eller pages
- **layout**- Bruges til at fast placeres de elementer som skal bruges globalt, så de bare kan importes i pages.

---

**Flow:**

1. Siden indlæses.

2. JavaScriptet udlæser produktets unikke ID fra URL'en ved hjælp af URLSearchParams.

3. Der laves et specifikt fetch-kald til API'et med dette ID.

4. Produktets detaljer (pris, beskrivelse, billede osv.) indsættes dynamisk i DOM'en.

5. Brugeren præsenteres for den uddybende produktinformation på productdetails.

---

Navngivning
Vi har navngivet vores filer, variabler og funktioner, så de er så selvforklarende som muligt. Dette gør det lettere for alle i gruppen at læse og forstå koden.

Vi har også skrevet navngivet det meste på engelsk for at undgå eventuelle problemer med fillæsning.

Eksempler på variabler

### Eksempler på variabler

```
***
```

### Eksempler på funktioner

```
***
```

Vi har brugt camelCase i JavaScript, fordi det gør koden mere ensartet og lettere at læse.

---

## Kommentarer i koden

Vi har kommenteret de steder i koden, hvor det giver mening.
Fx ved funktioner, fetch-kald og steder hvor der sker DOM-manipulation.

---

## Data og JSON-struktur

Vi henter data fra et API i JSON-format.

**Et objekt kan fx se sådan ud:**

```
***
```

## Git og branches

Vi har brugt GitHub til at samarbejde om projektet.

Vi har arbejdet med branches, så vi ikke sad og ændrede i det samme på samme tid.

Vi navngav branchene med feature.

### Eksempler på branches

```
 "index"
 "Teknisk dokumentation"
```

### Workflow

1. Lave en branch med feature-navn
2. Kode en feature
3. Committe ændringer
4. Pushe til GitHub
5. Merge til main når det virkede

Det gjorde det nemmere at holde styr på, hvem der lavede hvad.

---

## Bæredygtighed

Vi har tænkt bæredygtighed ind i projektet.

**Tiltag:**

- Ingen videoer
- Genbruge af kode

---

## Udfordringer undervejs

---

## Mulige forbedringer

---

---

## Gruppemedlemmer

- Frederik Højvar Bust Hansen
- Gregor Pavlik
- Sofia Nguyen
- William Tien Nguyen

---
