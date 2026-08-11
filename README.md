# ✍️ Escrever Melhor Sozinho — Miniguia de Autoestudo de Redação com NotebookLM

> Repositório criado para o desafio de projeto da DIO: uso de IA como ferramenta de aprendizagem ativa através da criação de um Caderno Temático no NotebookLM.

---

## 🎯 Contexto e Objetivos

**Assunto escolhido:** Técnicas de autoestudo para melhorar a escrita/redação (foco em texto dissertativo-argumentativo, modelo Enem/vestibular) **sem depender de um professor ou corretor externo**.

**Por que esse tema?**
Nem todo mundo tem acesso constante a alguém que corrija seus textos. Este caderno reúne métodos de autorrevisão, prática deliberada e critérios objetivos de avaliação para que qualquer pessoa consiga identificar e corrigir os próprios erros de escrita de forma autônoma.

**Objetivos de estudo:**
- [ ] Entender quais critérios oficiais são usados para avaliar uma redação (competências do Enem) e transformá-los em checklist de autoavaliação.
- [ ] Aprender técnicas concretas de autorrevisão (leitura em etapas, leitura invertida, diário de erros, distanciamento temporal).
- [ ] Construir uma rotina de prática que não depende de terceiros para gerar evolução consistente.
- [ ] Sair com prompts prontos para usar IA como "espelho crítico" do próprio texto, sem que ela escreva por mim.

---

## 🔎 Curadoria de Fontes

Fontes abertas selecionadas e carregadas no NotebookLM:

| # | Título | Tipo | Link | Por que escolhi |
|---|--------|------|------|------------------|
| 1 | A Redação do Enem 2025 — Cartilha do Participante (INEP) | PDF oficial | https://download.inep.gov.br/publicacoes/institucionais/avaliacoes_e_exames_da_educacao_basica/a_redacao_no_enem_2025_cartilha_do_participante.pdf | Fonte primária e oficial: define exatamente os 5 critérios (competências) usados para nota — a base de qualquer autoavaliação séria. |
| 2 | Como treinar redação sozinho para o Enem: guia completo | Artigo | https://aprovatotal.com.br/treinar-redacao-sozinho-enem/ | Traz técnicas práticas de autorrevisão (leituras separadas por critério, diário de erros). |
| 3 | Como fazer a autorrevisão da sua prova de redação | Artigo | https://blog.imaginie.com.br/prova-de-redacao-autorevisao/ | Apresenta a técnica da leitura de trás para frente e discute a dependência excessiva de correção por professor. |
| 4 | Como treinar redação sozinho para o Enem 2026? | Artigo | https://querobolsa.com.br/revista/como-treinar-redacao-sozinho-para-enem | Reforça a ideia de qualidade > quantidade na prática e reprodução das condições reais de prova. |
| 5 | Técnicas de redação: saiba como escrever melhor! | Artigo | https://faculdade.grancursosonline.com.br/blog/tecnicas-de-redacao/ | Cobre a etapa de planejamento/rascunho antes da escrita, complementando as técnicas de revisão pós-escrita. |

**Critérios de seleção:** priorizei 1 fonte oficial/institucional (para os critérios objetivos de avaliação) combinada com artigos práticos e complementares entre si (planejamento → escrita → autorrevisão), evitando fontes que só vendem cursos como conteúdo central.

---

## 🧪 Engenharia de Prompts e "Cicatrizes"

> Esta seção é para você preencher enquanto testa no NotebookLM — deixei os prompts sugeridos prontos e a estrutura de registro. Documentar o *processo real* (o que funcionou, o que não funcionou) é o que dá valor a essa seção.

### Prompt 1 — Extrair os critérios objetivos
**Prompt sugerido:**
```
Com base na Cartilha do Participante do INEP, liste as 5 competências avaliadas na redação do Enem e, para cada uma, escreva uma pergunta de autoavaliação que eu possa fazer ao meu próprio texto.
```
**Resposta obtida (resumo):** *[preencha após testar]*
**Fontes citadas pela IA:** *[preencha]*
**Dificuldades encontradas:** *[ex: a IA generalizou demais / não citou a competência certa / etc.]*
**Ajuste feito:** *[como você reformulou]*
**Prompt refinado:** *[preencha]*

---

### Prompt 2 — Consolidar técnicas de autorrevisão
**Prompt sugerido:**
```
Compare as técnicas de autorrevisão mencionadas nos artigos carregados (leitura em etapas, leitura invertida, diário de erros, leitura em voz alta) e organize-as em uma checklist na ordem em que devem ser aplicadas após terminar de escrever um texto.
```
**Resposta obtida (resumo):** *[preencha]*
**Dificuldades encontradas:** *[preencha]*
**Prompt refinado:** *[preencha]*

---

### Prompt 3 — Testar se a IA "cola" nas fontes ou alucina
**Prompt sugerido:**
```
Existe alguma técnica nas fontes carregadas que recomenda pedir para a IA corrigir minha redação inteira? Responda apenas com base nos documentos, e diga "não encontrado" se não houver.
```
**Objetivo do teste:** verificar se a IA inventa recomendações que não estão nas fontes (alucinação) — importante porque o tema é justamente *não* depender de correção externa.
**Resultado:** *[preencha]*

---

### 💡 Principais aprendizados sobre prompt engineering (preencha ao final)
- *[ex: pedir para a IA responder "com base apenas nas fontes" reduziu respostas genéricas]*
- *[ex: prompts que pedem checklist/tabela geram material mais reutilizável que prompts abertos]*
- *[ex: dividir "avaliação" e "técnica de revisão" em prompts separados trouxe respostas mais precisas]*

---

## 📖 Miniguia de Estudo (Entrega Final)

### Resumos Estruturados

#### 1. Os critérios que definem uma boa redação (base oficial — Enem)
A avaliação oficial se baseia em 5 competências: domínio da norma culta escrita; compreensão da proposta e aplicação de conhecimentos de diferentes áreas; capacidade de organizar e defender um ponto de vista com argumentos; domínio dos mecanismos linguísticos de argumentação (coesão); e elaboração de uma proposta de intervenção para o problema discutido. Transformar cada uma dessas competências em uma pergunta objetiva é o primeiro passo para conseguir se autoavaliar sem depender de terceiros.

#### 2. Planejamento antes de escrever
Antes de redigir, vale reservar alguns minutos para rascunhar as ideias principais e montar um esboço com o que será dito em cada parágrafo. Isso evita perda de foco durante a escrita e facilita a revisão depois, porque você já sabe o que o texto *deveria* estar dizendo.

#### 3. Técnicas de autorrevisão
- **Leituras separadas por critério:** ler o texto três vezes, cada vez com um foco diferente (gramática; estrutura/argumentação; proposta de intervenção), em vez de tentar avaliar tudo de uma vez.
- **Leitura invertida:** ler o texto de trás para frente ajuda a focar na grafia de cada palavra isoladamente, sem se distrair com o sentido geral — útil para pegar erros ortográficos.
- **Distanciamento temporal:** reler o texto (de preferência em voz alta) cerca de 24h depois de escrito revela problemas de coesão e repetição que passam despercebidos na hora.
- **Diário de erros:** anotar os erros recorrentes de cada redação cria um padrão visível ao longo do tempo, permitindo atacar as falhas mais frequentes primeiro.

#### 4. Rotina e repertório
Especialistas convergem em um ponto: qualidade da prática importa mais que quantidade. Escrever um texto por semana, revisar com atenção e só then partir para o próximo tende a gerar mais evolução do que escrever muitos textos sem análise. Ler artigos de opinião e notícias regularmente também amplia o repertório usado como argumento.

---

### 📘 Glossário

| Termo | Definição |
|-------|-----------|
| Competências (Enem) | Os 5 critérios oficiais usados para pontuar a redação, de 0 a 200 cada, somando até 1000 pontos. |
| Coesão textual | Encadeamento lógico entre frases e parágrafos, feito por conectivos e retomadas (pronomes, sinônimos etc.). |
| Coerência | Consistência interna das ideias do texto — argumentos que não se contradizem e fazem sentido em conjunto. |
| Repertório sociocultural | Conhecimentos externos (históricos, filosóficos, dados, referências culturais) usados para embasar a argumentação. |
| Proposta de intervenção | Parte final do texto dissertativo-argumentativo em que se propõe uma solução prática para o problema discutido. |
| Modalidade escrita formal | Registro de língua exigido na redação: sem gírias, com gramática normativa. |
| Texto dissertativo-argumentativo | Tipo textual que defende um ponto de vista por meio de argumentos organizados, típico de provas como o Enem. |
| Autorrevisão | Processo de reler e corrigir o próprio texto de forma sistemática, sem depender de correção externa. |
| Diário de erros | Registro contínuo dos erros mais recorrentes cometidos, usado para direcionar a prática. |

---

### 🔁 Prompts Reutilizáveis para Revisão

1. **Para checar aderência aos critérios oficiais:**
   ```
   Com base na Cartilha do Participante, avalie hipoteticamente que aspectos um texto precisaria ter para atender bem à Competência [1 a 5]. Liste em formato de checklist.
   ```

2. **Para revisar técnicas antes de uma sessão de escrita:**
   ```
   Resuma em até 5 bullets as técnicas de autorrevisão presentes nas fontes carregadas, na ordem em que devem ser aplicadas após terminar um texto.
   ```

3. **Para gerar um roteiro de prática semanal:**
   ```
   Com base nas recomendações de rotina de estudo presentes nas fontes, monte um cronograma semanal de prática de redação para quem estuda sozinho, sem correção externa.
   ```

4. **Para testar meu próprio entendimento (autoavaliação socrática):**
   ```
   Me faça 5 perguntas, uma para cada competência do Enem, que eu deveria conseguir responder sobre o meu próprio texto antes de considerá-lo pronto.
   ```

---

## 🛠️ Ferramentas utilizadas
- [NotebookLM](https://notebooklm.google/)
- GitHub (versionamento e portfólio)

## 👤 Autor
*[Seu nome]* — *[link do LinkedIn / portfólio, opcional]*
