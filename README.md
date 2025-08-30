# Bot WhatsApp com IA

Um bot inteligente para WhatsApp desenvolvido com Python, utilizando tecnologias modernas de IA com RAG de arquivos.

## 🚀 Tecnologias Utilizadas

- **Python** - Linguagem principal do projeto
- **LangChain** - Framework para desenvolvimento de aplicações com LLM
- **OpenAI API** - Integração com modelos de linguagem da OpenAI
- **Redis** - Cache e gerenciamento de sessões
- **Evolution API** - API para integração com WhatsApp
- **ChromaDB** - Banco de dados vetorial para busca semântica
- **Docker** - Containerização da aplicação

## 📋 Pré-requisitos

- Docker
- Docker Compose
- Chaves de API:
  - OpenAI API Key

## ⚙️ Configuração

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd <nome-do-repositorio>
```

2. Configure as variáveis de ambiente:
```bash
cp .env.example .env
```

3. Edite o arquivo `.env` com suas credenciais:


## 🐳 Execução com Docker

Para iniciar a aplicação, execute:

```bash
docker compose up --build
```

Este comando irá:
- Construir todas as imagens necessárias
- Iniciar os serviços


## 🛑 Parar a Aplicação

```bash
docker compose down
```

Para remover volumes e limpar completamente:
```bash
docker compose down -v
```

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).
