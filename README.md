# Marcelo Rodrigues Macedo Filho

*Analista de TI | Qualidade de Software | Sistemas Industriais*

Analista de TI na CAOA Montadora (Anápolis/GO), em uma planta de montagem de veículos Chery e Changan. Atuo na sustentação, evolução e validação dos sistemas que apoiam a produção, como impressão e sequenciamento de etiquetas, controle de produção, qualidade, logística/armazém e integração com o ERP. Minha base é a investigação de causa raiz: cruzar o comportamento da aplicação com os dados no banco até encontrar o ponto exato da falha.

Estou consolidando minha carreira em Qualidade de Software, com foco em testes funcionais, validação de dados, automação e testes de API. Os projetos abaixo mostram essa prática.

---

## Atuação profissional

*Qualidade e validação*
- Validação funcional e homologação de mudanças em sistemas de chão de fábrica antes da liberação para produção
- Análise de regras de negócio e documentação de defeitos com causa raiz, impacto e correção proposta
- Investigação de inconsistências entre aplicação e banco de dados via SQL (Oracle e SQL Server)
- Revisão de código com foco em segurança: parametrização de queries contra SQL Injection e tratamento de saída contra XSS

*Desenvolvimento e sustentação*
- Manutenção e evolução de aplicações web em ColdFusion (CFML) com Bootstrap
- Geração de etiquetas em PDF com código de barras e QR Code, roteamento para impressoras industriais e fluxos de reimpressão por leitura de código
- Integração entre MES (SQL Server) e ERP Protheus/TOTVS (Oracle via database links), incluindo painéis de monitoramento de interfaces e erros de integração
- Exportações de grandes volumes via CSV em streaming (tabelas com mais de 350 mil registros)

*Banco de dados*
- Consultas Oracle avançadas: CTEs, funções analíticas (`ROW_NUMBER() OVER`), `REGEXP_SUBSTR`, unpivot com `UNION ALL`
- Diagnóstico de falhas de JOIN, problemas de padding em `CHAR` e divergências de dados entre sistemas
- Proposta de triggers para correção estrutural de dados e scripts de rollback

## Destaques

- *Exportações que travavam:* identifiquei erros estruturais que impediam exportações de concluir e reescrevi o processo em CSV com streaming, suportando tabelas de centenas de milhares de linhas.
- *Dados em branco em relatórios:* diagnostiquei um JOIN incompleto que gerava campos vazios em exportações e corrigi com deduplicação via `ROW_NUMBER()`.
- *Compatibilidade com Java 17:* substituí APIs internas descontinuadas na geração de códigos de barras, mantendo a impressão de etiquetas em funcionamento.
- *Automação de infraestrutura com IA:* por iniciativa própria, implementei um agente de IA no servidor para automatizar tratativas recorrentes, como religamento de portas e reinício de serviços que geram lentidão.
- *Modernização:* participo da análise e da proposta de migração dos sistemas ColdFusion para uma arquitetura em nuvem (AWS).

## Projetos de portfólio (QA)

Projetos inspirados em sistemas reais de chão de fábrica, reescritos do zero com dados fictícios para demonstrar a parte de testes.

| Projeto | O que mostra | Stack de testes |
|---|---|---|
| [controle-quimicos-qa](https://github.com/VitraSan/controle-quimicos-qa) | Requisição de químicos com FEFO, validade e fechamento automático. Plano de testes, casos de teste e 2 bugs documentados | Jest, Supertest, Playwright, GitHub Actions |
| [monitor-integracao-qa](https://github.com/VitraSan/monitor-integracao-qa) | API de integração MES → ERP com contrato OpenAPI, testes de contrato e coleção Postman | Jest + Ajv, Postman/Newman, GitHub Actions |
| [etiquetas-vin-bdd](https://github.com/VitraSan/etiquetas-vin-bdd) | 55 cenários BDD em Gherkin (português) rodando nas camadas de domínio e API, com matriz de rastreabilidade | Cucumber, Supertest, GitHub Actions |

## Tecnologias

| Área | Ferramentas |
|---|---|
| Banco de dados | Oracle (SQL e PL/SQL), SQL Server |
| Desenvolvimento | ColdFusion (CFML), JavaScript, HTML, CSS, Bootstrap, Java (integração) |
| ERP e indústria | Protheus/TOTVS, MES |
| Dados | Power BI (conexão com Oracle) |
| Testes | Jest, Supertest, Playwright, Cucumber (BDD/Gherkin), Postman/Newman, OpenAPI |
| Processo | Git (branches e code review), Jira, Scrum |
| CI/CD | GitHub Actions |

*Estudando:* testes de performance e aprofundamento em automação

## Formação

- *Bacharelado em Ciência da Computação*, Anhanguera (conclusão prevista para jan/2027)
- *Técnico em Edificações*, IF Goiano

*Certificações:* Trilha Carreira QA · Começando em DevOps · Primeiros passos com Engenharia de Dados · COBIT 2019 · A partir do zero (programação)

*Idiomas:* Português (nativo) · Inglês (intermediário) · Espanhol (intermediário) · Italiano (básico)

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Marcelo%20Rodrigues-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcelo-rodrigues-macedo-filho-b657432b1)
