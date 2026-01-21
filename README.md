# Conversando por Voz com Whisper + Hugging Face + gTTS

Este projeto demonstra como criar um fluxo de **voz ↔ texto ↔ resposta** sem depender da quota da OpenAI, utilizando:

- [Whisper](https://github.com/openai/whisper) (open source) para transcrição de áudio.
- [Transformers](https://huggingface.co/docs/transformers/index) da Hugging Face para gerar respostas em texto.
- [gTTS](https://pypi.org/project/gTTS/) para converter texto em áudio.

---

## 🚀 Instalação

No Google Colab ou ambiente Python:

```bash
pip install git+https://github.com/openai/whisper.git
pip install transformers gTTS
