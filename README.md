# LMS corporativo para capacitação

> RH quer trilhas simples; colaboradores querem mobile-first.

[![Autor: Bruno Dyas](https://img.shields.io/badge/autor-Bruno%20Dyas-2563eb?style=for-the-badge)](https://github.com/brunodyas)
[![Stack](https://img.shields.io/badge/stack-react-python-059669?style=for-the-badge)](#stack-tecnológica)
[![Status](https://img.shields.io/badge/progresso-17%2F17-7c3aed?style=for-the-badge)](#sobre-o-projeto)

## Sobre o projeto

Upskilling contínuo; LMS pesados afastam PMEs.

## Funcionalidades e melhorias

- Quiz adaptativo
- Certificados
- Integração SSO
- Mercado: Upskilling contínuo; LMS pesados afastam PMEs.

## Diferencial

Trilhas adaptativas por competência

## Stack tecnológica

- **Perfil:** React · Python · FastAPI
- **Repositório:** [`corp-learning-lms-41df32`](https://github.com/brunodyas/corp-learning-lms-41df32)
- **Baseline OSS:** [redesigned-pancake](https://github.com/Sfedfcv/redesigned-pancake)

### Arquitetura

LMS corporativo para capacitação: Upskilling contínuo; LMS pesados afastam PMEs.. Client/server, tasks sequenciais, commits por entrega.

## Pré-requisitos

- Node.js 20+ e npm
- Python 3.11+
- Git

## Instalação

```bash
git clone https://github.com/brunodyas/corp-learning-lms-41df32.git
cd corp-learning-lms-41df32
cd server && pip install -r requirements.txt && cd ..
cd client && npm install && cd ..
Inicie backend e frontend em terminais separados.
```

## Como executar

1. Conclua a instalação acima.
2. Configure variáveis de ambiente (`.env` ou `.env.example`, se existir).
3. Execute o comando de desenvolvimento ou suba os containers Docker.
4. Valide health/API antes de expor em produção.

## Variáveis de ambiente

- Copie `.env.example` para `.env` quando disponível.
- Nunca commite segredos reais (tokens, senhas, chaves privadas).

## Testes

```bash
# Node.js
npm test

# Python
pytest -q

# .NET
dotnet test

# Java
mvn test
```

> Use o comando compatível com a stack detectada neste repositório.

## Estrutura do repositório

```text
.
├── client/          # Frontend (quando aplicável)
├── server/          # Backend / API (quando aplicável)
├── src/             # Código principal
├── tests/           # Testes automatizados
├── docker-compose.yml
└── README.md
```

## Roadmap

- Refinar observabilidade (logs estruturados, métricas e alertas).
- Endurecer segurança (auth, rate limit, secrets management).
- Expandir cobertura de testes e automação de deploy.

## Licença

Consulte o arquivo `LICENSE` incluído neste repositório.

---

**Desenvolvido por [Bruno Dyas](https://github.com/brunodyas)**

Entrega produzida pela fábrica autónoma **Djenus** — engenharia de software orientada a produto.
