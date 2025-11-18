📘 Busca Semântica com HuggingFace + Vector Database (FAISS)

Este repositório contém uma mini aplicação desenvolvida para a atividade AF #11 – Inteligência Artificial, utilizando HuggingFace e FAISS para realizar busca semântica em textos relacionados a golpes bancários digitais.

🚀 Tecnologias utilizadas

Python

HuggingFace (SentenceTransformer)

Modelo: sentence-transformers/all-MiniLM-L6-v2

Vector Database: FAISS

Google Colab / Jupyter Notebook

🧠 Objetivo

Criar uma aplicação simples de busca semântica capaz de identificar textos relacionados a golpes digitais, mesmo quando o usuário utiliza palavras diferentes das presentes nos documentos.

🛠️ Arquivos do repositório

Atividade 11.ipynb — Notebook contendo o código executado.

atividade 11.pdf — Slides da apresentação contendo problema, solução desenvolvida e resultados.

📝 Execução

O notebook realiza:

Carregamento do modelo de embeddings via HuggingFace.

Criação de embeddings para textos sobre golpes bancários.

Armazenamento dos embeddings em um banco vetorial FAISS.

Consulta semântica através de uma pergunta do usuário.

Retorno dos trechos mais relacionados.
