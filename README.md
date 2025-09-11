# Engenharia de Dados - Processando e Analisando Notas Fiscais (GOV BR)

**Demonstração simples e sofisticada de habilidades em engenharia de dados**

Esse foi um trabalho realizado esse mês (set/2025), recebi a demanda para extração de informações de notas ficais para comparativos de analise de preço. Somos responsavei por gerar preços com muita tecnica e estatistica envolvidos, e acompanhar o desenvolvimento dos mercados.

Nesse trabalho foi realizado a coleta de notas por meio de fotos ou arquivos pdfs, todos em formatos prorpios da empresa que emite essas notas. Eu tive a responsabilidade de fazer todo o processo de ETL e uma analise final dos resultados para a alta gestão.

OS METODOS AQUI SÃO OS MESMO USADOS NO MEU DIA A DIA DO TRABALHO, MAS OS DADOS SÃO ALTERADOS, PARA PROTEÇÃO E INTEGRIDADE DAS INFORMAÇÕES, SEGUINDO A LGPD (LEI GERAL DE PROTEÇÃO DE DADOS)

Uma solução clean e profissional que demonstra capacidades avançadas em processamento de imagens e texto usando tecnologias open source.

---
 
<div align="center">
 
**Made with ☕ by [Isabel Cruz](https://github.com/bellDataSc)**
 
[![GitHub followers](https://img.shields.io/github/followers/bellDataSc?style=social)](https://github.com/bellDataSc)
[![GitHub stars](https://img.shields.io/github/stars/bellDataSc/Natural-Language-Processing-with-Disaster-Tweets?sty…
 
*"Transforming text data into actionable insights, one tweet at a time"*
 
</div>

## Objetivo

Este repositório foi criado para **demonstrar conhecimentos práticos em engenharia de dados** através de:

- Pipeline de dados end-to-end
- Processamento multimodal (imagem + texto)
- Visualizações interativas
- Código limpo e bem estruturado
- Boas práticas de desenvolvimento

## Quick Start

### 1. Instalação
```bash
pip install -r requirements.txt
```

### 2. Executar Dashboard
```bash
streamlit run simple_streamlit_app.py
```

### 3. Acessar Google Colab
Abra o notebook `Data_Engineering_Showcase.ipynb` no Google Colab para ver a demonstração completa.

## Estrutura do Projeto

```
Data-Engineering-Showcase/
├──  README.md                          
├──  requirements.txt                   
├──  simple_streamlit_app.py           
├──  simple_image_processor.py         
├──  simple_text_processor.py          
├──  Data_Engineering_Showcase.ipynb   
└──  data/                             
```

## Stack Tecnológico

| Tecnologia | Uso | Benefício |
|------------|-----|-----------|
| **Python 3.9+** | Linguagem principal | Versatilidade e ecossistema rico |
| **OpenCV** | Processamento de imagens | Computer vision profissional |
| **YOLO** | Detecção de objetos | State-of-the-art em tempo real |
| **Transformers** | Análise de texto | Modelos de NLP avançados |
| **Streamlit** | Interface web | Dashboard rápido e interativo |
| **Plotly** | Visualizações | Gráficos interativos e profissionais |
| **Pandas** | Manipulação de dados | Análise e transformação eficiente |

## Funcionalidades

### Análise de Imagens
- Avaliação automática de qualidade
- Extração de cores dominantes
- Análise de nitidez, brilho e contraste
- Detecção de características visuais
- Processamento em lote

### Processamento de Texto
- Análise de sentimento avançada
- Extração de palavras-chave
- Métricas de legibilidade
- Detecção de idioma
- Pipeline de limpeza de texto

### Visualizações
- Dashboards interativos
- Gráficos de qualidade e performance
- Análise de distribuições
- Métricas em tempo real

## Demonstração de Habilidades

### Engenharia de Dados
- **Pipeline Design**: Arquitetura modular e escalável
- **ETL Processing**: Extract, Transform, Load eficiente
- **Error Handling**: Tratamento robusto de exceções
- **Logging**: Monitoramento estruturado
- **Caching**: Otimização de performance
- **Batch Processing**: Processamento em lote

### Desenvolvimento de Software
- **Clean Code**: Código limpo e documentado
- **OOP Design**: Orientação a objetos bem estruturada
- **Type Hints**: Código tipado para melhor manutenção
- **Configuration**: Gerenciamento de configurações
- **Testing Ready**: Estrutura preparada para testes

### Data Science & ML
- **Computer Vision**: Processamento avançado de imagens
- **NLP**: Processamento de linguagem natural
- **Feature Engineering**: Extração inteligente de características
- **Data Visualization**: Visualizações profissionais
- **Statistical Analysis**: Análise estatística dos resultados

## Como Usar

### Dashboard Streamlit

1. Execute o dashboard:
```bash
streamlit run simple_streamlit_app.py
```

2. Acesse http://localhost:8501

3. Faça upload de imagens ou insira textos para análise

### Google Colab

1. Abra `Data_Engineering_Showcase.ipynb` no Google Colab

2. Execute as células sequencialmente

3. Veja a demonstração completa do pipeline

### Processamento Programático

```python

from simple_image_processor import SimpleImageProcessor

processor = SimpleImageProcessor()
result = processor.analyze_image("image.jpg")
print(f"Quality Score: {result['quality_metrics']['overall_score']}")

 
from simple_text_processor import SimpleTextProcessor

text_processor = SimpleTextProcessor()
result = text_processor.analyze_text("Your text here")
print(f"Sentiment: {result['sentiment_analysis']['label']}")
```

## Exemplos de Resultados

### Análise de Imagem
```json
{
  "quality_metrics": {
    "overall_score": 87.3,
    "sharpness": 245.6,
    "brightness": 128.4,
    "contrast": 52.1
  },
  "color_analysis": {
    "dominant_colors": [
      {"hex": "#4A90E2", "percentage": 34.2},
      {"hex": "#7ED321", "percentage": 28.7}
    ]
  }
}
```

### Análise de Texto
```json
{
  "sentiment_analysis": {
    "label": "POSITIVE",
    "confidence": 0.894,
    "positive_score": 0.894
  },
  "keyword_extraction": [
    {"word": "technology", "tf_score": 0.045},
    {"word": "innovation", "tf_score": 0.032}
  ],
  "readability_metrics": {
    "flesch_score": 72.4,
    "complexity": 0.267
  }
}
```

## Conceitos Demonstrados

### Data Engineering Patterns
- **Pipeline Pattern**: Processamento sequencial de dados
- **Factory Pattern**: Criação de processadores especializados
- **Observer Pattern**: Logging e monitoramento de eventos
- **Cache Pattern**: Otimização de performance com cache

### Performance Optimization
- **Batch Processing**: Processamento eficiente em lote
- **Lazy Loading**: Carregamento sob demanda
- **Memory Management**: Gestão eficiente de memória
- **Parallel Processing**: Preparado para paralelização

### Error Resilience
- **Graceful Degradation**: Fallbacks inteligentes
- **Exception Handling**: Tratamento abrangente de erros
- **Input Validation**: Validação robusta de entradas
- **Recovery Mechanisms**: Recuperação automática

## Monitoramento e Métricas

O sistema inclui monitoramento abrangente:

- **Processing Stats**: Estatísticas de processamento
- **Success Rates**: Taxa de sucesso das operações
- **Performance Metrics**: Tempo de processamento e throughput
- **Cache Hit Rates**: Eficiência do cache
- **Error Tracking**: Rastreamento de erros


## Próximos Passos

### Possíveis Extensões
- [ ] Adicionar mais tipos de análise
- [ ] Implementar API REST
- [ ] Adicionar testes automatizados
- [ ] Criar pipeline CI/CD
- [ ] Adicionar monitoramento avançado

### Otimizações
- [ ] Processamento paralelo
- [ ] Cache distribuído
- [ ] Otimização de memória
- [ ] Containerização

## Licença

Este projeto é distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Autor
---
 
<div align="center">
 
**Made with ☕ by [Isabel Cruz](https://github.com/bellDataSc)**
 
[![GitHub followers](https://img.shields.io/github/followers/bellDataSc?style=social)](https://github.com/bellDataSc)
[![GitHub stars](https://img.shields.io/github/stars/bellDataSc/Natural-Language-Processing-with-Disaster-Tweets?sty…
 
*"Transforming text data into actionable insights, one tweet at a time"*
 
</div>

