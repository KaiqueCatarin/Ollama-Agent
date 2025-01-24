# 🗓️ Assistente de Agenda com IA Generativa e Controle por Voz

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Licença](https://img.shields.io/badge/Licença-MIT-green)](LICENSE)
[![API](https://img.shields.io/badge/API-Google_Calendar-orange)](https://developers.google.com/calendar)

Um assistente virtual inteligente que agenda compromissos via comando de voz utilizando processamento de linguagem natural com Mistral LLM e integração com Google Calendar.

![Demo](assets/demo.gif) <!-- Adicione um gif de demonstração posteriormente -->

## ✨ Funcionalidades Principais

- **🎤 Controle por voz** natural em tempo real
- **🧠 Processamento de NLP** com Mistral via Ollama
- **📅 Integração automática** com Google Calendar
- **⏰ Lembretes inteligentes** com múltiplos alertas
- **🗣️ Feedback por voz** em tempo real
- **🌐 Suporte a timezones** configurável

## 🛠️ Tecnologias Utilizadas

| Componente           | Tecnologias                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **IA Generativa**    | Mistral LLM, Ollama                                                         |
| **Reconhecimento de Voz** | SpeechRecognition, Google Speech-to-Text                               |
| **Síntese de Voz**   | pyttsx3                                                                     |
| **Integração Cloud** | Google Calendar API, OAuth2                                                 |
| **Core**             | Python 3.8+, dateutil, requests                                             |

## 📋 Pré-requisitos

- Python 3.8 ou superior
- Servidor Ollama local com modelo Mistral
- Credenciais da API do Google Calendar
- Microfone funcional

## 🚀 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/assistente-agenda-ia.git
cd assistente-agenda-ia
