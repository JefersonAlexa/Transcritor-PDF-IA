# 📄 Transcritor Inteligente — INOVHIA Tecnologia

Uma aplicação desktop robusta e de alta performance desenvolvida para automatizar a extração, análise e formatação de dados a partir de documentos PDF complexos (como relatórios de auditoria, apresentações de slides e demonstrações financeiras). 

O sistema opera com um motor híbrido: utiliza a inteligência visual do **Google Gemini** para análises profundas e um poderoso **Extrator Nativo Offline (Regex + PyMuPDF)** para estruturação de parágrafos quebrados e tabelas. O resultado é exportado de forma nativa e perfeitamente formatada para o **Microsoft Word (.docx)**.

---<img width="1084" height="484" alt="Transcritor1" src="https://github.com/user-attachments/assets/982d0343-d39d-456e-9282-c87cf494a02d" />


## ✨ Principais Funcionalidades

- **🤖 Análise com Inteligência Artificial (Gemini):** Envia "fotografias" de cada página do PDF para o modelo Gemini, extraindo resumos, identificando divergências e pontuando riscos com base em um prompt customizável.
- **🔌 Modo de Simulação Offline:** Processa documentos inteiros sem conexão com a internet ou consumo de cotas de API, extraindo texto bruto e detectando tabelas nativamente.
- **📊 Caçador de Tabelas:** Identifica matrizes de dados dentro do PDF e as reconstrói nativamente no Word (utilizando o estilo `Table Grid`), abandonando formatações rudimentares de texto.
- **🧹 Limpeza de Texto Avançada (Regex):** Resolve o problema clássico de cópia de PDFs (frases quebradas no meio do parágrafo), unindo sentenças e limpando caracteres de controle ocultos (Anti-Corrupção XML).
- **📝 Exportação Perfeita para MS Word:** Gera arquivos `.docx` blindados. Formata automaticamente cabeçalhos, aplica fonte *Arial*, insere espaçamento entre parágrafos (8pt) e configura margens corporativas.
- **🛡️ UX Suprema e Controles de Segurança:** Impede a leitura acidental de arquivos incorretos (lixo), burla o *Modo de Exibição Protegido* do Windows e oferece abertura inteligente de diretório após a exportação.

---
## ⚙️ Pré-requisitos e Instalação

### 1. Clonar o repositório
git clone [https://github.com/SEU_USUARIO/transcritor-inovhia.git](https://github.com/SEU_USUARIO/transcritor-inovhia.git)
cd transcritor-inovhia
