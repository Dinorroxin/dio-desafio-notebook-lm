# dio-desafio-notebook-lm
Esse repositório é o o projeto do curso "Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM"

---

## Assunto
O assunto escolhido foi ajuda na elaboração de um Roadmap em cibersegurança, mais especificamente filtrando pelo nicho de **Arquitetura de Segurança**. 

Este estudo tem o objetivo de guiar sobre quais certificações e assuntos estudar primeiro e assim evitando de acabar batendo contra uma "parede" por não ter conhecimento prévio de um assunto específico

A seguir segue o prompt utilizado para utilizar do deep research fornecido pela IA para busca de fontes concretas e atuais
```
Me ajude a fazer um roadmap para de assuntos para estudar e ingressar na área de cibersegurança, focando no nicho de arquitetura de segurança mas aberto a outras áreas que no momento estão com reconhecimento elevado, utilize de deep research para buscar fonte concretas, atuais e oficiais como:
- Blogs
- Posts
- Vídeos
- Sites de divulgações de empregos
- PDFs
- Textos
```

e sua resposta
```
Com certeza! Criar um roadmap para **Arquitetura de Segurança** e áreas em alta (como Cloud Security e IA em Cyber) é uma excelente iniciativa. Como você solicitou fontes concretas e oficiais, a melhor forma de começar é usando nossa ferramenta de **Deep Research**.

Essa busca avançada vasculha a web em busca de documentos técnicos, blogs de especialistas e requisitos de vagas para montar um panorama completo. Apenas um lembrete: o Deep Research é um processo detalhado e **pode levar alguns minutos** para ser concluído.

Vou iniciar a pesquisa agora mesmo focando em:
*   Trilhas de aprendizado para Arquitetura de Segurança.
*   Certificações mais valorizadas (como CISSP, CCSP).
*   Tendências de mercado para 2024/2025.
*   Materiais oficiais (PDFs e sites de frameworks como NIST e ISO).

Pesquisa iniciada! Estou realizando uma busca profunda sobre o roadmap de cibersegurança e arquitetura de segurança.

Assim que os resultados aparecerem no seu **painel de fontes**, você poderá revisá-los e clicar em **"Importar"** para adicioná-los ao nosso caderno. Lembre-se que, se houver resultados de pesquisas anteriores pendentes no painel, será necessário revisá-los (importando ou excluindo) para visualizar os novos.

Enquanto a pesquisa é processada, você já tem algum conhecimento prévio em redes ou programação, ou gostaria de começar do absoluto zero?
```

## Fontes
Levando em consideração que eu utilizei de deep research para procurar as fontes, ele retornou 21 fontes, então pedi para para ele buscar listar 5 fontes com o seguinte prompt
```
tenho conhecimento prévio de rede, agora quero que cite 5 fontes mais impactantes que foram encontradas

A resposta de saída deve ter:

- **Nome da fonte**, seja jornal, blog ou empresa;
- **Motivo pelo qual foi escolhida**(deve possuir no máximo 2 linhas, seja direto e objetivo)
- **Pré-requisitos**para entender o assunto abordado
- **Url de acesso**
- **Data de atualização**
```

obtive a seguinte resposta
```
Com base nas fontes pesquisadas e no seu conhecimento prévio de redes, aqui estão as 5 fontes mais impactantes para o seu ingresso na arquitetura de cibersegurança:

**1. TripleTen (Blog)**
*   **Motivo pelo qual foi escolhida:** Oferece um roadmap de progressão detalhado, com prazos e metas salariais para cada nível de senioridade até o cargo de Arquiteto de Segurança.
*   **Pré-requisitos para entender o assunto abordado:** Conhecimentos fundamentais de TI, como sistemas operacionais (Windows/Linux) e bases de redes (TCP/IP e DNS).
*   **Url de acesso:** [https://tripleten.com/blog/posts/cybersecurity-career-path](https://tripleten.com/blog/posts/cybersecurity-career-path)
*   **Data de atualização:** 11 de maio de 2026.

**2. Destination Certification (Blog de Treinamento)**
*   **Motivo pelo qual foi escolhida:** É a fonte definitiva para diferenciar e entender a aplicação prática dos três principais frameworks de arquitetura de mercado: SABSA, TOGAF e Zachman.
*   **Pré-requisitos para entender o assunto abordado:** Experiência intermediária em segurança da informação e familiaridade com conceitos de gestão de risco corporativo.
*   **Url de acesso:** [https://destcert.com/resources/enterprise-security-architecture-models/](https://destcert.com/resources/enterprise-security-architecture-models/)
*   **Data de atualização:** 9 de novembro de 2025.

**3. Cloud Security Alliance - CSA (Organização Global)**
*   **Motivo pelo qual foi escolhida:** Fornece a matriz oficial CCM v4.1, que é o padrão ouro técnico com 207 controles essenciais para projetar arquiteturas seguras em ambientes de nuvem.
*   **Pré-requisitos para entender o assunto abordado:** Entendimento dos modelos de nuvem (IaaS, PaaS, SaaS) e do Modelo de Responsabilidade Compartilhada.
*   **Url de acesso:** [https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1](https://cloudsecurityalliance.org/artifacts/cloud-controls-matrix-v4-1)
*   **Data de atualização:** 27 de janeiro de 2026.

**4. Innov8World (Portal de Tecnologia)**
*   **Motivo pelo qual foi escolhida:** Foca nas tecnologias de alta demanda e reconhecimento no momento, como Arquitetura Zero Trust, segurança orientada por IA e infraestruturas SASE.
*   **Pré-requisitos para entender o assunto abordado:** Noções básicas de infraestrutura digital moderna e entendimento geral de defesas de rede.
*   **Url de acesso:** [https://www.innov8world.com/cybersecurity-trends/](https://www.innov8world.com/cybersecurity-trends/)
*   **Data de atualização:** 2026.

**5. CertStud (Blog de Especialização)**
*   **Motivo pelo qual foi escolhida:** Apresenta um comparativo técnico e financeiro focado no ROI (Retorno sobre Investimento) para quem deseja escolher entre as certificações TOGAF e SABSA.
*   **Pré-requisitos para entender o assunto abordado:** Vivência em engenharia de sistemas ou cibersegurança e interesse em avançar para cargos de liderança técnica.
*   **Url de acesso:** [https://certstud.com/blog/togaf-vs-sabsa-architecture-certification-comparison-2025](https://certstud.com/blog/togaf-vs-sabsa-architecture-certification-comparison-2025)
*   **Data de atualização:** 12 de agosto de 2025.
```

## Engenharia de prompt

Nestes exemplos utilizei para os prompts as seguintes técnicas:

**Clareza e Contexto**
- Contexto prévio declarado ("tenho conhecimento prévio de rede") — calibra nível técnico da resposta
- Objetivo explícito (ingressar na área, foco em arquitetura de segurança)

**Restrição de escopo**
- Tipos de fonte definidos (blogs, posts, vídeos, vagas, PDF, textos)
- Quantidade fechada ("5 fontes mais impactantes")

**Especificação de formato de saída**
- Schema de campos obrigatórios: nome da fonte, motivo, pré-requisitos, URL, data de atualização

**Controle de tamanho/tom**
- Limite de extensão por campo ("máximo 2 linhas, seja direto e objetivo")

**Instrução de ferramenta**
- Uso explícito de "deep research" como método de busca

**Iteração em cadeia**
- Segundo prompt refina e filtra o resultado do primeiro, ao invés de pedir tudo numa única query

# Estrutura final

## Resumo do conteúdo aprendido

No decorrer desse curso desenvolvi habilidades que antes eram apenas superficiais,com foco em comunicar melhor e obter resultados mais precisos na hora de escrever prompts. Colocando em prática os conceitos aprendidos, foi possível chegar emresultados muito mais próximos do desejado — especialmente ao dividir prompts amplos em etapas menores e ao definir formato de saída explícito.

## Glossário — Técnicas de Engenharia de Prompt

| Técnica | Definição | Quando usar |
|---|---|---|
| Clareza e Contexto | Instrução direta, sem ambiguidade, com papel/objetivo/restrições explícitos | Sempre, base de qualquer prompt |
| Zero-shot | Pedir a tarefa sem exemplo, só a instrução | Tarefas simples, modelo já entende o padrão |
| Few-shot | Fornecer exemplos de entrada/saída antes da tarefa real | Formato específico difícil de descrever só com texto |
| Chain-of-thought | Pedir raciocínio passo a passo antes da resposta final | Problemas lógicos, matemáticos, decisões complexas |
| Decomposição | Quebrar tarefa grande em subtarefas menores e sequenciais | Projetos multi-etapa, pesquisa extensa |
| Especificação de formato de saída | Definir estrutura exata da resposta (JSON, tabela, schema de campos) | Quando a resposta será reaproveitada em outro sistema/documento |
| Restrição de escopo | Limitar o que deve/não deve ser incluído | Evitar resposta genérica ou fora do foco |
| Controle de extensão | Definir tamanho máximo/mínimo por resposta ou campo | Evitar verbosidade, forçar objetividade |
| Persona/Role prompting | Atribuir papel específico ao modelo ("aja como...") | Calibrar tom, vocabulário, nível técnico |
| Prompt negativo | Indicar explicitamente o que evitar | Reduzir respostas genéricas ou fora de tom |
| Iteração em cadeia | Refinar prompt anterior com base no resultado obtido | Pesquisa exploratória, ajuste progressivo |
| Instrução de ferramenta | Indicar explicitamente qual recurso/método usar (ex: "deep research") | Quando o modelo tem múltiplas formas de responder |
| Autoavaliação/self-check | Pedir que o modelo revise a própria resposta antes de entregar | Tarefas com risco de erro |

## Possíveis prompts reutilizaveis

Os seguintes prompts não necessariamente podem ser utilizados somente no conteúdo abordado, mas sim em qualquer conteúdo que seja relacionado à estudos

```
Assuma o papel de um recrutador/mentor sênior de [área de estudo], diga onde o mercado está aquecido e o que devo priorizar na hora de aprender, visando ingressar no mercado de trabalho
```

e

```
Retorne uma lista com as certificações mais bem reconhecidas no mercado de [área de atuação] com:
- **Valores**
- **Tempo de duração**
- **Fonte** (que empresa está fornecendo)
- **Assunto abordado**
- **Pré-requisitos** (caso exista)
```
