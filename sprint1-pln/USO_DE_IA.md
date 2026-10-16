# DECLARAÇÃO DE USO DE INTELIGÊNCIA ARTIFICIAL (USO_DE_IA.md)

**Disciplina:** Processamento de Linguagem Natural, Chatbots & Agentes Virtuais  
**Atividade:** Sprint 1 — Fundamentar: a linguagem da operação rodoviária  
**Projeto:** Challenge Motiva / FIAP (2026/2027)  
**Autores:**  
- Leonardo Melo [RM: 567097]
- Luna Rousseau Nogueira de Oliveira [RM: 564215]
- Mario Antonio Oliveira [RM: 567713]  
- Vinicius Augusto Silva [RM: 566830]  

---

## 1. Princípios Éticos e Transparência

Em conformidade com as diretrizes acadêmicas da FIAP e as instruções operacionais da disciplina, os integrantes declaram o uso assistido de ferramentas de Inteligência Artificial Generativa durante o desenvolvimento desta Sprint 1.

O papel da IA no projeto restringiu-se ao **apoio técnico, aceleração de código boiler-plate e suporte à estruturação sintática**, cabendo integralmente aos autores humanos o julgamento crítico, a definição da arquitetura de NLU, a modelagem das intenções, a revisão semântica das enunciações e a auditoria matemática das métricas geradas.

---

## 2. Ferramentas e Modelos Utilizados

| Ferramenta / Modelo | Provedor | Finalidade Específica |
| :--- | :--- | :--- |
| **Antigravity AI (Google DeepMind)** | Google | Auxílio na redação de expressões regulares complexas para normalização de números por extenso e estruturação do layout do notebook no Google Colab. |
| **OpenAI Whisper (Small)** | OpenAI | Modelo de ASR de código aberto utilizado como referência conceitual para caracterização dos padrões de erro acústico e transcrição fonética em português sob ruído rodoviário. |

---

## 3. Escopo de Utilização e Intervenção Humana

### 3.1 Onde a IA foi utilizada
1. **Expressões Regulares para Normalização Numérica:** Apoio na síntese de padrões regex em Python para captura de dezenas, centenas e frações (*"cento e vinte e três e meio"* $\rightarrow$ `123.5`).
2. **Template do Notebook e Scripts de Validação:** Estruturação das células do Jupyter Notebook executável e funções utilitárias para verificação de esquemas JSON.
3. **Revisão Gramatical e Formatação Técnica:** Padronização visual dos relatórios em Markdown e diagramas estruturados em formato Mermaid.

### 3.2 O que foi concebido e validado exclusivamente pelos Autores Humanos
1. **Taxonomia Canônica e Mapeamento das 40 User Stories:** Análise manual e qualitativa das 40 histórias de usuário do documento original da Motiva, agrupando ações equivalentes e estabelecendo criticidade e governança de confirmação.
2. **Esquema das 9 Entidades Operacionais:** Definição das tipagens de dados, vocabulário controlado de valores canônicos e padrões operacionais de rodovia.
3. **Curadoria do Corpus e Dupla Anotação:** Criação do contexto operacional das 60 enunciações distribuídas entre as 5 personas, anotação manual independente entre os dois integrantes (`a1` e `a2`), identificação e documentação qualitativa dos 5 casos de discordância.
4. **Validação do Gate de Passagem:** Verificação matemática do índice Cohen's Kappa ($0,9121 \ge 0,70$) e garantia de 100% de conformidade com o schema `corpus_enunciacoes.json`.
5. **Auditoria e Execução:** Execução de ponta a ponta do pipeline no Google Colab (GPU T4) com teste de cada bloco de código.

---

## 4. Declaração de Autoria e Responsabilidade

Os autores declaram que compreenderam a totalidade dos algoritmos, dados e regras documentados neste repositório. Nenhum componente deste projeto foi incorporado de forma automatizada sem a devida compreensão, validação e teste pelos integrantes responsáveis.

