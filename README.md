# OTIF Dashboard

Dashboard Power BI para métricas **OTIF (On-Time In-Full)** — indicadores de entregas no prazo e completude para análise executiva e operacional.

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data_Analysis-FF6B35?style=for-the-badge)](https://docs.microsoft.com/power-bi/)

---

## Visão Geral

O **OTIF Dashboard** é um conjunto de relatórios Power BI (Microsoft Fabric) desenvolvidos para visualizar e analisar indicadores de **On-Time In-Full** — métricas críticas para operações de supply chain e logística que avaliam:

- **On-Time**: Entregas realizadas dentro do prazo acordado
- **In-Full**: Entregas com quantidade completa conforme pedido

### Características

- **Relatório Executivo**: Visão consolidada com tema customizado (OTIF-Executive)
- **Modelo Semântico**: Estrutura de dados otimizada para análise
- **Censo Brasil**: Módulo adicional com dados demográficos e geográficos
- **Visuals Customizados**: Mapas geográficos e filtros avançados
- **Temas e Estilização**: Temas dark (Censo-Dark) e executivo

---

## Estrutura do Projeto

```
OTIFDashboard/
├── OTIFDashboard.Report/        # Relatório principal Power BI
│   ├── definition/              # Definições JSON do relatório
│   └── StaticResources/         # Temas e recursos visuais
├── OTIFDashboard.SemanticModel/ # Modelo de dados (semantic model)
├── CensoBrasil/                 # Módulo Censo Brasil
│   ├── CensoBrasil.Report/
│   └── CensoBrasil.SemanticModel/
├── .cursorrules                 # Regras de desenvolvimento
└── README.md
```

---

## Tecnologias

- **Power BI / Microsoft Fabric**: Relatórios e modelos semânticos
- **DAX**: Cálculos e métricas
- **JSON**: Definições de report (schema Fabric 3.1.0)
- **Visuals**: geoportalMap, textFilter e padrão Power BI

---

## Pré-requisitos

- **Power BI Desktop** ou **Microsoft Fabric** (Power BI Service)
- Acesso às fontes de dados configuradas no modelo semântico

---

## Uso

1. Abra o projeto no **Power BI Desktop** ou importe no **Fabric**
2. Conecte às fontes de dados necessárias
3. Atualize o modelo e publique no workspace desejado
4. Configure o refresh agendado conforme a necessidade do negócio

---

## Licença

Projeto proprietário. Uso interno.
