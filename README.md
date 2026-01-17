# Saúde nas Margens: Vigilância e Vulnerabilidade na Amazônia 🌿🏥

![Status do Projeto](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![Instituição](https://img.shields.io/badge/Instituição-ILMD__Fiocruz__Amazônia-blue)
![Linguagem Principal](https://img.shields.io/badge/Linguagem-Python_%7C_R-green)
![Licença](https://img.shields.io/badge/Licença-MIT-lightgrey)

> **Coordenação:** Prof. Dr. Pritesh Lalwani  
> **Instituição:** Instituto Leônidas & Maria Deane (ILMD) - Fiocruz Amazônia

---

## 📌 Sobre o Projeto

O **Saúde nas Margens** é uma iniciativa de pesquisa dedicada a investigar a dinâmica de doenças infecciosas e parasitárias em populações historicamente vulnerabilizadas na região Amazônica (populações indígenas, ribeirinhas e periféricas).

O projeto utiliza abordagens multidisciplinares, combinando **epidemiologia molecular**, **vigilância genômica** e **análise de dados espaciais** para compreender como determinantes sociais e ambientais influenciam a disseminação de patógenos (como Oropouche, Dengue, Malária e outros arbovírus) em áreas de difícil acesso.

### 🔍 Foco da Pesquisa
Este repositório contém os scripts e documentação referentes às análises computacionais do projeto, incluindo:
* Modelagem epidemiológica.
* Análise de bioinformática (alinhamentos, filogenia).
* Processamento de dados georreferenciados.

---

## 🎯 Objetivos

1.  **Mapeamento de Riscos:** Identificar *hotspots* de transmissão de doenças zoonóticas e vetoriais em comunidades marginalizadas.
2.  **Vigilância Genômica:** Monitorar variantes virais circulantes e sua correlação com casos graves ou surtos atípicos.
3.  **Determinantes Sociais:** Correlacionar dados clínicos com indicadores socioeconômicos e ambientais.
4.  **Apoio à Decisão:** Fornecer dados baseados em evidências para fortalecer políticas públicas de saúde na região Norte.

---

## 🛠️ Tecnologias e Ferramentas

O projeto utiliza um fluxo de trabalho híbrido com as seguintes tecnologias:

* **Linguagens:**
    * 🐍 **Python 3.9+:** Processamento de dados (`Pandas`, `NumPy`), Aprendizado de Máquina (`Scikit-learn`) e Bioinformática (`Biopython`).
    * 📊 **R:** Análise estatística robusta e visualização (`ggplot2`, `dplyr`, `sf`).
* **Bioinformática:**
    * MAFFT / ClustalW (Alinhamento)
    * IQ-TREE / MrBayes (Filogenia)
* **Geoprocessamento:**
    * QGIS / GeoPandas (Análise espacial)

---

## 📂 Estrutura do Repositório

```text
├── data/                  # Dados brutos e processados (anonimizados conforme LGPD/Comitê de Ética)
│   ├── raw/               # Dados originais
│   ├── processed/         # Dados limpos prontos para análise
│   └── external/          # Dados externos (IBGE, SINAN, etc.)
├── notebooks/             # Jupyter Notebooks para análise exploratória
├── src/                   # Código fonte dos scripts de análise
│   ├── data_cleaning/     # Scripts de limpeza
│   ├── genomics/          # Pipelines de bioinformática
│   └── visualization/     # Scripts para geração de gráficos e mapas
├── docs/                  # Documentação adicional e dicionários de dados
├── results/               # Figuras, tabelas e relatórios gerados
└── README.md              # Documentação do projeto
