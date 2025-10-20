<center>
  <h1 style="font-size:2.4em; margin-bottom:0.1em;">📧 SAC Automatizado com IA via Gmail</h1>
  <p style="margin-top:0.2em; font-size:1.05em; color:#555;">
    Sistema inteligente de atendimento ao cliente que automatiza respostas de e-mails no Gmail utilizando n8n e Inteligência Artificial.
  </p>
  <p>
    <a href="https://github.com/Rafael072187/SAC_Automatizad_com_IA_via_Gmail" style="background:#24292F;color:#fff;padding:8px 14px;border-radius:8px;text-decoration:none;font-weight:600;">
      🔗 Repositório no GitHub
    </a>
  </p>
</center>

<hr>

## 🧭 **Tabela de Conteúdos**
- Descrição  
- Instalação  
- Uso  
- Tecnologias  
- Como contribuir  
- Autor  
- Observações  

---

## 📘 **Descrição**
<details>
  <summary><b>Resumo</b></summary>
  O **SAC Automatizado com IA via Gmail** é um projeto desenvolvido no **n8n**, voltado para automatizar o atendimento ao cliente por e-mail.  
  Ele utiliza a **API do Gmail** para monitorar mensagens recebidas e o **modelo GPT-4o-mini** para gerar respostas automáticas e personalizadas.  
  O sistema inclui memória de curto prazo, permitindo manter o contexto de até 10 interações por cliente, e aplica filtros para evitar autoenvios indesejados.  
  Ideal para empresas que desejam agilizar o suporte ao cliente, reduzir carga de trabalho e padronizar comunicações.
</details>

---

## ⚙️ **Instalação**
<details>
  <summary><b>Passo a passo (Linux / macOS / Windows)</b></summary>

1. Clone o repositório:
   ```bash
   git clone https://github.com/Rafael072187/SAC_Automatizad_com_IA_via_Gmail.git
   cd SAC_Automatizad_com_IA_via_Gmail
Instale o n8n:

bash
Copiar código
npm install -g n8n
Inicie o servidor n8n:

bash
Copiar código
n8n start
Importe o fluxo:

Acesse o painel do n8n

Clique em Import Workflow

Selecione o arquivo SACemail.json

Configure as credenciais:

Gmail API → para ler e responder e-mails

OpenAI API Key → para gerar respostas inteligentes

LangChain Memory → para manter o histórico das conversas

</details>
🖥️ Uso
<details> <summary><b>Como usar o projeto</b></summary>
O fluxo do n8n inicia automaticamente com o Gmail Trigger, que verifica novos e-mails recebidos.

O sistema:

Identifica o remetente e verifica se não é um autoenvio;

Analisa o conteúdo da mensagem;

Gera uma resposta utilizando o modelo GPT-4o-mini;

Mantém o contexto da conversa com memória temporária;

Responde diretamente no mesmo thread do e-mail original.

Casos de uso ideais:

SAC corporativo e atendimento automático;

Suporte a dúvidas sobre produtos e serviços;

Interações rápidas e padronizadas com clientes.

</details> <p align="center" style="margin-top:14px;"> <img src="https://cdn-icons-png.flaticon.com/512/542/542638.png" width="90" alt="ícone ilustrativo"> <br> <i>Fluxo de automação do SAC via Gmail no n8n.</i> </p>
🛠️ Tecnologias
<details> <summary><b>Stack principal</b></summary>
n8n → Automação e orquestração do fluxo

Gmail API → Monitoramento e envio de e-mails

OpenAI GPT-4o-mini → Geração de respostas automáticas

LangChain Memory → Retenção de contexto das conversas

JavaScript / JSON → Estruturação dos nós e lógica do fluxo

</details>
🤝 Como contribuir
<details> <summary><b>Guia rápido</b></summary>
Faça um fork do repositório

Crie uma nova branch:

bash
Copiar código
git checkout -b feature/nova-feature
Adicione suas alterações:

bash
Copiar código
git commit -m "feat: adiciona nova automação de resposta"
git push origin feature/nova-feature
Abra um Pull Request descrevendo a melhoria proposta.

</details>
👤 Autor
<details> <summary><b>Contatos</b></summary> <p> <b>Rafael Bittencourt de Araújo</b> — desenvolvedor do projeto.<br> GitHub: <a href="https://github.com/Rafael072187" target="_blank">github.com/Rafael072187</a><br> </p> </details>
📝 Observações
✅ Automação ideal para SACs empresariais baseados em e-mail.
🔧 Pode ser integrada com bancos de dados externos ou Google Sheets para relatórios.
⚠️ Recomenda-se proteger as chaves de API e configurar permissões seguras no Gmail.

<p align="center" style="margin-top:18px;"> <a href="https://github.com/Rafael072187/SAC_Automatizad_com_IA_via_Gmail" style="background:#0b5fff;color:#fff;padding:10px 18px;border-radius:8px;text-decoration:none;font-weight:600;"> Ver repositório </a> </p> <p align="center" style="margin-top:14px;color:#666;"> Estrutura gerada automaticamente com base no repositório analisado. </p> ```
