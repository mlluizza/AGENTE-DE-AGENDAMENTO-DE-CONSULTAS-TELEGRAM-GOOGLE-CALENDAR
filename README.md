# Agente de Agendamento de Consultas via Telegram

Este projeto é um fluxo automatizado criado no n8n que atua como um(a) secretário(a) virtual inteligente. Ele recebe pedidos de consulta pelo Telegram, interpreta a linguagem natural do utilizador utilizando Inteligência Artificial e realiza o agendamento no Google Calendar, enviando uma confirmação amigável.

---
## 🚀 Funcionalidades

*   **Atendimento via Chat:** Receção de mensagens diretamente pelo Telegram.
*   **Extração Inteligente:** A IA identifica o nome real, o e-mail e a data/hora pretendida diretamente do texto da mensagem.
*   **Compreensão de Datas:** O sistema entende referências temporais informais e converte-as para o formato correto do calendário.
*   **Integração Automática:** Criação do evento no Google Calendar e geração automática do link da consulta.
*   **Respostas Humanizadas:** Envio de confirmação com um tom natural e empático.

## 🛠️ Tecnologias Utilizadas

*   **n8n** - Plataforma de automação.
*   **Telegram** - Interface de comunicação com o cliente.
*   **Google Calendar** - Gestão da agenda e criação de eventos.
*   **Inteligência Artificial** - Processamento da linguagem natural e orquestração do agendamento.

## ⚙️ Como Funciona

1.  **Receção:** O utilizador envia uma mensagem indicando a intenção de agendamento e os seus dados.
2.  **Interpretação:** A Inteligência Artificial lê o texto e compreende o contexto do pedido.
3.  **Agendamento:** O sistema extrai as informações necessárias e regista o evento no calendário.
4.  **Confirmação:** O utilizador recebe de volta uma mensagem humanizada com todos os detalhes e o link de acesso.

## 📝 Comportamento da IA

O agente é instruído a:
*   Ser humano e natural, evitando formatos rígidos.
*   Priorizar as informações escritas pelo cliente no texto da mensagem.
*   Gerar respostas leves contendo o nome, data, hora, e-mail e o link do evento.

## 📥 Como Instalar

1.  Importe o ficheiro do fluxo para o n8n.
2.  Configure as suas credenciais do Telegram e do Google Calendar.
3.  Conecte a sua conta de provedor de Inteligência Artificial.
4.  Ative o fluxo e inicie o uso no Telegram.

---

## 📸 Demonstração do Projeto
* **Interação no Telegram:**
<div align="center">
  <img width="405" height="614" alt="Interação no Telegram" src="https://github.com/user-attachments/assets/d593d5a4-e0d9-43f3-aa5b-77e37501c495" />
</div>

* **Evento no Google Calendar:**
<div align="center">
  <img width="933" height="908" alt="Evento no Google Calendar" src="https://github.com/user-attachments/assets/f2d8557b-f4ba-4238-9dbd-d11614d10e02" />
</div>

* **Fluxo construído no n8n:**
<div align="center">
  <img width="1185" height="555" alt="Fluxo construído no n8n" src="https://github.com/user-attachments/assets/c7e72b2a-3f9c-482a-8455-4916f80eb9d3" />
</div>
