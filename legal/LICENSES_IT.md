# Licenze di Terze Parti e Ringraziamenti

Questo documento elenca tutti i componenti di terze parti utilizzati in TexVoice e le rispettive licenze.

---

## Supertonic 3 — Modello Text-to-Speech

**Sviluppatore**: Supertone Inc.
**Licenza**: OpenRAIL-M License
**Sito web**: https://supertone.ai
**Repository**: https://github.com/supertone-inc/supertonic
**Modello**: https://huggingface.co/Supertone/supertonic-3

### Informazioni

Supertonic 3 è un sistema di sintesi vocale ultra-veloce, progettato per prestazioni estreme con un overhead computazionale minimo. Supporta 31 lingue e funziona interamente on-device.

### Riepilogo della Licenza

La Licenza OpenRAIL-M consente l'uso, la modifica e la distribuzione gratuita del modello, soggetta a restrizioni d'uso progettate per prevenire applicazioni dannose.

### Restrizioni d'Uso (OpenRAIL-M Allegato A)

NON puoi utilizzare questo modello per:

- (a) Violare leggi o regolamenti applicabili
- (b) Sfruttare, danneggiare o tentare di danneggiare minori
- (c) Generare o diffondere informazioni false per danneggiare altri
- (d) Generare informazioni personali identificabili per danneggiare individui
- (e) Generare contenuti senza dichiarare che sono generati da macchina (dove il contesto lo richiede)
- (f) Diffamare, denigrare o molestare altri
- (g) Impersonare altri senza consenso (deepfake)
- (h) Prendere decisioni completamente automatizzate che influiscono negativamente sui diritti legali
- (i) Discriminare individui o gruppi basandosi su caratteristiche protette
- (j) Sfruttare vulnerabilità di gruppi specifici
- (k) Fornire consulenza medica o interpretare risultati medici
- (l) Generare contenuti per forze dell'ordine, immigrazione o processi di asilo

**Licenza completa**: https://huggingface.co/Supertone/supertonic-3/blob/main/LICENSE

---

## Kokoro 82M — Modello Text-to-Speech

**Sviluppatore**: hexgrad
**Licenza**: Apache License 2.0
**Modello**: https://huggingface.co/hexgrad/Kokoro-82M

### Informazioni

Kokoro 82M è un modello di sintesi vocale on-device di alta qualità, con 9 lingue e 15 voci. Funziona interamente on-device tramite ONNX Runtime.

La licenza Apache 2.0 è pienamente permissiva: consente uso, modifica e distribuzione libera, senza restrizioni d'uso (a differenza di OpenRAIL-M sopra).

**Licenza completa**: https://huggingface.co/hexgrad/Kokoro-82M/blob/main/LICENSE.md

---

## ZipVoice — Modello di Clonazione Vocale

**Sviluppatore**: k2-fsa
**Licenza**: Apache License 2.0
**Repository**: https://github.com/k2-fsa/ZipVoice
**Modello**: https://huggingface.co/k2-fsa/ZipVoice

### Informazioni

ZipVoice è un modello di clonazione vocale zero-shot. Data una breve registrazione di una voce e la sua trascrizione, genera nuovo parlato in quella voce. Funziona interamente on-device tramite ONNX Runtime; la registrazione vocale non lascia mai il dispositivo.

**Licenza completa**: https://github.com/k2-fsa/ZipVoice/blob/master/LICENSE

---

## Vocos — Vocoder Neurale

**Sviluppatore**: gemelo.ai
**Licenza**: MIT License
**Repository**: https://github.com/gemelo-ai/vocos

### Informazioni

Vocos è il vocoder neurale usato per trasformare le caratteristiche acustiche generate da ZipVoice nella forma d'onda audio finale. Funziona interamente on-device.

---

## Modello Grafemi-Fonemi Inglese

**Sviluppatore**: PeterReid
**Licenza**: Apache License 2.0
**Modello**: https://huggingface.co/PeterReid/graphemes_to_phonemes_en_us

### Informazioni

Un piccolo modello on-device che converte il testo inglese in fonemi, usato per preparare il testo per il motore di clonazione vocale di ZipVoice. Funziona interamente on-device.

---

## ONNX Runtime

**Sviluppatore**: Microsoft Corporation
**Licenza**: MIT License
**Repository**: https://github.com/microsoft/onnxruntime

### Licenza MIT

```
Copyright (c) Microsoft Corporation

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## Expo

**Sviluppatore**: Expo
**Licenza**: MIT License
**Repository**: https://github.com/expo/expo

---

## React Native

**Sviluppatore**: Meta Platforms, Inc.
**Licenza**: MIT License
**Repository**: https://github.com/facebook/react-native

---

## PDFKit

**Sviluppatore**: Apple Inc.
**Licenza**: Proprietaria (inclusa nell'iOS SDK)
**Documentazione**: https://developer.apple.com/documentation/pdfkit

Utilizzato per estrarre testo dai documenti PDF on-device.
