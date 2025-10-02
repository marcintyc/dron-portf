# Keep Droning - Dostępne Wersje 🎨

Portfolio dronowe ma 3 różne wersje kolorystyczne. Każda na osobnym branchu!

## 🔥 WOW Edition (wow-variation)
**Branch:** `wow-variation`

### Cechy:
- 🔴 **Czerwone "O"** w "Droning" z pulsującymi animacjami 3D
- 🌈 Gradient **czerwono-cyjanowy** (#ff0066 → #00d4ff)
- ✨ Świecące efekty i cienie na wszystkich elementach
- 🎯 Dynamiczne karty z kolorowymi gradientowymi borderami
- 💫 Animowany przycisk CTA z efektem ripple
- 🎪 Navbar z gradientowym borderem
- 🎨 Intensywne kolory i efekty WOW

**Idealny dla:** Odważnych projektów, portfolio artystyczne, maksymalny efekt WOW!

```bash
git checkout wow-variation
```

---

## ☀️ Light Theme (light-theme)
**Branch:** `light-theme`

### Cechy:
- ⚪ Białe tło (#ffffff, #f5f7fa)
- 🔵 Niebieski akcent (#0066cc → #0099ff)
- 📝 Ciemny tekst dla lepszej czytelności
- 🎴 Białe karty z subtelnymi cieniami
- 🌤️ Jasny, świeży design
- 💼 Profesjonalny wygląd

**Idealny dla:** Korporacje, profesjonalne portfolio, jasne środowiska

```bash
git checkout light-theme
```

---

## 🌙 Dark Theme - Original (cursor/build-keep-droning-video-portfolio-e2b6)
**Branch:** `cursor/build-keep-droning-video-portfolio-e2b6`

### Cechy:
- ⚫ Ciemne tło (#0a0e27, #050811)
- 💙 Cyjanowy akcent (#00d4ff → #0088ff)
- ⭐ Klasyczny futurystyczny design
- 🌌 Efekty przestrzenne i parallax
- 🎮 Gaming/Tech vibe
- 🚀 Oryginalny design

**Idealny dla:** Tech portfolio, gaming projects, klasyczny dark mode

```bash
git checkout cursor/build-keep-droning-video-portfolio-e2b6
```

---

## Jak wybrać wersję?

1. **Wybierz branch:**
   ```bash
   git checkout [nazwa-brancha]
   ```

2. **Otwórz w przeglądarce:**
   ```bash
   # Opcjonalnie uruchom lokalny serwer
   python -m http.server 8000
   ```

3. **Zobacz w akcji:**
   Otwórz http://localhost:8000 lub bezpośrednio `index.html`

---

## Porównanie Szybkie

| Feature | WOW Edition | Light Theme | Dark Original |
|---------|-------------|-------------|---------------|
| Czerwone "O" | ✅ | ❌ | ❌ |
| Tło | Ciemne | Jasne | Ciemne |
| Główny kolor | Czerwony+Cyan | Niebieski | Cyan |
| Intensywność | 🔥🔥🔥 | ⭐⭐ | ⭐⭐⭐ |
| Profesjonalizm | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| Efekt WOW | 🚀🚀🚀🚀🚀 | ⭐⭐ | ⭐⭐⭐ |

---

## Mix & Match

Możesz też łączyć elementy z różnych wersji! Wszystkie style są w `style.css`, a główne kolory w sekcji `:root`.

### Przykład - Zmień kolory:
```css
:root {
    --primary-color: #twój-kolor;
    --secondary-color: #twój-kolor-2;
    /* ... */
}
```

---

**Tip:** Możesz mieć wszystkie 3 wersje lokalnie i przełączać się między nimi używając `git checkout`!
