📧 SAC Automatizado com IA via Gmail

Este projeto implementa um sistema de atendimento ao cliente (SAC) totalmente automatizado no n8n, que responde e-mails recebidos no Gmail utilizando Inteligência Artificial.

------------------------------------------------------------------------------------------------------------------

🚀 Funcionalidades

📩 Monitoramento de e-mails via Gmail Trigger

🤖 Agente de IA (GPT-4o-mini) treinado com respostas padronizadas da Hashtag Treinamentos

🧠 Memória de curto prazo (até 10 interações) para manter contexto das conversas

📤 Respostas automáticas enviadas diretamente no mesmo thread de e-mail

🔍 Filtro de remetente para evitar autoenvio indevido

------------------------------------------------------------------------------------------------------------------

🛠️ Tecnologias Utilizadas

Tecnologia	Finalidade

n8n	Orquestração do fluxo

Gmail API	Captura e envio de e-mails

OpenAI GPT-4o-mini	Geração de respostas inteligentes

LangChain Memory	Armazenamento de contexto da conversa

------------------------------------------------------------------------------------------------------------------

📂 Estrutura do Fluxo

Gmail Trigger → Verifica novos e-mails recebidos.

If → Garante que não responda e-mails do próprio remetente.

OpenAI Chat Model → Gera resposta com base nas perguntas.

AI Agent → Aplica regras e informações pré-definidas (SAC da Hashtag).

Simple Memory → Mantém o histórico da conversa (últimas 10 mensagens).

Reply to Message → Envia a resposta automática ao cliente.

------------------------------------------------------------------------------------------------------------------

🎯 Casos de Uso

Atendimento automático de clientes por e-mail.

Respostas rápidas e padronizadas sobre cursos, eventos e serviços da Hashtag.

Redução da carga manual da equipe de suporte.

Garante agilidade e consistência no relacionamento com leads e alunos.
