# 🧠 Caderno Temático: Machine Learning na Saúde e Previsão de AVC

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Tema](https://img.shields.io/badge/tema-Machine%20Learning%20na%20Saúde-blue)
![IA](https://img.shields.io/badge/Inteligência%20Artificial-IA-purple)
![NotebookLM](https://img.shields.io/badge/ferramenta-NotebookLM-orange)

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um **Desafio de Projeto da DIO**, utilizando o **NotebookLM como ferramenta de aprendizagem ativa** para pesquisa, organização, comparação e análise crítica de informações.

O tema escolhido foi a aplicação de **Inteligência Artificial (IA) e Machine Learning (ML) na área da saúde**, com foco especial em:

- Modelos preditivos;
- Aplicações de Machine Learning na saúde;
- Previsão de Acidente Vascular Cerebral (AVC);
- Ensemble Learning;
- Random Forest;
- Gradient Boosting;
- Dados desbalanceados;
- Métricas de avaliação;
- Validação e generalização;
- Inteligência Artificial Explicável (XAI);
- Limitações e desafios da IA na prática clínica.

O objetivo não foi apenas reunir informações sobre Inteligência Artificial, mas compreender como os modelos são utilizados, como seus resultados devem ser avaliados e quais fatores limitam sua aplicação em situações reais.

---

# 🎯 Objetivos

## Objetivo geral

Compreender a utilização de Inteligência Artificial e Machine Learning na área da saúde, relacionando modelos preditivos e técnicas de Ensemble Learning à previsão de AVC.

## Objetivos específicos

- Compreender os fundamentos de Inteligência Artificial aplicada à saúde;
- Estudar os conceitos fundamentais de Machine Learning;
- Compreender modelos preditivos aplicados à medicina;
- Analisar aplicações de ML na previsão de AVC;
- Compreender o funcionamento de Ensemble Learning;
- Estudar algoritmos como Random Forest, Gradient Boosting, XGBoost, CatBoost e Stacking;
- Investigar o problema de dados desbalanceados;
- Compreender técnicas de balanceamento de dados;
- Comparar métricas como Accuracy, Precision, Recall e F1-score;
- Estudar técnicas de validação e generalização;
- Compreender a importância da validação externa e prospectiva;
- Investigar os desafios relacionados à interpretabilidade e XAI;
- Analisar questões de privacidade, viés e integração da IA ao ambiente clínico;
- Utilizar o NotebookLM como ferramenta de aprendizagem ativa;
- Desenvolver prompts reutilizáveis para futuras pesquisas.

---

# 📚 Curadoria de Fontes

Foram selecionadas fontes relacionadas aos diferentes níveis do estudo: fundamentos de IA, aplicações de Machine Learning na saúde, modelos preditivos, previsão de AVC, Ensemble Learning e desafios de implementação.

As fontes foram utilizadas como base para as análises realizadas no NotebookLM.

## 1. Pulock Deb Roy et al. (2025)

**Tema:** Machine Learning e Inteligência Artificial aplicada à saúde.

A fonte apresenta uma visão ampla das aplicações de ML na medicina, incluindo modelos preditivos, sistemas de apoio à decisão clínica e desafios relacionados à utilização de IA.

**Link:**

https://www.nature.com/articles/s41598-025-01855-w

---

## 2. Melnykova et al. (2025)

**Tema:** Machine Learning aplicado à previsão de AVC em dados desbalanceados.

Esta foi uma das principais fontes para compreender o problema de desbalanceamento de classes, técnicas de tratamento dos dados e comparação de algoritmos para previsão de AVC.

**Fonte:** Scientific Reports / Nature.

**Link:**

https://www.nature.com/articles/s41598-025-01855-w

---

## 3. Mohajer-Bastami et al. (2025)

**Tema:** Aplicações de Inteligência Artificial e Machine Learning na área da saúde/neurologia.

A fonte foi utilizada para ampliar a visão sobre as possibilidades de aplicação de IA na medicina, além da previsão de AVC.

**Link:**

https://www.scielo.br/j/csp/a/jyhKL6G4dZhcbchMD6bcS8s/?lang=pt

---

## 4. Zhang & Chen

**Tema:** Modelos preditivos e utilização de Gradient Boosting.

A fonte foi utilizada principalmente para compreender modelos preditivos, importância de variáveis e utilização de Gradient Boosting em problemas de previsão de risco.

---

## 5. Wikipedia — AI in Healthcare

**Tema:** Visão geral sobre Inteligência Artificial na saúde.

Foi utilizada como fonte complementar para contextualização de conceitos gerais relacionados à IA na área médica.

> **Observação:** A Wikipedia foi utilizada apenas como fonte complementar e contextual. As principais conclusões técnicas foram baseadas prioritariamente nos artigos científicos.

---

# 🗺️ Mapeamento dos Temas

A análise das fontes permitiu organizar o conhecimento em uma sequência que vai dos conceitos fundamentais até os desafios de implementação clínica.

## 1. Fundamentos

- Inteligência Artificial;
- Machine Learning;
- Aprendizado supervisionado;
- Sistemas de Apoio à Decisão Clínica (CDSS).

## 2. Modelos preditivos

- Predição de riscos;
- Classificação;
- Regressão;
- Registros Eletrônicos de Saúde (EHR).

## 3. Aplicações na saúde

- Previsão de doenças;
- Diagnóstico;
- Planejamento de tratamento;
- Estratificação de risco;
- Previsão de AVC.

## 4. Ensemble Learning

- Bagging;
- Random Forest;
- Boosting;
- Gradient Boosting;
- XGBoost;
- CatBoost;
- AdaBoost;
- Stacking;
- Voting Ensemble.

## 5. Problemas técnicos

- Dados desbalanceados;
- Overfitting;
- Dados incompletos;
- Ruído;
- Seleção de características;
- Generalização.

## 6. Avaliação

- Accuracy;
- Precision;
- Recall;
- F1-score;
- ROC-AUC;
- Matriz de confusão.

## 7. Aplicação clínica

- Validação interna;
- Validação externa;
- Validação prospectiva;
- Interpretabilidade;
- XAI;
- Privacidade;
- Viés algorítmico;
- Integração ao fluxo clínico.

---

# 🔬 Engenharia de Prompts

O NotebookLM foi utilizado de forma iterativa. Em vez de solicitar apenas um resumo das fontes, foram utilizados prompts para explorar diferentes dimensões do problema.

## Prompt 1 — Mapeamento dos temas

> Com base nas fontes fornecidas, identifique os principais conceitos relacionados à Inteligência Artificial na saúde, Machine Learning, modelos preditivos, Ensemble Learning, dados desbalanceados, validação e previsão de AVC. Organize os conceitos em uma sequência lógica do nível introdutório ao avançado.

### Objetivo

Identificar os conceitos recorrentes e criar uma estrutura inicial de estudo.

---

## Prompt 2 — Verificação das afirmações

> Verifique as afirmações apresentadas no mapeamento anterior. Classifique cada afirmação como sustentada, parcialmente sustentada ou não sustentada pelas fontes. Identifique generalizações indevidas e apresente uma versão mais precisa quando necessário.

### Objetivo

Evitar generalizações e identificar afirmações que precisavam de contextualização.

---

## Prompt 3 — Análise dos algoritmos

> Compare os algoritmos de Machine Learning mencionados nas fontes, diferenciando modelos individuais de estratégias de Ensemble Learning, como Bagging, Boosting e Stacking.

### Objetivo

Compreender as diferenças entre os principais algoritmos.

---

## Prompt 4 — Dados desbalanceados

> Explique como os estudos tratam o desbalanceamento de classes na previsão de AVC e quais métricas são mais adequadas para avaliar modelos nesse cenário.

### Objetivo

Compreender por que a Accuracy pode ser insuficiente em datasets desbalanceados.

---

## Prompt 5 — Variáveis preditoras

> Compare as variáveis utilizadas nos estudos de previsão de AVC, identificando quais são efetivamente utilizadas como entradas dos modelos e quais apresentam evidências de importância preditiva.

### Objetivo

Diferenciar variáveis utilizadas pelo modelo de variáveis comprovadamente importantes.

---

## Prompt 6 — Generalização

> Analise as estratégias de validação utilizadas nos estudos e explique quais fatores podem impedir que um modelo apresente o mesmo desempenho quando aplicado a uma população ou instituição diferente.

### Objetivo

Compreender o problema da generalização.

---

## Prompt 7 — Síntese crítica

> Com base nas fontes, existe um algoritmo universalmente superior para aplicações de Machine Learning na saúde? Compare Random Forest, Gradient Boosting, CatBoost e outros métodos citados.

### Objetivo

Evitar concluir que um único algoritmo é sempre superior.

---

## Prompt 8 — XAI

> Explique a importância da Inteligência Artificial Explicável na área da saúde e os problemas relacionados aos modelos considerados caixa-preta.

### Objetivo

Relacionar desempenho preditivo, interpretabilidade e confiança clínica.

---

# 🩹 Cicatrizes e Troubleshooting

Durante a pesquisa, algumas informações exigiram análise crítica e refinamento.

## 1. Generalização do desempenho do Random Forest

Inicialmente, o resultado de aproximadamente 90% nas métricas apresentadas no estudo de previsão de AVC poderia levar à interpretação de que o Random Forest seria universalmente o melhor algoritmo para esse problema.

Após a análise crítica, essa conclusão foi reformulada.

O resultado deve ser interpretado como:

> O Random Forest apresentou excelente desempenho no estudo específico analisado, considerando o dataset e a metodologia utilizados.

Isso não significa que o algoritmo seja universalmente superior.

---

## 2. Problema da Accuracy

Outro ponto identificado foi a utilização da Accuracy como principal indicador de desempenho.

Em datasets altamente desbalanceados, a Accuracy pode produzir uma impressão equivocada de eficiência.

Por exemplo, se 96% dos pacientes não possuem AVC, um modelo que sempre preveja "não AVC" pode alcançar aproximadamente 96% de Accuracy sem identificar corretamente nenhum caso positivo.

Por isso, métricas como:

- Recall;
- Precision;
- F1-score;
- Matriz de confusão;

são importantes para avaliar o desempenho.

---

## 3. Variáveis preditoras

Foi necessário diferenciar:

- Variáveis utilizadas como entrada;
- Variáveis que demonstraram importância;
- Variáveis mencionadas apenas como exemplos;
- Variáveis utilizadas em outros problemas clínicos.

Essa diferenciação evitou atribuir a determinado estudo variáveis que não foram efetivamente utilizadas no modelo de previsão de AVC.

---

## 4. Comparação entre estudos diferentes

Também foi necessário evitar comparações diretas entre resultados obtidos em problemas diferentes.

Por exemplo:

- Random Forest → previsão de AVC;
- Gradient Boosting → risco de hospitalização;
- CatBoost → despesas médicas.

Embora todos sejam exemplos de Machine Learning na saúde, os problemas, datasets, métricas e objetivos são diferentes.

Portanto, os resultados não devem ser interpretados como uma competição direta entre algoritmos.

---

## 5. Idade como variável importante

O valor de importância atribuído à idade em um dos estudos analisados pertence ao contexto específico daquele estudo.

Portanto, não é correto transferir automaticamente esse resultado para um modelo de previsão de AVC.

A importância de uma variável depende do:

- Dataset;
- Objetivo;
- População;
- Algoritmo;
- Pré-processamento;
- Método de avaliação.

---

# 📖 Miniguia de Estudo

# Capítulo 1 — Inteligência Artificial na Saúde

A Inteligência Artificial pode ser entendida como um conjunto de técnicas utilizadas para desenvolver sistemas capazes de realizar tarefas que normalmente exigiriam algum nível de cognição humana.

Na saúde, suas aplicações incluem:

- Diagnóstico;
- Análise de imagens;
- Predição de doenças;
- Estratificação de risco;
- Planejamento de tratamento;
- Sistemas de apoio à decisão.

Um dos principais conceitos identificados nas fontes é a ideia de **IA assistiva**.

Nesse modelo, a tecnologia não necessariamente substitui o profissional de saúde, mas fornece informações que podem auxiliar sua tomada de decisão.

### Principais desafios

- Transparência;
- Privacidade;
- Responsabilidade;
- Viés;
- Validação;
- Segurança.

---

# Capítulo 2 — Machine Learning

Machine Learning é um subcampo da Inteligência Artificial que permite que sistemas aprendam padrões a partir de dados.

No aprendizado supervisionado, o modelo recebe dados de entrada associados a resultados conhecidos.

O objetivo é aprender relações capazes de generalizar para novos dados.

### Exemplos

**Classificação:**

> Paciente → alto risco / baixo risco

**Regressão:**

> Paciente → previsão de um valor numérico

Na saúde, Machine Learning pode ser utilizado para prever riscos, identificar padrões e auxiliar decisões clínicas.

---

# Capítulo 3 — Modelos Preditivos

Modelos preditivos utilizam informações históricas para estimar resultados futuros.

Exemplos:

- Risco de doença;
- Probabilidade de hospitalização;
- Resposta a tratamentos;
- Probabilidade de AVC.

Esses modelos podem contribuir para uma abordagem mais preventiva e personalizada da medicina.

Entretanto, seu desempenho depende diretamente da qualidade e representatividade dos dados utilizados.

---

# Capítulo 4 — Métricas de Avaliação

As principais métricas estudadas foram:

### Accuracy

Representa a proporção geral de previsões corretas.

### Precision

Indica quantos dos casos classificados como positivos realmente eram positivos.

### Recall / Sensibilidade

Indica quantos dos casos positivos reais foram identificados pelo modelo.

### F1-score

Combina Precision e Recall por meio da média harmônica.

### ROC-AUC

Avalia a capacidade discriminativa do modelo em diferentes limiares de classificação.

Em problemas médicos, principalmente quando há desbalanceamento, não é recomendado analisar apenas a Accuracy.

---

# Capítulo 5 — Dados Desbalanceados

Dados desbalanceados ocorrem quando uma classe possui muito mais exemplos que outra.

A previsão de AVC é um exemplo clássico.

Em um dataset, pode haver:

- Muitos pacientes sem AVC;
- Poucos pacientes com AVC.

Isso pode fazer com que o algoritmo tenha dificuldade em aprender a classe minoritária.

### Estratégias

Entre as técnicas identificadas nas fontes está o:

**Random Under-sampling (RUS)**

A técnica reduz a quantidade de exemplos da classe majoritária para equilibrar melhor a distribuição utilizada no treinamento.

Outras técnicas conhecidas incluem:

- SMOTE;
- SMOTETomek;
- Random Over-sampling;
- Class weights.

---

# Capítulo 6 — Ensemble Learning

Ensemble Learning consiste na combinação de múltiplos modelos para produzir uma previsão mais robusta.

## Bagging

Os modelos são treinados de maneira independente e suas previsões são combinadas.

### Random Forest

Random Forest é um dos principais exemplos de Bagging.

Ele utiliza várias árvores de decisão para produzir uma previsão final.

Entre suas vantagens estão:

- Redução do overfitting;
- Capacidade de capturar relações não lineares;
- Boa performance em dados estruturados.

---

## Boosting

No Boosting, os modelos são construídos sequencialmente.

Cada novo modelo procura corrigir erros cometidos pelos anteriores.

Exemplos:

- Gradient Boosting;
- XGBoost;
- CatBoost;
- AdaBoost.

---

## Stacking

Stacking combina diferentes modelos e utiliza um modelo adicional, chamado de meta-modelo, para produzir a previsão final.

---

## Voting

Voting combina as previsões de diferentes modelos.

Pode ser:

- Hard Voting;
- Soft Voting.

No Hard Voting, a decisão ocorre pela maioria dos votos.

No Soft Voting, as probabilidades produzidas pelos modelos podem ser combinadas.

---

# Capítulo 7 — Machine Learning na Previsão de AVC

A previsão de AVC é uma aplicação relevante de Machine Learning na saúde.

Entre as variáveis identificadas nas fontes estão:

- Idade;
- Hipertensão;
- Doença cardíaca;
- Glicose média;
- IMC;
- Status de fumante;
- Gênero.

Alguns estudos também discutem outras características, dependendo do dataset utilizado.

O conjunto de variáveis não é universal.

Ele depende da:

- População estudada;
- Disponibilidade dos dados;
- Metodologia;
- Definição do desfecho;
- Qualidade do dataset.

No estudo específico analisado, o Random Forest apresentou aproximadamente 90% nas métricas reportadas.

Esse resultado deve ser interpretado dentro do contexto daquele estudo.

---

# Capítulo 8 — Validação e Generalização

Um modelo pode apresentar excelente desempenho durante o treinamento e ainda assim falhar quando aplicado a novos pacientes.

Por isso, é necessário avaliar sua capacidade de generalização.

## Train-test split

Uma abordagem comum é dividir os dados em conjuntos de treinamento e teste.

Um exemplo é:

- 80% → treinamento;
- 20% → teste.

## Cross-validation

A validação cruzada divide os dados em diferentes subconjuntos para realizar múltiplos treinamentos e avaliações.

Um exemplo é o:

**5-fold cross-validation.**

## Validação externa

Consiste em testar o modelo utilizando dados independentes da instituição ou dataset original.

É importante para verificar se o modelo funciona em outras populações.

## Validação prospectiva

Avalia o sistema em condições reais de utilização clínica.

A ausência de validação externa e prospectiva é uma das principais limitações para a implementação de modelos de IA na prática clínica.

---

# Capítulo 9 — Interpretabilidade e XAI

Modelos complexos podem ser difíceis de interpretar.

Essa característica é frequentemente descrita como:

> "Caixa-preta".

A **Explainable Artificial Intelligence (XAI)** busca desenvolver métodos que permitam compreender os fatores que influenciaram uma decisão do modelo.

Na saúde, isso é particularmente importante porque decisões podem afetar diretamente pacientes.

A explicabilidade pode contribuir para:

- Confiança dos profissionais;
- Segurança;
- Auditoria;
- Responsabilização;
- Identificação de erros;
- Aceitação clínica.

---

# Capítulo 10 — Limitações e Desafios

A aplicação de IA na saúde apresenta desafios técnicos, éticos e regulatórios.

## Privacidade

Dados médicos são sensíveis e exigem proteção adequada.

## Viés algorítmico

Se os dados utilizados para treinamento forem pouco representativos, o modelo pode apresentar desempenho desigual entre diferentes grupos.

## Qualidade dos dados

Dados podem ser:

- Incompletos;
- Inconsistentes;
- Ruidosos;
- Fragmentados.

## Generalização

Um modelo treinado em uma população pode não funcionar da mesma maneira em outra.

## Integração clínica

O sistema precisa ser incorporado ao fluxo de trabalho sem gerar excesso de alertas ou aumentar a carga dos profissionais.

## Interpretabilidade

Modelos complexos precisam oferecer mecanismos que permitam compreender suas decisões.

---

# 📕 Glossário

| Conceito | Definição |
|---|---|
| **Inteligência Artificial (IA)** | Área voltada ao desenvolvimento de sistemas capazes de realizar tarefas associadas à inteligência humana. |
| **Machine Learning (ML)** | Subcampo da IA que permite aprender padrões a partir de dados. |
| **Aprendizado Supervisionado** | Aprendizado realizado a partir de dados que possuem resultados conhecidos. |
| **Modelo Preditivo** | Modelo utilizado para estimar resultados futuros. |
| **Classificação** | Problema em que o modelo prevê categorias. |
| **Regressão** | Problema em que o modelo prevê valores numéricos contínuos. |
| **Ensemble Learning** | Combinação de múltiplos modelos para gerar previsões. |
| **Bagging** | Estratégia que combina modelos treinados de forma independente. |
| **Boosting** | Estratégia em que modelos são construídos sequencialmente para corrigir erros. |
| **Random Forest** | Ensemble baseado em múltiplas árvores de decisão. |
| **Gradient Boosting** | Método de Boosting baseado na correção sequencial dos erros. |
| **Stacking** | Combinação de modelos utilizando um meta-modelo. |
| **Recall** | Proporção de positivos reais identificados corretamente. |
| **Precision** | Proporção de previsões positivas que realmente são positivas. |
| **F1-score** | Média harmônica entre Precision e Recall. |
| **Accuracy** | Proporção total de previsões corretas. |
| **Overfitting** | Adaptação excessiva aos dados de treinamento. |
| **Dataset desbalanceado** | Dataset no qual as classes possuem quantidades muito diferentes de exemplos. |
| **RUS** | Random Under-sampling, técnica que reduz a classe majoritária. |
| **XAI** | Inteligência Artificial Explicável. |
| **Validação Externa** | Avaliação utilizando dados independentes do conjunto original. |
| **Generalização** | Capacidade do modelo de funcionar em dados novos. |
| **CDSS** | Sistema de Apoio à Decisão Clínica. |
| **EHR** | Registro Eletrônico de Saúde. |

---

# 📝 Questões de Revisão

## Nível Básico

### 1. Qual é a diferença entre Inteligência Artificial e Machine Learning?

### 2. O que é aprendizado supervisionado?

### 3. O que caracteriza um dataset desbalanceado?

### 4. Qual é a diferença entre classificação e regressão?

### 5. O que é um modelo preditivo?

---

## Nível Intermediário

### 6. Por que a Accuracy pode ser enganosa em um problema de previsão de AVC?

### 7. Qual é a diferença entre Bagging e Boosting?

### 8. Por que o Recall é importante na área da saúde?

### 9. Qual é a diferença entre Train-test Split e Cross-validation?

### 10. O que é Random Under-sampling?

---

## Nível Avançado

### 11. Por que a ausência de validação externa limita a utilização clínica de um modelo?

### 12. Qual é a importância da XAI?

### 13. Por que não é correto afirmar que o Random Forest é universalmente o melhor algoritmo para previsão de AVC?

### 14. Como o viés dos dados pode afetar um sistema de IA médica?

### 15. Existe um algoritmo universalmente superior para aplicações de Machine Learning na saúde?

---

# ✅ Gabarito Comentado

### 1.

Machine Learning é um subcampo da Inteligência Artificial que permite que sistemas aprendam padrões a partir de dados.

### 2.

É o aprendizado realizado utilizando dados de entrada associados a resultados conhecidos.

### 3.

É quando uma classe possui quantidade muito maior de exemplos do que outra.

### 4.

Classificação prevê categorias, enquanto regressão prevê valores numéricos contínuos.

### 5.

É um modelo que utiliza dados disponíveis para estimar resultados futuros ou probabilidades.

### 6.

Porque um modelo pode obter alta Accuracy simplesmente favorecendo a classe majoritária e deixando de identificar a classe minoritária.

### 7.

Bagging treina múltiplos modelos de maneira independente. Boosting constrói modelos sequencialmente, tentando corrigir os erros anteriores.

### 8.

Porque o Recall mede a capacidade de identificar corretamente os casos positivos reais. Em determinadas aplicações médicas, deixar de identificar um paciente de risco pode ter consequências graves.

### 9.

Train-test Split separa os dados em treinamento e teste. Cross-validation realiza múltiplas divisões para avaliar a robustez do modelo e pode auxiliar no ajuste de hiperparâmetros.

### 10.

É uma técnica que reduz aleatoriamente exemplos da classe majoritária para diminuir o desequilíbrio entre as classes.

### 11.

Porque um modelo pode apresentar bom desempenho no dataset original e falhar quando aplicado a outra população, instituição ou contexto.

### 12.

A XAI busca tornar as decisões dos modelos mais compreensíveis, contribuindo para confiança, auditoria e segurança.

### 13.

Porque o desempenho depende do dataset, das características do problema, do pré-processamento, das métricas e da metodologia utilizada.

### 14.

Se os dados de treinamento não forem representativos, o modelo pode reproduzir ou ampliar desigualdades existentes nos dados.

### 15.

Não. As evidências analisadas indicam que diferentes algoritmos podem apresentar melhores resultados dependendo do problema e do dataset.

---

# 🔄 Prompts Reutilizáveis

## 1. Compreensão

> Explique o conceito de [CONCEITO] conforme descrito nas fontes, destacando sua importância para a tomada de decisão clínica e como ele se diferencia de abordagens tradicionais.

## 2. Resumo

> Crie um resumo executivo do estudo de [AUTOR/ANO], focando no problema clínico, tamanho da amostra e principais resultados quantitativos.

## 3. Comparação

> Compare o desempenho dos algoritmos [ALGORITMO A] e [ALGORITMO B] com base nas fontes. Identifique em qual contexto experimental cada um apresentou melhor desempenho.

## 4. Análise crítica

> Analise criticamente as conclusões da fonte [FONTE]. Verifique se os dados apresentados realmente sustentam suas conclusões.

## 5. Metodologia

> Descreva detalhadamente o processo de pré-processamento adotado pela fonte, explicando como os autores trataram dados desbalanceados, ausentes ou ruidosos.

## 6. Algoritmos

> Construa uma análise comparativa dos modelos [LISTA DE MODELOS], apresentando vantagens, limitações e aplicações na área da saúde.

## 7. Métricas

> Explique por que a métrica [MÉTRICA] é adequada para avaliar modelos aplicados a [DOENÇA], considerando os possíveis custos de falsos positivos e falsos negativos.

## 8. Limitações

> Identifique nas fontes as principais limitações técnicas, éticas e regulatórias relacionadas à aplicação de IA na saúde.

## 9. Revisão

> Com base no conteúdo estudado, crie questões de diferentes níveis de dificuldade para testar meu conhecimento.

## 10. Dados desbalanceados

> Explique como o desbalanceamento das classes pode afetar o desempenho de um modelo preditivo e quais estratégias podem ser utilizadas para reduzir esse problema.

## 11. Validação

> Identifique quais tipos de validação foram utilizados no estudo e quais estão ausentes. Explique como isso afeta a generalização do modelo.

## 12. XAI

> Sintetize o que as fontes apresentam sobre Inteligência Artificial Explicável e explique por que a interpretabilidade é importante na medicina.

---

# 💡 Principais Aprendizados

Durante o desenvolvimento do projeto, alguns pontos se destacaram.

### 1. IA não significa necessariamente substituição do profissional

A utilização de IA na saúde pode ocorrer como ferramenta de apoio à decisão, fornecendo informações adicionais para o profissional.

### 2. Machine Learning depende dos dados

A qualidade do modelo está diretamente relacionada à qualidade, quantidade e representatividade dos dados utilizados.

### 3. Accuracy não é suficiente

Em problemas desbalanceados, analisar apenas Accuracy pode produzir conclusões equivocadas.

### 4. Recall possui grande importância

Em determinados cenários clínicos, identificar corretamente os casos positivos é fundamental para reduzir falsos negativos.

### 5. Ensemble Learning pode melhorar o desempenho

Técnicas como Random Forest, Gradient Boosting e Stacking combinam diferentes modelos para produzir previsões mais robustas.

### 6. Não existe um algoritmo universalmente melhor

Um algoritmo pode apresentar excelente desempenho em determinado dataset e desempenho inferior em outro.

### 7. Validação é essencial

Um modelo precisa demonstrar capacidade de generalização para ser considerado confiável.

### 8. XAI é importante na saúde

A explicabilidade pode aumentar a confiança dos profissionais e facilitar a identificação de possíveis erros.

### 9. Desempenho técnico não é suficiente

Para utilizar IA na prática clínica também é necessário considerar:

- Privacidade;
- Segurança;
- Ética;
- Viés;
- Regulamentação;
- Integração ao fluxo clínico.

---

# 📌 Conclusão

A realização deste Caderno Temático permitiu compreender de forma integrada o papel da Inteligência Artificial e do Machine Learning na área da saúde.

O estudo mostrou que modelos preditivos podem ser utilizados para auxiliar na identificação de riscos e apoiar decisões clínicas, incluindo aplicações relacionadas à previsão de AVC.

Entretanto, a utilização de Machine Learning na saúde apresenta desafios que vão além da obtenção de bons resultados quantitativos.

Problemas como **dados desbalanceados, qualidade dos dados, overfitting, falta de validação externa, generalização, viés algorítmico, privacidade e interpretabilidade** precisam ser considerados antes de uma aplicação clínica.

A análise também demonstrou que não existe necessariamente um algoritmo universalmente superior. O desempenho de Random Forest, Gradient Boosting, CatBoost ou outros métodos depende das características do problema, do dataset, do pré-processamento e da metodologia de avaliação.

Outro aprendizado importante foi compreender a diferença entre **desempenho experimental e aplicabilidade clínica**. Um modelo pode apresentar excelentes métricas em um estudo controlado e ainda precisar de validação adicional antes de ser utilizado em diferentes populações ou ambientes hospitalares.

Nesse contexto, o NotebookLM foi utilizado não apenas como ferramenta para obter respostas, mas como instrumento de **pesquisa, comparação, verificação, organização e revisão crítica do conhecimento**.

O projeto também demonstrou a importância da engenharia de prompts para direcionar a Inteligência Artificial e obter respostas mais específicas, verificáveis e úteis para o processo de aprendizagem.

---

# 📚 Referências

## Artigos e trabalhos utilizados

**DEB ROY, Pulock et al. (2025).**  
Machine Learning e aplicações de Inteligência Artificial na saúde.

Disponível em:  
https://www.nature.com/articles/s41598-025-01855-w

---

**MELNYKOVA, et al. (2025).**  
Estudo sobre previsão de AVC utilizando Machine Learning e tratamento de dados desbalanceados.

Disponível em:  
https://www.nature.com/articles/s41598-025-01855-w

---

**MOHAJER-BASTAMI, et al. (2025).**  
Aplicações de Inteligência Artificial e Machine Learning em saúde/neurologia.

Disponível em:  
https://www.scielo.br/j/csp/a/jyhKL6G4dZhcbchMD6bcS8s/?lang=pt

---

**ZHANG, & CHEN.**  
Aplicação de modelos preditivos e Gradient Boosting para análise de risco.

---

**WIKIPEDIA.**  
Artificial Intelligence in Healthcare.

Fonte utilizada de forma complementar para contextualização dos conceitos de IA na saúde.

---

# 🧰 Ferramentas utilizadas

- **NotebookLM** — organização, análise e questionamento das fontes;
- **GitHub** — armazenamento e documentação do projeto;
- **Google Scholar** — busca e seleção inicial de referências;
- **Markdown** — estruturação do documento.

---

# 👩‍💻 Autoria

Projeto desenvolvido como atividade prática da **DIO — Digital Innovation One**.

**Tema:** Machine Learning na Saúde e Previsão de AVC  
**Ferramenta de aprendizagem:** NotebookLM  
**Repositório:** `caderno-tematico-machine-learning-saude`

---

⭐ **Projeto desenvolvido com foco em aprendizagem ativa, pensamento crítico, curadoria de fontes e documentação do processo de pesquisa.**
