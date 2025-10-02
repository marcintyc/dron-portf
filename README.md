# Keep Droning - Portfolio Dronowe 🚁 (WOW Edition)

Profesjonalne portfolio dronowe z możliwością dodawania filmów z YouTube oraz lokalnych plików wideo.

## 🔥 WOW Edition - Co nowego?

✨ **Latający dron 🚁** zamiast "O" w "Droning" z animacją lotu 3D!
✨ Gradient czerwono-cyjanowy na całej stronie
✨ Dynamiczne świecące efekty i cienie
✨ Interaktywne karty wideo z kolorowymi borderami
✨ **Białe, czytelne napisy** na wszystkich kartach
✨ Animowany przycisk CTA z efektem ripple
✨ Efekty hover na wszystkich elementach
✨ Gradient navbar z kolorowym borderem
✨ Efekt dymu/śladu za dronem 💨
✨ Backdrop blur na kartach dla lepszego kontrastu

## Funkcje

✅ Nowoczesny, responsywny design
✅ Animacje i efekty parallax
✅ Filtrowanie wideo (YouTube / lokalne)
✅ Sekcja portfolio z grid
✅ Sekcja O mnie z statystykami
✅ Formularz kontaktowy
✅ Smooth scrolling
✅ Mobile-friendly menu

## Jak dodać własne wideo?

### YouTube:
1. Otwórz `index.html`
2. Znajdź sekcję `<div class="video-grid">`
3. Dodaj nową kartę wideo:
```html
<div class="video-card" data-category="youtube">
    <div class="video-wrapper">
        <iframe src="https://www.youtube.com/embed/TU_ID_WIDEO" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="video-info">
        <h3 class="video-title">Tytuł filmu</h3>
        <p class="video-description">Opis filmu</p>
    </div>
</div>
```

### Lokalne wideo:
1. Utwórz folder `videos` w głównym katalogu
2. Dodaj swoje pliki wideo (format .mp4)
3. W `index.html` dodaj:
```html
<div class="video-card" data-category="local">
    <div class="video-wrapper">
        <video controls poster="miniatura.jpg">
            <source src="videos/twoj-film.mp4" type="video/mp4">
            Twoja przeglądarka nie obsługuje odtwarzania wideo.
        </video>
    </div>
    <div class="video-info">
        <h3 class="video-title">Tytuł filmu</h3>
        <p class="video-description">Opis filmu</p>
    </div>
</div>
```

## Personalizacja

### Zmiana kolorów:
W pliku `style.css` zmień zmienne CSS w sekcji `:root`:
```css
:root {
    --primary-color: #00d4ff;
    --secondary-color: #0088ff;
    --dark-bg: #0a0e27;
    /* ... */
}
```

### Zmiana danych kontaktowych:
W pliku `index.html` znajdź sekcję `#contact` i zmień:
- Email
- Telefon
- Lokalizację
- Linki do social media

### Zmiana statystyk:
W sekcji "O mnie" możesz zmienić liczby w `script.js`:
```javascript
const values = [500, 100, 50]; // Godziny lotu, Projekty, Klienci
```

## Struktura plików

```
keep-droning/
│
├── index.html          # Główna strona
├── style.css           # Style CSS
├── script.js           # Skrypty JavaScript
├── README.md           # Instrukcja
│
└── videos/             # Folder na lokalne wideo (do utworzenia)
    ├── drone-video-1.mp4
    └── drone-video-2.mp4
```

## Uruchomienie

Wystarczy otworzyć plik `index.html` w przeglądarce!

Dla lepszego działania możesz użyć lokalnego serwera:
```bash
python -m http.server 8000
```

Następnie odwiedź: `http://localhost:8000`

## Kompatybilność przeglądarek

- ✅ Chrome/Edge (v90+)
- ✅ Firefox (v88+)
- ✅ Safari (v14+)
- ✅ Opera (v76+)

## Technologie

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript
- Google Fonts (Orbitron, Poppins)

---

Stworzone z ❤️ dla miłośników dronów
