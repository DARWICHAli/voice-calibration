# 🎙️ Speaker Identity & Voice Enhancement Interface

## 📌 Objectif

Ce projet propose une interface interactive permettant de :

1. Charger une **vidéo ou un fichier audio** en entrée
2. **Identifier et segmenter les voix** dans l’enregistrement (diarisation)
3. Estimer pour chaque voix le **genre**, l’**âge approximatif**, ou une **ID anonyme**
4. Permettre de **moduler le volume** de chaque locuteur (amplifier/diminuer)

---

## ⚙️ Fonctionnalités principales

- 🔊 **Extraction audio** depuis une vidéo
- 🧠 **Diarisation des locuteurs** (séparation par voix)
- 🧬 **Identification des caractéristiques** des locuteurs :
  - Genre (homme/femme)
  - Âge estimé (enfant/adulte/personne âgée)
- 🎚️ **Amplification ciblée** par locuteur
- 🖥️ Interface utilisateur simple pour tout contrôler

---

## 🧰 Technologies utilisées

- **Langage** : Python 3.10+
- **Traitement audio** : `ffmpeg`, `pydub`, `librosa`, `soundfile`
- **Diarisation** : [`pyannote-audio`](https://github.com/pyannote/pyannote-audio)
- **Embeddings vocaux** : `ECAPA-TDNN`, `x-vectors`
- **Modèles de classification** : réseaux de neurones pré-entraînés
- **Interface utilisateur** : `Streamlit` ou `Gradio`

---
