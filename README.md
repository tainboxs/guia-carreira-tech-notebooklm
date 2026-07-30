# 🚀 Guia de Posicionamento Profissional e Otimização para Vagas de Tecnologia

> **Projeto prático desenvolvido para o Desafio de Projeto "Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM" da DIO em parceria com o Santander.**

---

## 📌 Contexto e Objetivos

O mercado de tecnologia em grandes multinacionais é altamente competitivo, especialmente para estudantes em busca do primeiro estágio. Para se destacar, não basta apenas ter conhecimento técnico; é fundamental saber comunicar esse valor por meio do **LinkedIn**, de um **currículo direcionado** e de uma **comunicação assertiva em entrevistas**.

Este caderno temático no NotebookLM foi criado com o objetivo de centralizar, analisar e sintetizar as melhores práticas do mercado sobre:
- Otimização do perfil do LinkedIn focado nos algoritmos de busca e recrutadores.
- Adaptação estratégica do currículo para os requisitos específicos de cada vaga (compatibilidade com ATS).
- Preparação para entrevistas comportamentais e técnicas utilizando estruturas consolidadas do mercado.

---

## 📚 Curadoria de Fontes

Para garantir respostas embasadas e de alta qualidade no NotebookLM, foram selecionadas e carregadas as seguintes fontes abertas de relevância no setor:

1. **Guia Oficial de Otimização do LinkedIn:** [Otimizar seu perfil LinkedIn para atrair recrutadores em 2026](https://www.jobalign.app/pt/otimizar-perfil-linkedin.html)
2. **Manual da Metodologia STAR para Entrevistas:** [Metodologia STAR: como usar em entrevistas de emprego](https://www.gupy.io/blog-do-emprego/metodologia-star)
3. **Guia de Construção de Currículos para Tech (Foco em ATS):** [Currículo para profissional de tecnologia em 2026: estrutura ATS + portfólio que convence RH](https://blog.criarcv.com.br/curriculo-tech-passar-ats-2026/)
4. **Relatório de Tendências de Carreira em Tecnologia:** [Mercado de tecnologia em constante evolução: tendências e oportunidades de carreira](https://www.insper.edu.br/pt/conteudos/tecnologia/mercado-de-tecnologia)

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Abaixo estão registrados os testes e refinamentos de prompts realizados durante a interatividade com o NotebookLM, demonstrando o processo de aprendizado ativo:

### 🧪 Teste 1: Solicitação Inicial vs. Prompt Refinado
- **Prompt Inicial (Genérico):** *"Como deixar o meu currículo bom para conseguir um estágio?"*
- **Resultado/Problema:** A resposta trouxe dicas genéricas (como "evite erros de português" e "coloque seus dados de contato"), sem especificidade para a área de tecnologia.
- **Prompt Refinado:** *"Atue como um recrutador sênior de uma multinacional de tecnologia. Com base nas fontes sobre ATS e Metodologia STAR, analise como um estudante de Engenharia/Tecnologia deve descrever seus projetos acadêmicos e pessoais de Python/IoT no currículo para demonstrar impacto prático."*
- **Aprendizado:** Dar um papel (*roleplay*) à IA e delimitar o escopo da área e das tecnologias gera sugestões focadas em métricas e verbos de ação.

### 🧪 Teste 2: Extração de Palavras-Chave para o LinkedIn
- **Prompt Refinado:** *"Com base nos materiais de otimização de LinkedIn e tendências do mercado, crie uma lista comparativa de palavras-chave que não podem faltar no título (Headline) e no resumo ('Sobre') de quem busca vagas em desenvolvimento e análise de dados."*
- **Resultado:** A IA gerou uma estrutura clara dividida em competências técnicas (Hard Skills) e metodologias/postura (Soft Skills), prontas para aplicação direta no perfil.

---

## 📘 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado das Estratégias

#### 🔷 Otimização do LinkedIn
- **Título (Headline):** Substitua termos genéricos como "Em busca de oportunidade" por títulos diretos focados em soluções e tecnologias. *Exemplo:* `Estudante de Engenharia de Software | Python | Análise de Dados | IoT & Automação`.
- **Seção "Sobre":** Narrativa clara mostrando sua trajetória, os problemas que você gosta de resolver e os principais projetos já desenvolvidos.
- **Seção "Destaque":** Fixe links diretos para o seu GitHub, artigos ou projetos em destaque.

#### 📄 Adaptação de Currículo por Vaga
- **Mapeamento de Requisitos:** Identifique as palavras-chave principais na descrição da vaga (*Job Description*) e garanta que elas apareçam no seu currículo.
- **Descrição de Projetos com Foco em Resultados:** Use a estrutura *[Ação] + [Tecnologia] + [Resultado/Impacto]*.
  - *Fraco:* "Fiz um projeto em Python."
  - *Forte:* "Desenvolvi sistema automatizado de extração e tratamento de dados em Python (Pandas), reduzindo o tempo de processamento manual em tarefas acadêmicas."

#### 🗣️ Preparação para Entrevistas (Técnica STAR)
Ao responder perguntas sobre experiências anteriores, estruture a resposta da seguinte forma:
- **S (Situação):** Contexto inicial do problema ou projeto.
- **T (Tarefa):** O seu papel ou desafio específico naquela situação.
- **A (Ação):** O que você fez para resolver (quais ferramentas e raciocínio utilizou).
- **R (Resultado):** O impacto gerado, o aprendizado obtido ou o indicador alcançado.

---

### 📖 Glossário de Conceitos Aprendidos

| Termo | Definição |
| :--- | :--- |
| **ATS (Applicant Tracking System)** | Sistemas automatizados que filtram e ranqueiam currículos com base na correspondência de palavras-chave antes da análise humana. |
| **Metodologia STAR** | Framework de resposta para entrevistas focado em Situação, Tarefa, Ação e Resultado. |
| **Keyword Matching** | Processo de alinhar os termos do seu currículo e LinkedIn exatamente aos termos solicitados na descrição da vaga. |
| **Networking Ativo** | Conectar-se estrategicamente com profissionais e recrutadores enviando mensagens personalizadas e agregando valor à rede. |
| **Hard Skills vs. Soft Skills** | Competências técnicas (ex.: Python, SQL, IoT) versus competências comportamentais (ex.: inteligência emocional, resolução de problemas). |

---

### 🛠️ Promptbook (Prompts Reutilizáveis)

Estes prompts podem ser reutilizados futuramente no NotebookLM para apoiar novas revisões de perfil e currículo:

```text
[Prompt 1 - Análise de Compatibilidade]
"Copie e cole a descrição da vaga X abaixo e compare com minhas experiências listadas nas fontes. Liste 3 pontos fortes do meu perfil para essa vaga e 3 palavras-chave que preciso incluir no currículo."

[Prompt 2 - Simulação de Entrevista Comportamental]
"Faça 3 perguntas comportamentais típicas de processos seletivos de multinacionais para vagas de tecnologia. Após cada resposta minha, avalie se utilizei corretamente a estrutura STAR e sugira melhorias."

[Prompt 3 - Revisão de Headline e Resumo do LinkedIn]
"Com base no meu histórico de projetos, sugira 3 variações de título chaves para o LinkedIn e um rascunho da seção 'Sobre' focado em transmitir profissionalismo e clareza técnico-científica."
