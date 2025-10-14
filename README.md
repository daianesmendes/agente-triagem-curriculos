# 🤖 Agente de Triagem de Currículos (n8n)

Fluxo automatizado desenvolvido no **n8n** para triagem de currículos recebidos por e-mail.  
A automação analisa o conteúdo dos PDFs, compara com as vagas em planilha e envia respostas automáticas ao RH com auxílio de **IA (OpenAI)**.

---

## 🧩 Funcionalidades
- **📨 Gmail Trigger:** detecta novos currículos recebidos.  
- **📄 Extract from PDF:** extrai e processa o texto do currículo.  
- **🧹 Formatação de Dados:** organiza e padroniza as informações.  
- **📊 Consulta de Vagas (Google Sheets):** busca vagas ativas.  
- **🧠 IA (OpenAI):** identifica a vaga mais compatível.  
- **⚖️ IF Node:** verifica o nível de compatibilidade.  
- **📧 Envio de E-mail:** comunica o resultado ao RH.

---

## ⚙️ Tecnologias
- [**n8n.io**](https://n8n.io)  
- **Google Gmail API**  
- **Google Sheets API**  
- **OpenAI GPT Model**

---

## 🚀 Como Usar
1. Baixe o arquivo [`agente_triagem_curriculos.json`](workflows/agente_triagem_curriculos.json)  
2. Importe o fluxo no **n8n**  
3. Configure as credenciais: Gmail, Sheets e OpenAI  
4. Execute o fluxo e monitore as respostas automáticas.

---

Desenvolvido por **Daiane Mendes**  
💼 Estagiária de Automação e IA  
🔗 [LinkedIn](https://linkedin.com/in/daiane-mendes-848252289) | [GitHub](https://github.com/daianesmendes)

![Fluxo n8n](docs/Triagem_de_Curriculos_n8n.png)

