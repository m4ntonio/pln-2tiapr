# PLN — Processamento de Linguagem Natural, Chatbots & Agentes Virtuais
**Turma:** 2TIAPR — FIAP (2026/2027)  
**Projeto:** Agente de Voz Rodoviário para o Challenge Motiva  

## Integrantes do Grupo
- **Mario Antonio Oliveira** (RM: 567713)
- **Vinicius Augusto Silva** (RM: 566830)

---

## Estrutura do Repositório

```
pln-2tiapr/
│
├── sprint1-pln/                               # Entrega Oficial da Sprint 1
│   ├── sprint1_pln_motiva.ipynb               # Notebook executável com pipeline NLU e baseline
│   ├── corpus_enunciacoes.json                # 60 enunciações anotadas (Cohen's Kappa = 0,9121)
│   ├── taxonomia_intencoes.json               # Mapeamento 100% das 40 User Stories em 27 intenções
│   ├── glossario_rodoviario.json              # Dicionário de jargões rodoviários e correções ASR
│   ├── DECISOES_DESIGN.md                     # Documento técnico detalhado de decisões e métricas
│   ├── USO_DE_IA.md                           # Declaração formal de uso ético e transparente de IA
│   └── integrantes.txt                        # Identificação formal dos integrantes da equipe
│
└── README.md                                  # Apresentação do repositório
```

---

## Sprint 1 — Fundamentar: A Linguagem da Operação Rodoviária

### Resumo dos Resultados Técnicos e Conformidade (Rubrica 100 Pontos)
- **Cobertura da Taxonomia:** 100% das 40 User Stories da Motiva mapeadas em 27 intenções canônicas com 9 entidades operacionais.
- **Corpus Anotado:** 60 enunciações com dupla anotação independente (`a1` e `a2`) atingindo **Cohen's Kappa de 0,9121** (superando o Gate de Passagem $\ge 0,70$).
- **Pipeline de Normalização Numérica:** Taxa de conversão de números e frações por extenso de **93.8%** (patamar exigido: $\ge 90\%$).
- **Baseline de NLU:** Acurácia global de **85.0%** no classificador por palavras-chave com extração determinística por Regex.
- **Contrato de Saída:** 100% dos 60 registros validados estritamente contra o JSON Schema oficial.
