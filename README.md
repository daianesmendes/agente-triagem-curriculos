🤖 Agente de Triagem de Currículos (n8n)

Fluxo automatizado desenvolvido no **n8n** que realiza a triagem de currículos recebidos por e-mail, analisa compatibilidade com vagas e envia respostas automáticas ao RH.

🧩 Funcionalidades

- **Gmail Trigger:** dispara quando um currículo é recebido por e-mail.  
- **Leitura do Currículo (Extract from PDF):** extrai o texto do anexo PDF.  
- **Organizar Dados:** formata as informações do candidato.  
- **Get Row(s) in Sheet:** busca as vagas disponíveis em uma planilha do Google Sheets.  
- **AI Agent (OpenAI):** analisa o perfil do candidato e identifica a vaga mais compatível.  
- **IF Node:** decide se há compatibilidade suficiente.  
- **Envio de E-mail:** envia mensagem personalizada ao RH com o resultado.

🧠 Tecnologias Utilizadas

- **n8n.io**
- **Google Gmail API**
- **Google Sheets API**
- **OpenAI GPT model**

🚀 Como Importar o Workflow

1. Baixe o arquivo [`resume_analyzer.json`](workflows/resume_analyzer.json)  
2. No n8n, clique em "Import Workflow"  
3. Cole o conteúdo do arquivo ou faça upload  
4. Atualize as credenciais das integrações (Gmail, Sheets, OpenAI)

   [Fluxo no n8n](docs/Triagem%20de%20currículos%20-%20n8n.png)

