📅 Agente de Agendamento de Consultas – Telegram + Google Calendar

Este projeto implementa um agente inteligente no n8n que permite ao usuário agendar, consultar e cancelar compromissos diretamente pelo Telegram, com sincronização automática no Google Calendar.

🚀 Funcionalidades

📲 Integração com Telegram: o usuário interage com o agente em tempo real.

🤖 IA com OpenAI: processamento de linguagem natural para entender comandos (ex.: "Marque uma consulta amanhã às 15h").

🧠 Memória de Conversa: histórico curto mantido para melhor contextualização.

📅 Integração com Google Calendar:

Agendar novos eventos.

Consultar compromissos existentes.

Cancelar eventos.

💬 Resposta automática no Telegram confirmando as operações.

🛠️ Tecnologias

Tecnologia	Finalidade

n8n	Orquestração do fluxo

Telegram Bot API	Canal de comunicação com o usuário

OpenAI (gpt-4o-mini)	Interpretação dos comandos em linguagem natural

Google Calendar API	Gestão de eventos (criar, listar, deletar)

📂 Estrutura do Fluxo

Telegram Trigger → Recebe a mensagem do usuário.

AI Agent (LangChain) → Interpreta a intenção.

Google Calendar Tools → Executa a ação correspondente:

Criar evento

Listar eventos

Deletar evento

Send Message (Telegram) → Retorna a confirmação ao usuário.

🎯 Casos de Uso

Marcar consultas ou reuniões sem sair do Telegram.

Consultar agenda rapidamente com linguagem natural.

Cancelar compromissos de forma simples e intuitiva.
