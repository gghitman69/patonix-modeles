# Modèles de langues pour PatonixOS — mentions légales et attributions

Archives téléchargées à la demande par PatonixOS (Réglages › Langues). Chaque archive est vérifiée par SHA-256 d'après un catalogue signé (Ed25519) embarqué dans PatonixOS ; ce dépôt n'est qu'un hébergement.

## Traduction (`mt-*`) — licence CC BY 4.0
- Modèles **Opus-MT** du groupe **Helsinki-NLP** (Jörg Tiedemann, Santhosh Thottingal, université d'Helsinki) : https://huggingface.co/Helsinki-NLP — publication : « OPUS-MT — Building open translation services for the World », EAMT 2020.
- Licence : Creative Commons Attribution 4.0 International — https://creativecommons.org/licenses/by/4.0/
- **Modifications** : les modèles d'origine (`Helsinki-NLP/opus-mt-<src>-<tgt>`) ont été convertis au format CTranslate2 (quantification int8, `ct2-transformers-converter`) et accompagnés du vocabulaire SentencePiece. Le portugais utilise `opus-mt-en-ROMANCE` / `opus-mt-ROMANCE-en` avec le jeton de langue `>>pt<<`. Aucun réentraînement.
- Ces modèles sont fournis « en l'état », sans garantie ; Helsinki-NLP ne cautionne pas PatonixOS.

## Voix (`tts-*`) — projet Piper (rhasspy/piper-voices, https://huggingface.co/rhasspy/piper-voices)
| Archive | Voix | Licence du jeu de données (fiche de la voix) |
|---|---|---|
| tts-en-ljspeech | en_US ljspeech (medium) | domaine public — LJ Speech (Keith Ito) |
| tts-en-john | en_US john (medium) | domaine public — LibriVox |
| tts-es-carlfm | es_ES carlfm (x_low) | domaine public — carlfm01/my-speech-datasets |
| tts-de-kerstin | de_DE kerstin (low) | CC0 — rhasspy/dataset-voice-kerstin |
| tts-de-thorsten | de_DE thorsten (low) | CC0 — Thorsten-Voice (Thorsten Müller) |
| tts-pt-edresson | pt_BR edresson (low) | **CC BY 4.0** — Edresson Casanova, TTS-Portuguese-Corpus (https://github.com/Edresson/TTS-Portuguese-Corpus) |

Les fichiers `.onnx` et `.onnx.json` sont ceux de rhasspy/piper-voices, **non modifiés** (seulement regroupés en archive `.tar`).
