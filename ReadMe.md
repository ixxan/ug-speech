# Uyghur Speech Models

Check out this [demo](https://huggingface.co/spaces/ixxan/uyghur-speech-models) to try the models from this repository.

---

Notebooks in this repo containing model fine-tuning code:
* **Fine_Tune_MMS_ASR_Uyghur**: [Meta-MMS-ASR](https://huggingface.co/facebook/mms-1b-all) fine-tuned for Uyghur with [THUYG20](https://openslr.org/22), [Common Voice](https://commonvoice.mozilla.org), and [UQSpeechDataset](https://github.com/gheyret/UQSpeechDataset). The resulting model can be accessed [here](https://huggingface.co/ixxan/wav2vec2-large-mms-1b-uyghur-latin).
* **Fine_Tune_MMS_TTS_Uyghur**: [Meta-MMS-TTS](https://huggingface.co/facebook/mms-tts-uig-script_arabic) fine-tuned for Uyghur with [UQSpeechDataset](https://github.com/gheyret/UQSpeechDataset).
The resulting model can be accessed [here](https://huggingface.co/ixxan/mms-tts-uig-script_arabic-UQSpeech).
* **Fine_Tune_Whisper_Uyghur_CV**: [OpenAI-Whisper](https://huggingface.co/openai/whisper-small) fine-tuned for Uyghur with [Common Voice](https://commonvoice.mozilla.org). The resulting model can be accessed [here](https://huggingface.co/ixxan/whisper-small-uyghur-common-voice).
* **Fine_Tune_Whisper_Uyghur_THUYG20**: [OpenAI-Whisper](https://huggingface.co/openai/whisper-small) fine-tuned for Uyghur with [THUYG20](https://openslr.org/22). The resulting model can be accessed [here](https://huggingface.co/ixxan/whisper-small-uyghur-common-voice).

Notebooks contain examples of inferencing the ASR and TTS models: 
* **Uyghur_ASR_Inference**
* **Uyghur_TTS_Inference**
