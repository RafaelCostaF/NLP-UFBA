# 📊 PDF NLP Analyzer

Este projeto realiza a análise estatística de documentos em PDF com técnicas de NLP (Processamento de Linguagem Natural), utilizando a biblioteca spaCy.

---

## ✅ Funcionalidades

- Extração de texto de arquivos PDF usando **PyMuPDF** (`fitz`)
- Limpeza de palavras de parada (stopwords)
- Cálculo de métricas linguísticas:
  - Número total de sentenças
  - Número médio de sentenças por documento
  - Número total de tokens (palavras válidas)
  - Número médio de tokens por documento
  - Top-10 tokens mais frequentes
  - Down-10 tokens menos frequentes
  - Contagem de:
    - Substantivos
    - Verbos
    - Preposições

---

## 📦 Requisitos

- Python 3.8+
- pip

### 📚 Bibliotecas necessárias

Você pode instalar todas as dependências com:

- pip install -r requirements.txt

Baixe o modelo de linguagem com: 

- python -m spacy download en_core_web_sm