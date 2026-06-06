# Análise de Retenção e Abandono de Clientes em E-commerce

## Projeto de Parceria Semantix

Este projeto foi desenvolvido como parte do Projeto de Parceria Semantix, com o objetivo de aplicar técnicas de análise de dados para investigar fatores relacionados ao abandono de clientes em uma plataforma de e-commerce.

A análise busca identificar padrões de comportamento que possam auxiliar empresas na retenção de clientes, contribuindo para a redução de perdas financeiras e melhoria da experiência do usuário.

---

# Problema

A retenção de clientes é um dos principais desafios enfrentados pelas empresas de comércio eletrônico. A perda de clientes impacta diretamente o faturamento, aumenta os custos de aquisição de novos consumidores e reduz o potencial de crescimento sustentável do negócio.

Diante desse cenário, torna-se fundamental compreender quais fatores estão associados ao abandono da plataforma e quais comportamentos podem indicar risco de perda de clientes.

A análise de dados permite identificar padrões ocultos nos dados de navegação, compras e engajamento dos usuários, possibilitando ações preventivas para melhorar a retenção.

---

# Fonte dos Dados

**Dataset utilizado:**

Ecommerce Customer Behavior Dataset

**Fonte:**

https://www.kaggle.com/datasets/dhairyajeetsingh/ecommerce-customer-behavior-dataset

### Características dos dados

* Dados estruturados
* Aproximadamente 50 mil registros
* Informações demográficas
* Dados de navegação
* Histórico de compras
* Indicadores de engajamento
* Indicador de abandono de clientes

### Método de coleta

Os dados foram obtidos através de download direto da plataforma Kaggle.

---

# Ferramentas Utilizadas

* Python
* PySpark
* SQL
* Google Colab
* Looker Studio
* GitHub

---

# Modelagem e Tratamento dos Dados

Durante a preparação dos dados foram realizadas as seguintes etapas:

### Limpeza dos Dados

* Identificação de valores nulos
* Tratamento de valores ausentes
* Remoção de registros duplicados
* Padronização de campos textuais
* Verificação de inconsistências

### Conversão de Tipos

Foi realizada a conversão de colunas numéricas que estavam armazenadas como texto para os formatos adequados (integer e double), permitindo análises estatísticas e agregações corretas.

### Tratamento de Outliers

Foram identificadas idades inconsistentes, incluindo registros inferiores a 18 anos e superiores a 100 anos. Esses registros foram removidos da análise para garantir maior confiabilidade dos resultados.

### Criação de Variáveis de Negócio

Foram criadas novas variáveis para facilitar a análise:

* Faixa Etária
* Status do Cliente
* Nível de Risco de Abandono

---

# Análise Exploratória dos Dados (EDA)

A análise exploratória permitiu compreender a distribuição dos dados e identificar padrões relacionados ao abandono de clientes.

Foram analisadas variáveis relacionadas a:

* Idade
* Frequência de login
* Tempo de relacionamento
* Uso do aplicativo
* Valor médio dos pedidos
* Valor total do cliente (Lifetime Value)
* Tempo desde a última compra
* Localização geográfica

Além disso, foram calculados indicadores de retenção e abandono para diferentes segmentos de clientes.

---

# Dashboard 

## Link para visualização dos dashboards
https://datastudio.google.com/reporting/1ffba6a8-d363-413e-ba71-8589142cbe5f

O dashboard foi desenvolvido no Looker Studio para apresentar os principais indicadores e insights obtidos durante a análise.

### Principais Indicadores

* Total de Clientes
* Clientes Perdidos
* Taxa de Abandono
* Valor Médio do Cliente
* Valor Médio do Pedido

### Principais Visualizações

* Distribuição dos Clientes
* Taxa de Abandono por Faixa Etária
* Uso Médio do Aplicativo
* Tempo Médio Sem Comprar
* Distribuição Geográfica dos Clientes
* Top Países por Valor Médio do Cliente
* Distribuição por Nível de Risco

---

# Principais Insights

### Taxa de Abandono

A análise identificou uma taxa de abandono de aproximadamente **29,08%**, indicando que quase um terço da base de clientes deixou de utilizar a plataforma.

### Faixa Etária

Clientes entre **18 e 24 anos** apresentaram as maiores taxas de abandono quando comparados aos demais grupos etários.

### Engajamento Digital

Clientes ativos apresentaram maior utilização do aplicativo em relação aos clientes perdidos, sugerindo uma forte relação entre engajamento digital e retenção.

### Frequência de Compra

Clientes que abandonaram a plataforma permaneceram mais tempo sem realizar compras, demonstrando que períodos prolongados de inatividade podem indicar risco de abandono.

### Valor Financeiro

O valor médio dos pedidos e o Lifetime Value apresentaram diferenças moderadas entre clientes ativos e perdidos, indicando que o abandono ocorre em diferentes perfis de clientes.

### Distribuição Geográfica

A análise geográfica permitiu identificar a distribuição dos clientes entre diferentes países, auxiliando na segmentação de estratégias comerciais.

---

# Conclusão

Os resultados demonstram que o abandono de clientes está associado principalmente a fatores comportamentais, como utilização do aplicativo e frequência de compras.

A análise evidenciou a importância do monitoramento contínuo dos indicadores de engajamento e da implementação de estratégias preventivas voltadas para clientes em risco.

### Recomendações

* Criar campanhas de reativação para clientes inativos.
* Desenvolver programas de fidelização.
* Investir na experiência do aplicativo.
* Segmentar clientes por nível de risco.
* Monitorar continuamente indicadores de retenção.

A utilização de análise de dados mostrou-se fundamental para compreender o comportamento dos clientes e apoiar a tomada de decisões estratégicas no contexto do comércio eletrônico.

---

# Autor

**João Cavalcanti Euzébio**

Projeto desenvolvido para o Projeto de Parceria Semantix.
