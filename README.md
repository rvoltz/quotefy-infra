# quotefy-infra

Infraestrutura do projeto Quotefy.

## Estrutura de Pastas

```
quotefy-infra/
├── README.md
├── quotefy-infra/
│   ├── hml/
│   │   ├── back/
│   │   │   ├── app.env
│   │   │   ├── db.env
│   │   │   ├── docker-compose.yml
│   │   │   └── whatsapp.env
│   │   └── front/
│   │       ├── docker-compose.yml
│   │       └── front.env
│   └── prd/
│       └── (vazio)
```

- `hml/`: Ambiente de homologação (teste)
	- `back/`: Infraestrutura do backend (ambiente de teste)
	- `front/`: Infraestrutura do frontend (ambiente de teste)
- `prd/`: Ambiente de produção (ainda vazio)
