![Capa do Projeto](capa.png)

# 📄 PDF Insight Bot (com Gemini API)

Este projeto é um agente inteligente de PDF que lê, entende e responde perguntas sobre documentos, usando o modelo Gemini 1.5 Flash da Google AI. Ideal para estudar IA aplicada, criar portfólio ou até mesmo automatizar atendimento com base em documentos técnicos e comerciais.

## 📚 Sumário  
- 💡 Funcionalidades  
- 💬 Exemplo de uso  
- 📂 Estrutura do Projeto  
- 🛠️ Tecnologias Usadas  
- 🚀 Como executar localmente  
- 📈 Próximas melhorias  
- ✍️ Autor  
- 📝 Licença  

## 💡 Funcionalidades  
✅ Integração com a API Gemini (Google AI)  
✅ Leitura de múltiplos PDFs automaticamente  
✅ Geração de embeddings com LangChain e FAISS  
✅ Respostas contextuais com base no conteúdo real dos PDFs  
✅ Destaque inteligente de palavras-chave no terminal  
✅ Projeto leve, didático e pronto para portfólio  

✨ Funcionalidade extra:  
✅ Destaque visual no terminal com palavras-chave como Tema, Tecnologia, Setor para facilitar a leitura da resposta da IA.

## 💬 Exemplo de uso  
**Pergunta:** Qual é o tema principal do documento?  
**Resposta:** O 📚 TEMA principal do documento é o impacto da 🧠 TECNOLOGIA blockchain no mercado e a regulamentação das moedas virtuais.

## 📂 Estrutura do Projeto  
pdf-insight-bot/  
├── utils/  
│   └── leitor_pdf.py  
├── data/  
│   └── documents/  
│       ├── inteligencia_artificial.pdf  
│       ├── blockchain_no_mercado.pdf  
│       └── impacto_da_automacao.pdf  
├── teste_leitor_pdf.py  
├── .env.example  
├── README.md  
└── capa.png  

## 🛠️ Tecnologias Usadas  
Python 3, LangChain, Gemini API (Google AI), FAISS, python-dotenv  

## 🚀 Como executar localmente  
Clone o repositório:  
git clone https://github.com/MrsM21/pdf-insight-bot.git  
cd pdf-insight-bot  

Instale as dependências:  
pip install -r requirements.txt  

Crie o arquivo .env:  
GEMINI_API_KEY=sua-chave-aqui  

Adicione seus arquivos .pdf na pasta:  
data/documents/  

Execute o script de teste:  
python teste_leitor_pdf.py  

## 📈 Próximas melhorias  
[ ] Salvar a base vetorial (FAISS) em .pkl  
[ ] Interface web com Gradio ou Streamlit  
[ ] Versão online com deploy gratuito (Replit, Render)  
[ ] Integração com mini-CRM para armazenar perguntas e contatos  

## ✍️ Autor  
Projeto criado por [NeusaM21](https://github.com/NeusaM21) como parte do seu portfólio em IA aplicada. Feito com carinho, estudo e ✨ café.

## 📝 Licença  
Este projeto está sob a MIT License. Use, adapte e compartilhe — só não esquece os créditos. 😉



