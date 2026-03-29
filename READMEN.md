# API com Python - Projeto de Estudos

Projeto simples para estudos sobre criação de APIs com Python usando FastAPI.

## Como rodar com Docker

```bash
# Build da imagem
docker build -t minha-api .

# Executar o container
docker run -p 8000:8000 minha-api
```

Acesse: `http://localhost:8000`

Documentação automática: `http://localhost:8000/docs`
