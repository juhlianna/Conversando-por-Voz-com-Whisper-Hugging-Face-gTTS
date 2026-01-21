# Conversa por Voz em Português (Whisper + Hugging Face + gTTS)

Este projeto demonstra como criar um fluxo de **voz ↔ texto ↔ resposta** totalmente em português, sem depender da quota da OpenAI.

## 🚀 Tecnologias utilizadas
- [Whisper](https://github.com/openai/whisper) (open source) para transcrição de áudio.
- [Transformers](https://huggingface.co/docs/transformers/index) da Hugging Face com modelo `unicamp-dl/ptt5-base-portuguese-vocab` para gerar respostas em português.
- [gTTS](https://pypi.org/project/gTTS/) para converter texto em áudio.

---

## 📦 Instalação
No Google Colab ou ambiente Python:

```bash
pip install git+https://github.com/openai/whisper.git
pip install transformers gTTS
