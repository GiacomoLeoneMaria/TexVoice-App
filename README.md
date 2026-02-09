<p align="center">
  <img src="assets/icon.png" alt="TexVoice Logo" width="400"/>
</p>

<p align="center">
  <strong>Transform Text into Audiobooks. 100% Offline. No Login Required.</strong><br/>
</p>

---

## Disponibilità / Availability

<p align="center">
  <a href="https://apps.apple.com/app/texvoice">
    <img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on App Store" height="50"/>
  </a>
</p>

| Platform | Status |
|----------|--------|
| **iOS (iPhone / iPad)** | [App Store](https://apps.apple.com/it/app/texvoice/id6758604969?l=en-GB) |

---

# TexVoice

## Panoramica / Overview

**🇮🇹 Italiano:**
TexVoice è un'applicazione iOS che trasforma qualsiasi testo o PDF in audiolibri di alta qualità utilizzando voci AI naturali. Tutto avviene localmente sul dispositivo: nessuna connessione internet richiesta, nessun account da creare, nessun dato inviato a server esterni.

**🇬🇧 English:**
TexVoice is an iOS application that transforms any text or PDF into high-quality audiobooks using natural AI voices. Everything happens locally on your device: no internet connection required, no account to create, no data sent to external servers.

---

## Caratteristiche Principali / Key Features

**🇮🇹** L'applicazione è progettata per offrire un'esperienza completa di creazione e ascolto di audiolibri, con un focus su privacy e semplicità.

**🇬🇧** The application is designed to offer a complete audiobook creation and listening experience, with a focus on privacy and simplicity.

---

### Privacy e Offline / Privacy & Offline

**🇮🇹 Italiano:**
- **100% Offline**: Tutta l'elaborazione avviene sul dispositivo. Nessun server, nessun cloud
- **Nessun Login**: Inizia subito senza creare account o fornire email
- **Nessun Tracciamento**: I tuoi dati rimangono sul tuo dispositivo

**🇬🇧 English:**
- **100% Offline**: All processing happens on-device. No servers, no cloud
- **No Login Required**: Start immediately without creating accounts or providing email
- **No Tracking**: Your data stays on your device

---

### Conversione Testo in Audio / Text to Audio Conversion

**🇮🇹 Italiano:**
- **Importazione PDF**: Carica documenti PDF e estrai automaticamente il testo
- **Scrittura Diretta**: Incolla o scrivi direttamente il testo da convertire
- **10 Voci AI**: 5 voci femminili (Aurora, Sofia, Emma, Luna, Stella) e 5 maschili (Marco, Luca, Leo, Alex, Matteo)
- **5 Lingue Supportate**: Inglese, Spagnolo, Francese, Portoghese e Coreano

**🇬🇧 English:**
- **PDF Import**: Upload PDF documents and automatically extract text
- **Direct Writing**: Paste or directly write the text to convert
- **10 AI Voices**: 5 female voices (Aurora, Sofia, Emma, Luna, Stella) and 5 male (Marco, Luca, Leo, Alex, Matteo)
- **5 Languages Supported**: English, Spanish, French, Portuguese, and Korean

---

### Gestione Capitoli / Chapter Management

**🇮🇹 Italiano:**
- **Rilevamento Automatico**: L'app identifica automaticamente i capitoli nei testi
- **Editor Visuale**: Modifica, rinomina, unisci o dividi i capitoli come preferisci
- **Anteprima Contenuto**: Visualizza un'anteprima del contenuto di ogni capitolo
- **Conteggio Parole**: Ogni capitolo mostra il numero di parole per stimare la durata
- **Divisione Intelligente**: Per testi lunghi, l'app divide automaticamente in parti gestibili

**🇬🇧 English:**
- **Automatic Detection**: The app automatically identifies chapters in texs
- **Visual Editor**: Edit, rename, merge, or split chapters as you prefer
- **Content Preview**: View a preview of each chapter's content
- **Word Count**: Each chapter shows word count to estimate duration
- **Smart Splitting**: For long texts, the app automatically splits into manageable parts

---

### Libreria Personale / Personal Library

**🇮🇹 Italiano:**
- **Salvataggio Locale**: Gli audiolibri generati vengono salvati nella tua libreria personale
- **Ascolto Offline**: Ascolta i tuoi audiolibri ovunque, senza connessione internet
- **Metadati Completi**: Ogni audiolibro mostra titolo, autore, durata, data creazione e voce utilizzata

**🇬🇧 English:**
- **Local Storage**: Generated audiobooks are saved to your personal library
- **Offline Listening**: Listen to your audiobooks anywhere, without internet connection
- **Complete Metadata**: Each audiobook shows title, author, duration, creation date and voice used

---

### Interfaccia Utente / User Interface

**🇮🇹 Italiano:**
- **Tema Dark/Light**: Supporto automatico per la modalità chiara e scura del sistema
- **Processo in 3 Step**: Carica → Scegli Voce → Ascolta
- **Feedback Visivo**: Barre di progresso durante la generazione dell'audio

**🇬🇧 English:**
- **Dark/Light Theme**: Automatic support for system light and dark mode
- **3-Step Process**: Upload → Choose Voice → Listen
- **Visual Feedback**: Progress bars during audio generation

---

### Internazionalizzazione (i18n) / Internationalization

**🇮🇹 Italiano:**
- **Supporto Multi-lingua**: L'interfaccia è tradotta in più lingue e si adatta automaticamente alla lingua del dispositivo
- **Lingue Supportate**: Italiano, Inglese, Tedesco, Portoghese, Giapponese, Coreano, Francese, Spagnolo, Cinese

**🇬🇧 English:**
- **Multi-language Support**: The interface is translated into multiple languages and automatically adapts to the device's language
- **Supported Languages**: Italian, English, German, Portuguese, Japanese, Korean, French, Spanish, Chinese

---

## Tecnologie Utilizzate / Technologies Used

**🇮🇹** L'applicazione è stata costruita utilizzando **React Native** con il framework **Expo**, con moduli nativi personalizzati per la sintesi vocale.

**🇬🇧** The application was built using **React Native** with the **Expo** framework, with custom native modules for speech synthesis.

---

### Framework Core / Core Framework

**🇮🇹 Italiano:**
- **React Native**: Per lo sviluppo dell'applicazione iOS
- **Expo**: Per semplificare lo sviluppo, il building e l'accesso alle API native
- **Expo Router**: Per la navigazione file-based tra le schermate

**🇬🇧 English:**
- **React Native**: For iOS application development
- **Expo**: To simplify development, building, and access to native APIs
- **Expo Router**: For file-based navigation between screens

---

### Sintesi Vocale / Speech Synthesis

**🇮🇹 Italiano:**
- **ONNX Runtime**: Motore di inferenza per l'esecuzione dei modelli di sintesi vocale
- **Modulo Nativo Personalizzato**: `supertonic-tts` - modulo Expo nativo Swift per la sintesi text-to-speech ad alte prestazioni
- **Elaborazione On-Device**: Tutta la sintesi avviene localmente senza connessione internet

**🇬🇧 English:**
- **ONNX Runtime**: Inference engine for running speech synthesis models
- **Custom Native Module**: `supertonic-tts` - native Expo Swift module for high-performance text-to-speech synthesis
- **On-Device Processing**: All synthesis happens locally without internet connection

---

### Estrazione PDF / PDF Extraction

**🇮🇹 Italiano:**
- **PDFKit**: Framework nativo Apple per l'elaborazione dei PDF
- **Modulo Nativo Personalizzato**: `pdf-text-extract` - modulo Expo nativo Swift per l'estrazione del testo dai PDF
- **Estrazione Metadati**: Recupera automaticamente titolo, autore e numero di pagine

**🇬🇧 English:**
- **PDFKit**: Native Apple framework for PDF processing
- **Custom Native Module**: `pdf-text-extract` - native Expo Swift module for extracting text from PDFs
- **Metadata Extraction**: Automatically retrieves title, author, and page count

---

### UI & Componenti / UI & Components

**🇮🇹 Italiano:**
- **React Native Core Components**: Componenti base per costruire l'interfaccia utente
- **`@expo/vector-icons`**: Per una vasta libreria di icone personalizzabili
- **`expo-image`**: Per la gestione ottimizzata delle immagini
- **`expo-blur`**: Per effetti di sfocatura nell'interfaccia
- **`expo-linear-gradient`**: Per gradienti di colore nei componenti UI
- **`expo-haptics`**: Per feedback tattile durante le interazioni
- **`react-native-reanimated`**: Per animazioni fluide e performanti
- **`react-native-gesture-handler`**: Per gestire gesture complesse
- **`react-native-safe-area-context`**: Per gestire correttamente i layout su dispositivi con notch

**🇬🇧 English:**
- **React Native Core Components**: Base components for building the user interface
- **`@expo/vector-icons`**: For a vast library of customizable icons
- **`expo-image`**: For optimized image handling
- **`expo-blur`**: For blur effects in the interface
- **`expo-linear-gradient`**: For color gradients in UI components
- **`expo-haptics`**: For tactile feedback during interactions
- **`react-native-reanimated`**: For smooth and performant animations
- **`react-native-gesture-handler`**: To handle complex gestures
- **`react-native-safe-area-context`**: To properly manage layouts on devices with notch

---

### Audio & Media / Audio & Media

**🇮🇹 Italiano:**
- **`expo-av`**: Per la riproduzione audio degli audiolibri generati
- **`expo-file-system`**: Per la gestione dei file audio e il salvataggio nella libreria

**🇬🇧 English:**
- **`expo-av`**: For audio playback of generated audiobooks
- **`expo-file-system`**: For audio file management and saving to library

---

### Archiviazione Locale / Local Storage

**🇮🇹 Italiano:**
- **`@react-native-async-storage/async-storage`**: Per persistere i dati utente (libreria, impostazioni) direttamente sul dispositivo

**🇬🇧 English:**
- **`@react-native-async-storage/async-storage`**: To persist user data (library, settings) directly on the device

---

### API Native & Servizi / Native APIs & Services

**🇮🇹 Italiano:**
- **`expo-document-picker`**: Per selezionare e importare documenti PDF dal dispositivo
- **`expo-localization`**: Per rilevare la lingua e le impostazioni regionali del dispositivo
- **`expo-splash-screen`**: Per il controllo programmatico della splash screen
- **`expo-status-bar`**: Per controllare l'aspetto della status bar del sistema

**🇬🇧 English:**
- **`expo-document-picker`**: To select and import PDF documents from the device
- **`expo-localization`**: To detect the device's language and regional settings
- **`expo-splash-screen`**: For programmatic control of the splash screen
- **`expo-status-bar`**: To control the system status bar appearance

---

## Roadmap / Coming Soon

**🇮🇹 Italiano:**
- 🔜 **Voice Cloning**: Clona la tua voce per narrare i tuoi audiolibri
- 🔜 **Nuove Lingue**: Supporto per altre lingue nella sintesi vocale
- 🔜 **Nuove Voci**: Ulteriori voci AI con diversi stili e accenti
- 🔜 **Supporto Documenti**: Importazione di altri formati (EPUB, DOCX, TXT)
- 🔜 **Android**: Versione per dispositivi Android

**🇬🇧 English:**
- 🔜 **Voice Cloning**: Clone your voice to narrate your audiobooks
- 🔜 **New Languages**: Support for additional languages in speech synthesis
- 🔜 **New Voices**: Additional AI voices with different styles and accents
- 🔜 **Document Support**: Import of other formats (EPUB, DOCX, TXT)
- 🔜 **Android**: Version for Android devices

---

## 🙏 Ringraziamenti e Riferimenti / Acknowledgments & References

### Supertonic 2 — Text-to-Speech Model

<p align="center">
  <a href="https://huggingface.co/Supertone/supertonic-2"><img src="https://img.shields.io/badge/🤗_Model-Hugging_Face-yellow?style=for-the-badge" alt="Model"></a>
  <a href="https://github.com/supertone-inc/supertonic"><img src="https://img.shields.io/badge/💻_Code-GitHub-black?style=for-the-badge&logo=github" alt="Code"></a>
</p>

**🇮🇹 Italiano:**
Il cuore di TexVoice è alimentato da [Supertonic 2](https://github.com/supertone-inc/supertonic), un modello TTS ultra-veloce e multilingue sviluppato da [Supertone Inc](https://supertone.ai/). Supertonic è progettato per l'elaborazione on-device con prestazioni eccezionali — fino a **167× più veloce del tempo reale** — utilizzando solo 66M di parametri.

**🇬🇧 English:**
The heart of TexVoice is powered by [Supertonic 2](https://github.com/supertone-inc/supertonic), an ultra-fast, multilingual TTS model developed by [Supertone Inc](https://supertone.ai/). Supertonic is designed for on-device processing with exceptional performance — up to **167× faster than real-time** — using only 66M parameters.

- **License**: [OpenRAIL-M](https://huggingface.co/Supertone/supertonic-2/blob/main/LICENSE)
- **Copyright**: © 2026 Supertone Inc.

---

### ONNX Runtime

**🇮🇹 Italiano:**
L'inferenza dei modelli TTS è eseguita grazie a [ONNX Runtime](https://onnxruntime.ai/), il motore di inferenza cross-platform ad alte prestazioni sviluppato da Microsoft.

**🇬🇧 English:**
TTS model inference is powered by [ONNX Runtime](https://onnxruntime.ai/), the high-performance cross-platform inference engine developed by Microsoft.

- **License**: [MIT License](https://github.com/microsoft/onnxruntime/blob/main/LICENSE)
- **Copyright**: © Microsoft Corporation

---

## 🤝 Contributi / Contributing

**🇮🇹** I contributi sono benvenuti! Sentiti libero di aprire issue o pull request.

**🇬🇧** Contributions are welcome! Feel free to open issues or pull requests.

---

## Contatti / Contact

**🇮🇹** Per domande o supporto, contatta: [giacomoleonemariadev@gmail.com](mailto:giacomoleonemariadev@gmail.com), o apri una Issue su GitHub.

**🇬🇧** For questions or support, contact: [giacomoleonemariadev@gmail.com](mailto:giacomoleonemariadev@gmail.com), or open an Issue on GitHub.

---

<p align="center">
  Made with ❤️ by Giacomo Cavallini
</p>
