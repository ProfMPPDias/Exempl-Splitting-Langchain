# Exemplo de Splitting com LangChain 🦾📖

Projeto para dividir documentos em partes menores usando os _TextSplitters_ da **LangChain**! O foco é fragmentar textos relevantes e preservar o contexto para aplicações de IA.

## 💡 O que esse projeto faz?

- Mostra exemplos para dividir textos usando **Character**, **RecursiveCharacter**, **Token** e **MarkdownHeader Splitters**
- Ensina boas práticas para garantir que fragmentos preservem significado/contexto
- Demonstra como tratar diferentes formatos (PDF, Markdown, texto puro)


## 🛠 Instalação dos requisitos no VSCode

### 1. Crie e ative o ambiente virtual (venv)

```bash
python -m venv .venv
```

- **No Windows:**

```
.venv\Scripts\activate
```

- **No Linux/Mac:**

```
source .venv/bin/activate
```

- Dica: O VSCode normalmente detecta o venv criado. No canto inferior esquerdo, troque o kernel Python para `.venv` se necessário.


### 2. Instale as bibliotecas necessárias:

Instale tudo pelo terminal do VSCode, com o ambiente venv ativado:

```bash
pip install langchain
pip install langchain-community
pip install pypdf
pip install tiktoken
pip install ipykernel
pip install jupyter
```


### 3. Configure o Kernel do Jupyter

Após instalar `ipykernel`, rode:

```bash
python -m ipykernel install --user --name=.venv
```

Agora, ao abrir o .ipynb no VSCode, escolha o kernel `.venv` para executar com seu ambiente local ✅

## 🎯 Como rodar o notebook no VSCode

1. Instale a extensão **Jupyter** no VSCode (`ms-toolsai.jupyter`).
2. Abra o notebook `main.ipynb`.
3. Selecione o kernel Python do seu ambiente virtual.
4. Rode as células e explore os exemplos!

## 📚 Exemplos de Splitters abordados

- **CharacterTextSplitter**
- **RecursiveCharacterTextSplitter**
- **TokenTextSplitter (usa tiktoken)**
- **MarkdownHeaderTextSplitter**


## ⚡ Dicas Extras

- Sempre utilize o ambiente venv para evitar conflitos de dependência.
- Use overlap para preservar contexto entre fragmentos.
- Teste diferentes chunk_sizes para diversos tipos de documento.


## 🤖 Sobre

Projeto exemplo para quem trabalha com **RAG**, **chatbots** ou pipelines de IA que usam fragmentação inteligente de texto!

***