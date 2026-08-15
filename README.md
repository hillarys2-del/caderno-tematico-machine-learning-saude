# 🧠 Caderno Temático: Machine Learning na Saúde e Previsão de AVC

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um Desafio de Projeto da [DIO](https://www.dio.me/), utilizando o **NotebookLM** como ferramenta de aprendizagem ativa para pesquisa, análise crítica, organização e consolidação do conhecimento.

O tema escolhido foi a aplicação de **Inteligência Artificial (IA) e Machine Learning (ML) na área da saúde**, com foco em:

- Modelos preditivos;
- Aplicações de Machine Learning na saúde;
- Previsão de Acidente Vascular Cerebral (AVC);
- Ensemble Learning;
- Random Forest;
- Tratamento de dados desbalanceados;
- Métricas de avaliação;
- Validação e generalização;
- Inteligência Artificial Explicável (XAI);
- Limitações e desafios da aplicação clínica de IA.

O projeto também busca demonstrar que o uso de IA como ferramenta de aprendizagem não deve se limitar à obtenção de respostas. É necessário **questionar, verificar, comparar, contextualizar e corrigir as informações obtidas**.

---

# 🎯 Objetivos

### Objetivo geral

Compreender como técnicas de Inteligência Artificial e Machine Learning podem ser aplicadas à área da saúde, com ênfase em modelos preditivos e na previsão de AVC.

### Objetivos específicos

- Compreender os fundamentos de IA aplicada à saúde;
- Estudar os conceitos fundamentais de Machine Learning;
- Compreender modelos preditivos aplicados à saúde;
- Analisar aplicações de ML na previsão de AVC;
- Compreender o funcionamento de Ensemble Learning;
- Estudar algoritmos como Random Forest, Gradient Boosting, XGBoost, CatBoost, AdaBoost e Stacking;
- Investigar o problema de dados desbalanceados;
- Compreender técnicas de balanceamento, como Random Under-sampling;
- Comparar métricas de avaliação, como Accuracy, Precision, Recall e F1-score;
- Compreender técnicas de validação e generalização;
- Estudar a importância da validação externa e prospectiva;
- Compreender o conceito de Inteligência Artificial Explicável (XAI);
- Identificar limitações e desafios para aplicação clínica;
- Utilizar o NotebookLM como ferramenta de aprendizagem ativa;
- Desenvolver pensamento crítico na análise de respostas produzidas por Inteligência Artificial;
- Relacionar os conhecimentos estudados com aplicações práticas de Machine Learning para previsão de AVC.

---

# 📚 1. Curadoria de Fontes

Foram selecionadas cinco fontes principais para construção do caderno temático. Os materiais foram inseridos no NotebookLM para que pudessem ser analisados de forma conjunta.

A seleção buscou contemplar diferentes perspectivas sobre IA na saúde, modelos preditivos, Machine Learning, neurologia, previsão de AVC e desafios de aplicação.

## 1.1 Pulock Deb Roy et al. (2025)

Trabalho relacionado às aplicações de Inteligência Artificial e Machine Learning na área da saúde.

A fonte foi utilizada principalmente para estudar:

- aplicações de IA na saúde;
- Machine Learning;
- modelos preditivos;
- aprendizado supervisionado;
- aplicações clínicas;
- desafios relacionados à utilização de IA.

**Fonte:**

https://www.nature.com/articles/s41598-025-01855-w

---

## 1.2 Melnykova et al. (2025)

Estudo relacionado à aplicação de Machine Learning na **previsão de AVC**, com atenção especial ao problema de **dados desbalanceados** e à avaliação de diferentes algoritmos.

A fonte foi utilizada para estudar:

- previsão de AVC;
- variáveis preditoras;
- Random Forest;
- Ensemble Learning;
- dados desbalanceados;
- Random Under-sampling;
- métricas de avaliação.

**Fonte:**

https://www.scielo.br/j/csp/a/jyhKL6G4dZhcbchMD6bcS8s/?lang=pt

---

## 1.3 Mohajer-Bastami et al. (2025)

Trabalho relacionado à aplicação de Inteligência Artificial e Machine Learning na área de neurologia.

A fonte contribuiu principalmente para a compreensão de:

- aplicações de IA em neurologia;
- modelos preditivos;
- aplicações clínicas;
- limitações dos modelos;
- desafios para utilização de IA em contextos médicos.

**Fonte:**

https://seer.unisc.br/index.php/jovenspesquisadores/article/view/20339

---

## 1.4 Zhang & Chen

Estudo relacionado à utilização de Machine Learning para previsão de risco de hospitalização.

A fonte foi utilizada principalmente para compreender:

- Gradient Boosting;
- modelos preditivos;
- importância de características;
- validação;
- generalização;
- aplicação de Machine Learning em dados de saúde.

É importante destacar que os resultados dessa fonte relacionados à importância das variáveis pertencem ao **contexto específico do estudo de hospitalização** e não devem ser automaticamente generalizados para modelos de previsão de AVC.

**Fonte:**

https://teses.usp.br/teses/disponiveis/6/6141/tde-05022024-163230/en.html

---

## 1.5 Artificial Intelligence in Healthcare — Wikipedia

Fonte utilizada como material complementar para contextualização geral sobre Inteligência Artificial aplicada à saúde.

Foi utilizada principalmente para auxiliar na compreensão introdutória de:

- Inteligência Artificial;
- aplicações médicas;
- Machine Learning;
- modelos preditivos;
- sistemas de apoio à decisão.

**Fonte:**

https://en.wikipedia.org/wiki/Artificial_intelligence_in_healthcare

---

> **Observação:** As fontes foram utilizadas como corpus de estudo no NotebookLM. Resultados quantitativos foram mantidos dentro do contexto específico em que foram apresentados, evitando generalizações indevidas entre estudos com diferentes objetivos, datasets e metodologias.

---

# 🗺️ 2. Mapeamento dos Temas

Após a inserção das fontes no NotebookLM, foi utilizado um primeiro prompt para identificar os principais conceitos e temas recorrentes.

### Prompt utilizado

> **"Mapeie os principais conceitos e temas recorrentes nas fontes fornecidas sobre Inteligência Artificial na saúde, Machine Learning, modelos preditivos, previsão de AVC, Ensemble Learning, limitações e desafios. Organize os temas em uma sequência lógica, partindo dos conceitos introdutórios até os mais avançados."**

A análise permitiu organizar o conhecimento em diferentes níveis.

---

## 2.1 Nível introdutório — Fundamentos

- Inteligência Artificial na saúde;
- Machine Learning;
- Aprendizado supervisionado;
- Aprendizado não supervisionado;
- Sistemas de Apoio à Decisão Clínica (CDSS).

---

## 2.2 Nível intermediário — Modelos e aplicações

- Modelos preditivos;
- Classificação;
- Regressão;
- Registros Eletrônicos de Saúde;
- Predição de doenças;
- Estratificação de risco.

---

## 2.3 Nível avançado — Previsão de AVC

- Variáveis preditoras;
- Dados desbalanceados;
- Random Under-sampling;
- Métricas de avaliação;
- Random Forest;
- Ensemble Learning.

---

## 2.4 Nível avançado — Otimização e generalização

- Bagging;
- Boosting;
- Gradient Boosting;
- XGBoost;
- CatBoost;
- AdaBoost;
- Stacking;
- Validação cruzada;
- Validação externa;
- Validação prospectiva;
- Generalização.

---

## 2.5 Aplicação clínica

- Interpretabilidade;
- Inteligência Artificial Explicável (XAI);
- Viés algorítmico;
- Privacidade;
- Integração ao fluxo de trabalho;
- Fadiga de alertas;
- Segurança do paciente.

---

# 🔬 3. Engenharia de Prompts

O NotebookLM foi utilizado de forma **iterativa**, e não apenas como uma ferramenta para gerar um resumo automático.

O processo foi dividido em etapas:

Fontes
   ↓
Mapeamento
   ↓
Análise
   ↓
Auditoria
   ↓
Comparação
   ↓
Correção
   ↓
Síntese
   ↓
Miniguia
