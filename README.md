# 🤖 Agendamento Inteligente com n8n + Gemini + Google Calendar

Sistema de agendamento inteligente desenvolvido com n8n, Google Gemini e Google Calendar.

O fluxo interpreta solicitações em linguagem natural, extrai informações estruturadas, verifica disponibilidade na agenda e cria eventos automaticamente.

---

# 🚀 Funcionalidades

- Interpretação de mensagens usando IA (Google Gemini)
- Extração estruturada de dados
- Normalização de datas e horários
- Consulta automática ao Google Calendar
- Verificação de disponibilidade
- Criação automática de eventos
- Tratamento de horários indisponíveis

---

# 🏗️ Arquitetura do Fluxo

text
Usuário
   │
   ▼
Agente Inteligente (Gemini)
   │
   ▼
Tratamento de Dados
   │
   ▼
Normalização
   │
   ▼
Verificação de Disponibilidade
   │
   ▼
Validação de Horário
   │
   ├── Disponível
   │      ▼
   │  Criar Evento
   │
   └── Indisponível
          ▼
   Retorno ao Usuário


---

# ⚙️ Tecnologias Utilizadas

- n8n
- Google Gemini
- Google Calendar API
- Structured Output Parser

---

# 💡 Exemplo de Uso

Mensagem recebida:

> Quero agendar uma troca de óleo para sexta-feira às 14h.

Processamento:

1. O agente identifica intenção e dados.
2. Extrai data e horário.
3. Consulta disponibilidade no Google Calendar.
4. Valida o horário.
5. Cria o evento automaticamente.

---

# 🎯 Objetivo

Demonstrar a integração entre Inteligência Artificial e automação de processos utilizando n8n e serviços externos.

---

# 📄 Licença

Projeto desenvolvido para fins de estudo e portfólio
