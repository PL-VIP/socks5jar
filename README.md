# ETNA Vulcan Web Client - Rozpakowany projekt

## 📁 Struktura katalogów

```
web_vulcan_client/
├── lib/                    # Biblioteki
│   └── hebeSigner.js       # Moduł podpisywania dla VULCAN/ETNA
├── public/                 # Pliki statyczne
│   ├── app.js              # Główna aplikacja frontendowa
│   ├── index.html          # Strona główna
│   └── style.css           # Style CSS
├── server.js               # Backend Express.js
├── package.json            # Zależności NPM
└── README.md               # Dokumentacja
```

## 🚀 Szybki start

```bash
# Instalacja zależności
npm install

# Uruchomienie serwera
npm start

# Tryb development
npm run dev
```

## 📝 Opis komponentów

### hebeSigner.js
Biblioteka obsługująca podpisywanie żądań dla systemu VULCAN/ETNA. Odpowiada za autentykację i szyfrowanie danych.

### app.js
Główna logika aplikacji frontendowej. Obsługuje komunikację z backendend i renderowanie UI.

### server.js
Express.js server obsługujący żądania HTTP/HTTPS i serwujący pliki statyczne.

## ✅ Status

- ✅ Rozpakowane z archiwum etna-vulcan-web-client.zip
- ✅ Dodane do repozytorium socks5jar
- ✅ Gotowe do dalszego rozwoju

## 📦 Zależności

- `express` - Web framework
- `nodemon` - Hot reload dla development

Aby je zainstalować:
```bash
npm install
```

---

**Ostatnia aktualizacja:** 2026-09-08
