# simulador-inteligente-de-entrevista

# Projeto de Entrevista Técnica com IA

## 🎯 Objetivo do Projeto
O objetivo foi **simular uma entrevista estruturada para uma vaga de Cientista de Dados Júnior**, cobrindo:
1. Título da vaga e propósito do cargo  
2. Senioridade esperada  
3. Stack de tecnologias e práticas essenciais  
4. Soft skills valorizados  

Após coletar as respostas, foi gerado um **resumo analítico da vaga** e conduzida uma entrevista técnica simulada para avaliar conhecimentos práticos.

---

## 🤖 Como a IA foi Utilizada
- **Prompts**: estruturados para conduzir a entrevista com **uma pergunta por vez**.  
- **Lógica**: seguiu uma ordem fixa de temas e só avançou após cada resposta.  
- **Ferramentas**:  
  - Memória para registrar que o candidato tem 1h/dia disponível para estudos.  
  - Busca na web para sugerir cursos e vídeos de apoio.  
  - Estrutura de entrevista para simular perguntas técnicas e avaliar respostas.  

---

## 📝 Exemplos de Perguntas e Respostas

**Pergunta:**  
Você mencionou que Python é essencial. Poderia me explicar como você usaria **Pandas** e **NumPy** em conjunto para preparar um conjunto de dados antes de aplicar um modelo de machine learning?

**Resposta:**  
Usaria Pandas para carregar, inspecionar e manipular dados tabulares (leitura de arquivos, seleção de colunas, tratamento de valores ausentes, encoding, joins) e NumPy para operações numéricas vetorizadas e eficientes (normalização, padronização, cálculos matriciais).  
Fluxo típico: carregar dados com Pandas → limpar e transformar (Pandas) → converter para arrays NumPy (.values ou .to_numpy()) → aplicar transformações numéricas (NumPy) → entregar os arrays finais ao modelo de machine learning.

---

**Pergunta:**  
Imagine que você tem um conjunto de dados com **valores ausentes e variáveis categóricas**. Quais técnicas você aplicaria para tratar esses problemas antes de treinar um modelo de machine learning?

**Resposta:**  
- Valores ausentes: remoção de linhas/colunas (se o impacto for pequeno), imputação (média/mediana, moda, categoria “desconhecido”), ou métodos mais robustos (KNN, regressão).  
- Variáveis categóricas: One-Hot Encoding, Ordinal Encoding ou Target/Frequency Encoding em casos de alta cardinalidade.  
- Sempre validando o impacto das escolhas com cross-validation.

---

**Pergunta:**  
Explique como você avaliaria o desempenho de um modelo de **classificação**. Quais métricas você utilizaria além da acurácia, e em quais situações cada uma delas é mais relevante?

**Resposta:**  
- Precisão: relevante quando falsos positivos são caros.  
- Recall: crítico quando falsos negativos são inaceitáveis.  
- F1-score: equilíbrio entre precisão e recall.  
- ROC-AUC: avalia separação do modelo independentemente do limiar.  
- Matriz de confusão: análise detalhada dos tipos de erro.  

---

## 🔄 Como Reproduzir ou Entender a Solução
1. **Definir a estrutura da entrevista**: criar sequência fixa de perguntas (vaga → senioridade → stack → soft skills).  
2. **Aplicar lógica de entrevista**: fazer **uma pergunta por vez**, esperar resposta, e só então avançar.  
3. **Gerar resumo analítico**: consolidar todas as respostas em um perfil da vaga.  
4. **Simular entrevista técnica**: elaborar perguntas práticas sobre Python, SQL, estatística e machine learning.  
5. **Diagnóstico final**: avaliar pontos fortes e áreas de evolução do candidato.  
6. **Plano de estudos**: sugerir cronograma prático com vídeos e exercícios, adaptado ao tempo disponível (1h/dia).  

---

## ✅ Conclusão
Esse projeto mostra como a IA pode ser usada para **estruturar entrevistas técnicas**, avaliar candidatos e propor planos de desenvolvimento.  
Qualquer pessoa pode reproduzir seguindo a ordem das perguntas, registrando respostas e consolidando em um resumo analítico.

## Prints:

<img width="1068" height="579" alt="image" src="https://github.com/user-attachments/assets/c9cf999c-eafd-4598-bebc-d435f26eefbf" />

<img width="1042" height="549" alt="image" src="https://github.com/user-attachments/assets/1d939d51-2963-4086-a6de-4d87ed3d13f0" />


---

# Projeto de Entrevista com IA para Vaga de Psicologia

## 🎯 Objetivo do Projeto
O objetivo foi **simular uma entrevista técnica estruturada** para uma vaga de Psicólogo Organizacional Júnior, conduzida passo a passo.  
A entrevista seguiu uma ordem pré-definida de perguntas sobre:
1. Título e propósito da vaga  
2. Senioridade esperada  
3. Soft skills valorizados  

Após a coleta das respostas, foi gerado um **resumo analítico** da vaga e uma entrevista simulada com candidato.

---

## 🤖 Como a IA foi Utilizada
- **Prompts:** Foram usados comandos claros e diretos para guiar a entrevista, sempre com **uma pergunta por vez**.  
- **Lógica:** A IA seguiu uma sequência fixa de temas (Título → Senioridade → Soft Skills → Resumo).  
- **Ferramentas:**  
  - Estrutura de diálogo para perguntas e respostas.  
  - Geração de resumo analítico com base nas informações fornecidas.  
  - Simulação de entrevista com candidato, explorando formação, experiência, soft skills e objetivos de carreira.  

---

## 📝 Exemplos de Perguntas e Respostas

### Perguntas sobre a vaga
- **Pergunta:** "Qual é o título da vaga e qual o propósito principal desse cargo?"  
- **Resposta:** "Psicólogo Organizacional"

- **Pergunta:** "Qual a senioridade esperada e por quê?"  
- **Resposta:** "Junior"

- **Pergunta:** "Quais comportamentos ou atitudes são mais valorizados?"  
- **Resposta:** "Proatividade, criatividade, pensamento crítico, transparência e flexibilidade"

---

### Perguntas na entrevista simulada com candidato
- **Pergunta:** "Você poderia me contar um pouco sobre sua formação acadêmica e como ela se relaciona com a área de Psicologia Organizacional?"  
- **Resposta:** "Sou formado em Psicologia. Logo, tenho o conhecimento teórico na área de Psicologia Organizacional."

- **Pergunta:** "Quais experiências práticas você já teve em ambientes organizacionais?"  
- **Resposta:** "Fiz estágio durante um ano em uma empresa, atuando na parte de RH, recrutamento e seleção."

- **Pergunta:** "Qual dessas atitudes você considera seu ponto mais forte e pode dar um exemplo concreto?"  
- **Resposta:** "Criatividade, por já ter atuado por muito tempo na Publicidade; sempre busco ser transparente nas tomadas de decisões das empresas e tenho uma facilidade muito grande de ser flexível na rotina do trabalho e tenho muita adaptabilidade."

---

## 🔄 Como Reproduzir ou Entender a Solução
1. **Definir a sequência de perguntas** que serão feitas (pré-estruturadas).  
2. **Aplicar a regra de uma pergunta por vez**, aguardando resposta antes de prosseguir.  
3. **Registrar as respostas** do usuário ou candidato.  
4. **Gerar um resumo analítico** apenas após confirmação explícita.  
5. **Simular entrevistas** explorando formação, experiência, soft skills e objetivos.  
6. **Documentar em Markdown** para fácil leitura e compartilhamento em GitHub.  

---

## ✅ Benefícios da Abordagem
- Estrutura clara e organizada.  
- Entrevista conduzida de forma natural e progressiva.  
- Resumo analítico que sintetiza informações de forma objetiva.  
- Fácil replicação em outros contextos de seleção ou treinamento.

## Prints:
<img width="961" height="566" alt="image" src="https://github.com/user-attachments/assets/0eddff87-3265-413e-8cef-7b9d1e487b96" />

<img width="978" height="533" alt="image" src="https://github.com/user-attachments/assets/cb50a9e0-d704-42c1-9e8c-1a1344c345c8" />


