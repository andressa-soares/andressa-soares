<div align="center">

# Olá! Eu sou a Andressa. 🤝

**Desenvolvimento back-end · Java · Kotlin · IA aplicada**

Estudante de Análise e Desenvolvimento de Sistemas (FATEC) e pesquisadora de Iniciação Científica.

</div>

---

## Foco

- **Back-end:** APIs REST em Java (Spring Boot) e Kotlin, com modelagem de domínio, regras de negócio explícitas, persistência relacional e testes automatizados.
- **Cloud:** em busca da certificação **AWS Certified Cloud Practitioner (CLF-C02)**. Noções de infraestrutura como código com Terraform e GitHub Actions.
- **Engenharia de prompt:** pesquisa de Iniciação Científica sobre como a estrutura do prompt afeta a funcionalidade, a segurança, a qualidade e a conformidade com a LGPD do código back-end gerado por LLMs. Apresentada no **34º SIICUSP (USP)** e aprovada no **CONIC**.

## O que já apliquei

**API e arquitetura**
- Arquitetura em camadas (controller, service, domain) com dependência em um único sentido
- Contrato OpenAPI escrito antes do código, como fonte única da documentação
- Strategy para regras de negócio extensíveis (regra nova é uma classe nova)
- Parâmetros de negócio externalizados em configuração, não em literais
- DTOs separados do domínio, com mapper explícito
- Padrão `PATCH` para atualização parcial e `POST /actions` para transições de estado
- Documentos de design (SDD) com decisões registradas e motivos

**Persistência e dados**
- Spring Data JPA e Hibernate, PostgreSQL
- Locking otimista (`@Version`) e pessimista (`PESSIMISTIC_WRITE`) em operações críticas
- Migrações versionadas com Flyway
- Modelagem relacional com integridade referencial, constraints de unicidade e ENUMs

**Segurança e confiabilidade**
- Autenticação com JWT e controle de acesso por papéis (RBAC)
- Bean Validation na entrada
- Tratamento global de erros com payload padronizado (`@RestControllerAdvice`)
- Logs estruturados em `campo=valor`, sem dados pessoais (CPF mascarado)
- Pesquisa com checklist da LGPD (arts. 5º, 6º, 11, 12, 37 e 46)

**Testes**
- Unitários e de integração com Mockito e banco H2 em memória
- Smoke tests por `curl` contra a API em execução
- Teste de carga com k6
- Análise estática com bandit, ruff e mypy

**Infraestrutura e entrega**
- Docker, Dockerfile multistage e Docker Compose
- GitHub Actions: `plan` em pull request, `apply` e `destroy` manuais
- Terraform com state remoto em S3 e política IAM de mínimo privilégio
- Deploy em Railway e Vercel

**IA aplicada**
- Plugin para Claude Code (spec-forge), com requisitos em notação EARS
- Experimento reprodutível com 3 modelos, 4 níveis de prompt e 6 tarefas, em duas modalidades (API e agentes)

## Agora

- ☁️ Preparando o **CLF-C02**.
- 🔁 Estudando mensageria e microsserviços.
- 🟣 Aprendendo Kotlin, migrando partes do meu projeto de Pet Shop.

## Projetos em destaque

| Projeto | O que mostra |
|---|---|
| [pet-shop-management](https://github.com/andressa-soares/pet-shop-management) | API REST em Java/Spring Boot com workflow de estados, controle de concorrência, tratamento global de erros, logs estruturados e Docker |
| [kotlin-refactoring](https://github.com/andressa-soares/kotlin-refactoring) | Migração, em escopo reduzido, da feature `Owner` do Pet Shop para Kotlin, com 115 testes automatizados e smoke tests |
| [spec-forge](https://github.com/andressa-soares/spec-forge-plugin) | Plugin para Claude Code que transforma uma ideia em requisitos (EARS) e design técnico |
| [infra-aws-terraform](https://github.com/andressa-soares/infra-aws-terraform) | Projeto de estudo: pipeline GitHub Actions + Terraform que cria e destrói uma EC2 na AWS, com state remoto em S3 e política IAM de mínimo privilégio |
| [university_db](https://github.com/andressa-soares/university_db) | Modelagem relacional em PostgreSQL a partir de regras de negócio, com migrations e consultas analíticas |

## Stack

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg" alt="Kotlin" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" alt="AWS" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/insomnia/insomnia-original.svg" alt="Insomnia" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/datagrip/datagrip-original.svg" alt="DataGrip" height="40" />
</p>

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/andressa-dos-santos-soares/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andressasoares.dev@gmail.com)
