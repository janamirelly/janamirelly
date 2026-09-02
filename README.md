# Janayna Mirelly

**Analista de Testes Júnior** · QA Manual · Testes de API · Automação de interface em Java

Formada em Análise e Desenvolvimento de Sistemas. Trabalho com levantamento de regras de negócio, desenho de casos de teste rastreáveis, investigação de defeitos até a causa raiz e automação de interface.

No meu portfólio **escrevi a aplicação e a suíte que a testa**. As regras de negócio foram levantadas a partir do comportamento do sistema, não recebidas prontas — e os defeitos documentados não foram plantados: apareceram testando o meu próprio código.

---

## Projeto em destaque

### VarejoSync — Módulo de Estoque

Portfólio de QA sobre um módulo de gestão de estoque: cadastro de produtos com variações de cor e tamanho, consulta de saldos, edição de parâmetros de reposição e inativação de variações.

| Regras de negócio | Testes automatizados | Defeitos investigados | Cobertura por RN |
| :---: | :---: | :---: | :---: |
| **14** | **10** | **4** | **50%** |

O que está documentado no repositório:

- **14 regras de negócio e 14 critérios de aceite** formalizados a partir do comportamento observado no sistema
- **9 casos de teste** com pré-condição, massa, passos, resultado esperado e evidência anexada
- **4 defeitos** investigados até a causa no código e no banco — três corrigidos e retestados, um ainda aberto
- **10 testes automatizados** em Java, Selenium WebDriver e JUnit, no padrão Page Object
- **Validação de persistência em SQL**, além do que a interface exibe

**Escopo declarado:** o trabalho de QA cobre o módulo de estoque. Os módulos de vendas e gerencial existem na aplicação, mas não foram testados formalmente. Os gaps de cobertura estão registrados abertamente na matriz de cobertura do projeto.

**Repositório:** [🔗 VarejoSync — Módulo de Estoque](https://github.com/janamirelly/varejosync-estoque-qa)

---

## Como eu trabalho

**Análise e documentação** — leio o comportamento do sistema para extrair a regra de negócio, escrevo o critério de aceite e só então desenho o caso de teste. Cada teste tem origem em uma regra e destino em uma evidência.

**Execução** — testes funcionais, negativos e exploratórios, com particionamento de equivalência e análise de valor limite. Registro de defeito com comportamento esperado, comportamento obtido, passos de reprodução e evidência.

**Testes de API** — requisições no Postman contra o backend, comparando a resposta com a regra documentada e com o que efetivamente persistiu no banco. Foi por esse caminho que encontrei o defeito ainda aberto do projeto.

**Validação em banco** — consultas SQL para conferir pré e pós-condição. Três dos quatro defeitos do projeto só ficaram visíveis no banco: a interface mostrava sucesso.

**Automação de interface** — suíte em Java com Selenium WebDriver e JUnit, estruturada em Page Object, com massa de teste gerada e limpeza de dados entre execuções.

---

## Ferramentas de QA

<div>
  <img src="https://img.shields.io/badge/Testes%20Funcionais-2563eb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Postman-f97316?style=for-the-badge&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Selenium-43b02a?style=for-the-badge&logo=selenium&logoColor=white" />
  <img src="https://img.shields.io/badge/JUnit-25a162?style=for-the-badge&logo=junit5&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ea2d2e?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-c71a36?style=for-the-badge&logo=apachemaven&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-334155?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Notion-0f172a?style=for-the-badge&logo=notion&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-ef4444?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-111827?style=for-the-badge&logo=github&logoColor=white" />
</div>

## Base técnica

<div>
  <img src="https://img.shields.io/badge/HTML-e34f26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS-1572b6?style=for-the-badge&logo=css&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003b57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL%20Server-cc2927?style=for-the-badge&logoColor=white" />
</div>

---

## Em estudo — 2º semestre de 2026

- **Playwright** para testes de API
- **GitHub Actions** para execução automatizada da suíte
- **WireMock** com Docker para simulação de serviços
- **k6** para testes de performance

Ainda sem entrega publicada. Conforme cada tema vira código, entra no repositório do projeto.

---

## Contato

[LinkedIn](https://www.linkedin.com/in/janayna-mirelly-dev) · [E-mail](mailto:janaynamirelly@gmail.com)






