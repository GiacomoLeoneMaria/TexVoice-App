# Third-Party Licenses and Acknowledgments

This document lists all third-party components used in TexVoice and their respective licenses.

---

## Supertonic 3 — Text-to-Speech Model

**Developer**: Supertone Inc.
**License**: OpenRAIL-M License
**Website**: https://supertone.ai
**Repository**: https://github.com/supertone-inc/supertonic
**Model**: https://huggingface.co/Supertone/supertonic-3

### About

Supertonic 3 is a lightning-fast, on-device text-to-speech system designed for extreme performance with minimal computational overhead. It supports 31 languages and runs entirely on-device.

### License Summary

The OpenRAIL-M License allows free use, modification, and distribution of the model, subject to use-based restrictions designed to prevent harmful applications.

### Use Restrictions (OpenRAIL-M Attachment A)

You may NOT use this model to:

- (a) Violate any applicable laws or regulations
- (b) Exploit, harm, or attempt to harm minors
- (c) Generate or disseminate false information to harm others
- (d) Generate personal identifiable information to harm individuals
- (e) Generate content without disclosing it is machine-generated (where context requires)
- (f) Defame, disparage, or harass others
- (g) Impersonate others without consent (deepfakes)
- (h) Make fully automated decisions adversely impacting legal rights
- (i) Discriminate against individuals or groups based on protected characteristics
- (j) Exploit vulnerabilities of specific groups
- (k) Provide medical advice or interpret medical results
- (l) Generate content for law enforcement, immigration, or asylum processes

**Full License**: https://huggingface.co/Supertone/supertonic-3/blob/main/LICENSE

---

## Kokoro 82M — Text-to-Speech Model

**Developer**: hexgrad
**License**: Apache License 2.0
**Model**: https://huggingface.co/hexgrad/Kokoro-82M

### About

Kokoro 82M is a high-quality, on-device text-to-speech model supporting 9 languages and 15 voices. Runs entirely on-device via ONNX Runtime.

The Apache 2.0 License is fully permissive: it allows free use, modification, and distribution, with no use-based restrictions (unlike OpenRAIL-M above).

**Full License**: https://huggingface.co/hexgrad/Kokoro-82M/blob/main/LICENSE.md

---

## ZipVoice — Voice Cloning Model

**Developer**: k2-fsa
**License**: Apache License 2.0
**Repository**: https://github.com/k2-fsa/ZipVoice
**Model**: https://huggingface.co/k2-fsa/ZipVoice

### About

ZipVoice is a zero-shot voice cloning text-to-speech model. Given a short recording of a voice and its transcript, it generates new speech in that voice. Runs entirely on-device via ONNX Runtime; the recorded voice sample never leaves the device.

**Full License**: https://github.com/k2-fsa/ZipVoice/blob/master/LICENSE

---

## Vocos — Neural Vocoder

**Developer**: gemelo.ai
**License**: MIT License
**Repository**: https://github.com/gemelo-ai/vocos

### About

Vocos is the neural vocoder used to turn ZipVoice's generated acoustic features into the final audio waveform. Runs entirely on-device.

---

## English Graphemes-to-Phonemes Model

**Developer**: PeterReid
**License**: Apache License 2.0
**Model**: https://huggingface.co/PeterReid/graphemes_to_phonemes_en_us

### About

A small on-device model that converts English text into phonemes, used to prepare text for ZipVoice's voice cloning engine. Runs entirely on-device.

---

## ONNX Runtime

**Developer**: Microsoft Corporation
**License**: MIT License
**Repository**: https://github.com/microsoft/onnxruntime

### MIT License

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

**Developer**: Expo
**License**: MIT License
**Repository**: https://github.com/expo/expo

---

## React Native

**Developer**: Meta Platforms, Inc.
**License**: MIT License
**Repository**: https://github.com/facebook/react-native

---

## PDFKit

**Developer**: Apple Inc.
**License**: Proprietary (included in iOS SDK)
**Documentation**: https://developer.apple.com/documentation/pdfkit

Used for extracting text from PDF documents on-device.
