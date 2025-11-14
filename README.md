# Análise de Salários em Ciência de Dados

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1jKwcJK-S3fQj2XoyUur-bAPdxlu8Y5bC?usp=sharing)


## Equipe
- [Gabriel Couto Ribeiro](https://github.com/rouri404)
- [Gabriel Kato Peres](https://github.com/kato8088)
- [João Vitor de Matos Araujo](https://github.com/joaomatosq)

## Visão Geral do Projeto
Este projeto realiza uma análise abrangente sobre os salários na área de Ciência de Dados em diferentes países. O objetivo é entender os fatores que influenciam os salários e fornecer insights valiosos para profissionais e empresas do setor.

## Conjunto de Dados

### Como obter os dados
1. Acesse o link: [Data Science Job Salaries Dataset](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries/data)
2. Faça o download do arquivo `ds_salaries.csv`
3. Coloque o arquivo na raiz do projeto (pasta principal)

### Sobre os dados
O conjunto de dados contém informações sobre salários de profissionais de Ciência de Dados de diferentes países, incluindo:
- Ano de trabalho
- Nível de experiência
- Tipo de emprego
- Cargo
- Salário em USD
- Localização da empresa
- Tamanho da empresa
- Proporção de trabalho remoto

## Principais Descobertas

### 1. Panorama do Mercado de Dados
- O mercado de Data Science apresenta uma grande variação salarial, refletindo diferentes níveis de experiência, localizações e especializações
- A média salarial é de $112,297.87 USD, com uma mediana de $101,570.00 USD
- A faixa salarial varia significativamente, de $2,859 até $600,000 USD anuais

### 2. Fatores Determinantes nos Salários
- **Experiência**: O fator mais impactante, com diferenças significativas entre níveis júnior, pleno, sênior e executivo
- **Cargo e Especialização**: Posições de liderança e especializações técnicas avançadas apresentam os maiores salários
- **Localização Geográfica**: Países com maior custo de vida e maior concentração de empresas de tecnologia oferecem salários mais altos
- **Tipo de Contrato**: Contratos CLT/full-time oferecem maior estabilidade, enquanto trabalhos freelancers podem ter maior variação
- **Tamanho da Empresa**: Grandes empresas geralmente oferecem melhores pacotes salariais e benefícios

### 3. Habilidades Mais Valorizadas
1. **Conhecimento Técnico Avançado**: Domínio de ferramentas e técnicas de análise de dados
2. **Liderança e Gestão**: Habilidades para gerenciar equipes e projetos de dados
3. **Especialização Técnica**: Conhecimento aprofundado em áreas como IA, Machine Learning e Engenharia de Dados
4. **Visão de Negócios**: Capacidade de transformar dados em insights acionáveis

### 4. Qualidade e Confiabilidade dos Dados
- O conjunto de dados está bem estruturado e não contém valores nulos
- Não foram encontradas linhas duplicadas
- Os dados são consistentes e refletem as tendências atuais do mercado

## Metodologia
1. **Pré-processamento**:
   - Carregamento e inspeção inicial dos dados
   - Verificação de valores ausentes e duplicados
   - Análise de estatísticas descritivas

2. **Análise Exploratória**:
   - Distribuição de salários
   - Relação entre variáveis
   - Comparação entre diferentes grupos (países, níveis de experiência, etc.)

3. **Visualização**:
   - Gráficos para melhor compreensão dos padrões salariais
   - Comparações visuais entre diferentes segmentos

## Como Usar

### Configuração Inicial
1. Clone o repositório:
   ```bash
   git clone https://github.com/GrupoMoskitto/DATA-SCIENCE-GS-2025.git
   cd DATA-SCIENCE-GS-2025
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate  # Windows
   ```

3. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```
4. Execute o notebook `gs-data-science.ipynb`# DATA-SCIENCE-GS-2025
