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

```
Com base na Cartilha do Participante do INEP, liste as 5 competências avaliadas na redação do Enem e, para cada uma, escreva uma pergunta de autoavaliação que eu possa fazer ao meu próprio texto.
```
De acordo com a Cartilha do Participante do Inep, a redação do Enem é avaliada por meio de cinco competências, cada uma valendo até 200 pontos
. Abaixo, listo as competências e uma pergunta de autoavaliação para cada uma:
Competência I: Demonstrar domínio da modalidade escrita formal da língua portuguesa. Esta competência avalia se o texto respeita as regras gramaticais, a ortografia, a acentuação e se apresenta uma construção sintática complexa e fluida
.
Pergunta de autoavaliação: "Meu texto segue as regras gramaticais da norma-padrão e utiliza um vocabulário formal, sem gírias, marcas de oralidade ou erros recorrentes de pontuação e concordância?"
.
Competência II: Compreender a proposta de redação e aplicar conceitos das várias áreas de conhecimento para desenvolver o tema dentro dos limites estruturais do texto dissertativo-argumentativo em prosa. Aqui, verifica-se se o candidato abordou o tema completo (sem tangenciar) e se utilizou um repertório sociocultural (conhecimentos de outras áreas como História, Sociologia ou Literatura) de forma produtiva
.
Pergunta de autoavaliação: "Eu abordei todos os elementos da frase temática e utilizei conhecimentos externos que realmente ajudam a validar o meu ponto de vista, em vez de apenas citar frases prontas?"
.
Competência III: Selecionar, relacionar, organizar e interpretar informações, fatos, opiniões e argumentos em defesa de um ponto de vista. Esta competência foca na inteligibilidade do texto e na existência de um projeto de texto estratégico e claro
.
Pergunta de autoavaliação: "Os meus argumentos estão organizados de forma lógica e progressiva, mostrando que planejei a estrutura do texto para defender minha tese de maneira convincente?"
.
Competência IV: Demonstrar conhecimento dos mecanismos linguísticos necessários para a construção da argumentação. Avalia-se a coesão textual, ou seja, como as frases e os parágrafos são interligados por meio de conectivos e outros recursos para evitar repetições excessivas
.
Pergunta de autoavaliação: "Utilizei uma variedade de conectivos (como 'além disso', 'contudo', 'nesse sentido') para ligar minhas ideias, garantindo que o texto flua bem e que as partes não pareçam soltas?"
.
Competência V: Elaborar proposta de intervenção para o problema abordado, respeitando os direitos humanos. O candidato deve propor uma solução concreta para o problema discutido, contendo cinco elementos obrigatórios: agente, ação, meio/modo, efeito e detalhamento
.
Pergunta de autoavaliação: "Minha proposta de solução responde explicitamente quem fará, o que será feito, como será feito, qual o objetivo e inclui um detalhamento extra, tudo isso respeitando os direitos humanos?"

---

### Prompt 2 — Consolidar técnicas de autorrevisão

```
Compare as técnicas de autorrevisão mencionadas nos artigos carregados (leitura em etapas, leitura invertida, diário de erros, leitura em voz alta) e organize-as em uma checklist na ordem em que devem ser aplicadas após terminar de escrever um texto.
```
Com base nos artigos fornecidos, a autorrevisão é uma etapa essencial para garantir a qualidade do texto, permitindo identificar erros de grafia, falta de coerência e problemas de coesão que podem passar despercebidos durante a escrita sob pressão
.
Abaixo, apresento uma comparação entre as técnicas mencionadas e uma checklist sugerida na ordem de aplicação após a conclusão do rascunho:
Comparação das Técnicas de Autorrevisão
Leitura em Etapas (Uma coisa de cada vez): Foca em isolar problemas específicos. O ideal é começar pelos pontos fracos (como pontuação ou coerência) e depois passar para repetições e ortografia
.
Leitura em Voz Alta: Serve para perceber a fluidez do texto. Ajuda a identificar repetições viciosas, falhas de coesão e problemas na construção das frases que a leitura silenciosa pode omitir
.
Leitura Invertida (De trás para frente): É uma técnica técnica para microdetalhes. Ao ler o texto de trás para frente, você quebra a sequência lógica e foca apenas na grafia das palavras, facilitando a identificação de erros de ortografia e acentuação
.
Diário de Erros (Acompanhamento): Mais do que uma revisão imediata, é uma estratégia de longo prazo. Consiste em categorizar os erros por competência e acompanhar os padrões de falhas para não repeti-los nos próximos textos
.
Checklist de Autorrevisão (Ordem de Aplicação)
Após terminar de escrever seu texto, siga estes passos:
[ ] Faça um "descanso" visual: Pare e respire fundo por 10 a 30 segundos antes de começar a ler, para distanciar-se do que acabou de escrever e ganhar um olhar mais crítico
.
[ ] Leitura em Etapas (Foco Global): Verifique primeiro se você atendeu ao tema, se a tese está clara e se os parágrafos estão conectados logicamente (coerência e coesão)
.
[ ] Leitura em Voz Alta (Foco no Ritmo): Leia o texto para si mesmo para encontrar frases muito longas, falta de conectivos ou palavras repetidas excessivamente
.
[ ] Leitura Invertida (Foco Gramatical): Leia as palavras isoladamente, do fim para o início do texto, para conferir acentuação e ortografia sem se distrair com o sentido das frases
.
[ ] Alimentação do Diário de Erros: Após identificar e corrigir as falhas (ou após receber uma correção externa), anote os erros cometidos separando-os pelas competências do Enem para evitar que apareçam na próxima produção
.
Dica extra dos fontes: Se você fizer qualquer alteração em uma frase durante a revisão, lembre-se de reler o parágrafo inteiro para garantir que a concordância e a lógica ainda façam sentido

---

### Prompt 3 — Testar se a IA "cola" nas fontes ou alucina

```
Existe alguma técnica nas fontes carregadas que recomenda pedir para a IA corrigir minha redação inteira? Responda apenas com base nos documentos, e diga "não encontrado" se não houver.
```
Não encontrado.
Pelo contrário, as fontes advertem que o estudante deve evitar utilizar inteligências artificiais na hora de escrever o texto
. A recomendação dos especialistas é não se sabotar pedindo ideias ao ChatGPT ou qualquer outra IA que entregue o conhecimento pronto, pois essa prática traz pouco aprendizado e não reflete as condições reais da prova, onde não há esse tipo de consulta
. As fontes focam em técnicas de autorrevisão manual e sugerem, quando necessário, buscar correções feitas por professores especialistas

---

## 📖 Miniguia de Estudo

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
Renan Silva Quadros
