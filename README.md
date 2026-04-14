# 🎙️ Assistente de Voz Inteligente: Whisper + ChatGPT + gTTS

Este repositório contém a implementação de um sistema de conversação por voz desenvolvido como parte de um desafio prático na **DIO (Digital Innovation One)**. O projeto integra tecnologias de ponta em Inteligência Artificial para criar uma interface de comunicação fluida entre humanos e máquinas.

## 🚀 Tecnologias Utilizadas

O projeto utiliza uma stack focada em Processamento de Linguagem Natural (NLP) e Áudio:

* **Python 3.x**: Linguagem base do projeto.
* **OpenAI Whisper**: Modelo de Speech-to-Text (STT) de alta precisão para transcrição e tradução de áudio.
* **OpenAI ChatGPT (GPT-3.5/4)**: O motor de inteligência por trás das respostas textuais.
* **gTTS (Google Text-to-Speech)**: Biblioteca para converter a resposta textual em fala natural.

## 🧠 Arquitetura da Solução

O fluxo de dados da aplicação segue estas etapas:

1.  **Entrada**: Captura de áudio ou leitura de arquivo `.mp3`/`.wav`.
2.  **Transcrição (STT)**: O Whisper processa o áudio e gera o texto correspondente.
3.  **Processamento (LLM)**: O texto é enviado via API para o ChatGPT, que processa a intenção e gera uma resposta.
4.  **Síntese de Voz (TTS)**: O gTTS transforma a resposta do ChatGPT em um arquivo de áudio.
5.  **Saída**: O sistema reproduz a voz para o usuário.

## 🛠️ Como Executar

### Pré-requisitos

Antes de começar, você precisará de uma **API Key da OpenAI**.

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Samu1407/chat-voz.git](https://github.com/Samu1407/chat-voz.git)
   cd chat-voz
