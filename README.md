# Estudo de Caso: Como uma empresa de bem-estar pode ser inteligente?

Este projeto é o TCC do Programa de Certificação Profissional em Análise de Dados do Google. O objetivo é aplicar o processo completo de análise de dados em um cenário real, utilizando dados de usuários de dispositivos inteligentes da empresa **Bellabeat**, que desenvolve produtos focados na saúde e bem-estar da mulher.

---

## 🧠 Contexto do Projeto

A Bellabeat quer aproveitar os dados de seus produtos para identificar novas oportunidades de crescimento. Assumindo o papel de analista de dados, fui encarregado de explorar um conjunto de dados de rastreadores de saúde e gerar **insights** que possam orientar futuras decisões de **marketing** da empresa.

---

## 🔄 Etapas do Processo de Análise de Dados

### 1. **Perguntar** ❓
- **Qual problema estou tentando resolver?**  
  Como os usuários interagem com seus dispositivos de saúde e como a Bellabeat pode usar esses dados para aumentar sua base de clientes e engajamento?

- **Objetivo de negócio:**  
  Descobrir padrões de uso entre os consumidores para **identificar tendências de comportamento**, melhorar a **estratégia de marketing** e aumentar a retenção de clientes.

---

### 2. **Preparar** 🧾
- **Fonte dos dados:**  
  [FitBit Fitness Tracker Data (Kaggle)](https://www.kaggle.com/datasets/arashnic/fitbit)  
  Dataset público com dados de rastreadores de saúde anônimos de 30 usuários durante 31 dias.
  Pode ser encontrado no Kaggle.

- **Formato e Ferramentas:**  
  Arquivos CSV tratados com **R**, **tidyverse**, **RStudio**, e visualizações em **Tableau Public**.
  Todas as ferramentas listadas acima foram aprendidas no curso da Google.

---

### 3. **Processar** 🧹
- Verificação de valores ausentes e duplicados  
- Padronização de nomes de colunas  
- Conversão de tipos de dados (datas, horas, etc.)  
- Filtragem de usuários com dados insuficientes  
- Unificação de datasets com `merge()`

---

### 4. **Analisar** 📈
Principais perguntas respondidas:
- Quantos minutos de atividade física por dia os usuários praticam?
- Há correlação entre calorias gastas e tempo ativo?
- Quantas calorias usuários gastam em média?
- Como está o nível de engajamento com o app (registro de sono, passos, etc)?

Ferramentas:
- Análise exploratória com `ggplot2`
- Estatísticas descritivas: média, mediana, desvio padrão
- Gráficos: barras, dispersão, boxplots

---

### 5. **Compartilhar** 📊
- As Visualizações foram criadas utilizando o Tableau:  
  [🔗 Link para o Dashboard no Tableau Public](https://public.tableau.com/app/profile/SEU_USUARIO)

- Principais Gráficos:
  - Média de calorias queimadas por tipo de atividade
  - Distribuição de minutos ativos vs calorias
  - Correlação entre passos diários e gasto calórico
  - Comparativo de usuários que registram sono x não registram

---

### 6. **Agir** ✅
**Insights:**
- Usuários que registram o sono e atividade física têm padrões mais consistentes de uso → **incentivar o uso contínuo via notificações e gamificação**
- Calorias queimadas estão altamente correlacionadas ao número de passos → **foco em metas de caminhada**
- Apenas parte dos usuários utiliza todos os recursos → **campanhas de onboarding e tutoriais personalizados**

**Ações sugeridas para a empresa:**
- Investir em campanhas educativas sobre o uso do app e dispositivos
- Aumentar o engajamento do app com desafios diários ou semanais.
- Usar os dados de sono e passos como gatilhos para alarmes e notificações para os usuários

---

## 🧰 Ferramentas Utilizadas     

| R / RStudio    | Limpeza e análise dos dados          |
| tidyverse      | Manipulação e transformação de dados |
| ggplot2        | Gráficos e visualizações             |
| Tableau Public | Dashboard interativo final           |
| GitHub         | Hospedagem do projeto e documentação |

---

## 📝 Créditos e Fontes

- Dataset: [FitBit Fitness Tracker Dataset - Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)
- Estudo de Caso original: Google Data Analytics Professional Certificate

---

## 📬 Contato

Guilherme Venturini de Castro  
[LinkedIn](https://www.linkedin.com/in/guilherme-venturini-castro/)  
[GitHub](https://github.com/gvc2010)

