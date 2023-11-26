# Voice Bhasha 
This project demonstrates multilingual translation using two different approaches: one with mBART (Hugging Face's Transformers library) and the other with Google Translate (gTTS library). Each script translates a given text into multiple Indian languages.

**Functionality**
> The translator has an **automatic language detection system** which identifies the language of the given audio on it's own
> The translator also provides accuracy score of translation by word error rate

**Scripts**
1. mBART Translation
Script: mbart_translation.py
This script uses the mBART model to translate a given text into multiple Indian languages. It calculates the Word Error Rate (WER) for each translation.

2. Google Translate with gTTS
Script: google_translate.py
This script uses Google Translate and the gTTS library to translate a given text into multiple Indian languages. It generates audio files for each translation.
