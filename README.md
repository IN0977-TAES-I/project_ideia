
# Replicação
# PR Reviewer
  - Limitação
    - Expandir para outras linguagens
    - Deteção de interferência semântica
    - Visualidzação de Dependência
    - Verificar o código da API do Github
    - Adicionar camada de contexto

  - Abordagem
    - Incluir repo de Meta sobre contexto
    - 

# Uso de LLM - Caso Nathalia
  - Limitação
    - Geração de código com LLM
    - Incluir-as-Judge
    - Avaliação de Variações novas estratégias de prompts
    - Avaliação de Variações novos modelos
  
  - Abordagem
    - Incluir camada de avaliador


# Formulação do Problema
- Qual outra abordagem diferente da técnicas e métodos SOTA para deteção de conflito semâtico no merge?

# Propostas
- Q1. Introdução de nova camada de Avalidador como Juiz, eficiente e rápido é melhor do que as soluções propostas
- Q2. Inclusão de análise de contexto usando MLC  melhora, piorar ou indiferente, na deteção de conflito semântico?
- Q3. Uso de raciocínio em LLM, contribuiu, na deteção de conflito semântico:
  - Como identificar o movimento de mudanças do código para atencipar conflito
    
 # Conjunto de Dados
- [Ad-Hoc Java Merge Scenaries Dataset]()
- [Merge Dataset](https://github.com/spgroup/mergedataset/tree/master)

# Hands-on
## JEV
- [Build your own Jev (100% local)](https://x.com/_avichawla/status/2101563610644496464)
- [JEV-vs-LLM-Judge](https://x.com/akshay_pachaar/status/2103120680485282009?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E2103120680485282009%7Ctwgr%5E%7Ctwcon%5Es1_c10&ref_url=)
- [JEV Enginnerign for Coding Agents](https://x.com/Mr_Buzzoni/status/2106261967975391339?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E2106261967975391339%7Ctwgr%5E%7Ctwcon%5Es1_c10&ref_url=)
- [JEV OPUS 5.5 ](https://x.com/0x_rody/status/2106029798531186719?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E2106029798531186719%7Ctwgr%5E%7Ctwcon%5Es1_c10&ref_url=)
- [Agentica Patterns with JEV](https://x.com/Mr_Buzzoni/status/2105904864614363605?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E2105904864614363605%7Ctwgr%5E%7Ctwcon%5Es1_c10&ref_url=)
- [RAG + JEV](https://x.com/akshay_pachaar/status/2105281570898849903?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E2105281570898849903%7Ctwgr%5E%7Ctwcon%5Es1_c10&ref_url=)
  
# Repositórios
  - Avaliador de LLM
    - JEV https://arxiv.org/abs/2609.29769
      - [JEV vs. LLMs as Rubric Judges: Cheaper, Faster, and Wrong in the Same Places](https://arxiv.org/abs/2609.29769)
      - [KEV](https://github.com/jaredpalmer/kev) 
    - [Cloudfare clef](https://huggingface.co/Cloudflare/clef)
  - Avaliador do Especialista
    - [Ponytail](https://github.com/dietrichgebert/ponytail)
  - Anaĺise Temporal com Agente
    -[Skill-Temporal-Developer](https://github.com/temporalio/skill-temporal-developer)
  - Context
    - Context Language Models Article
    - [Context Language Models](https://github.com/facebookresearch/context-language-models)
  - Conteinerization
    - [AI Docker Image Optimization](https://github.com/dti-reitoria-ifpe/ai-docker-image-optimization)
  - Reasoning
    - Como identificar o movimento de mudanças do código para atencipar conflito 
  - Visualization
    - [Oil-Git](https://oil-oil.github.io/oil-git/)
    - [Architecture Diagram Generator](https://github.com/Cocoon-AI/architecture-diagram-generator)


# Articles
## JEV
- [Comparing Static Analyses for Improved Semantic Conflict Detection](https://spgroup.github.io/papers/interference-static-analyses-comparison.html)
   
## Análise Estática para deteção de conflito semântico
- [Comparing Static Analyses for Improved Semantic Conflict Detection](https://spgroup.github.io/papers/interference-static-analyses-comparison.html)
- [The Impact of Static Analysis Depth Limit on Semantic Conflict Detection(https://cbsoft.sbc.org.br/2026/data/papers/sbes/The%20Impact%20of%20Static%20Analysis%20Depth%20Limit%20on%20Semantic%20Conflict%20Detection.pdf)
- [Refilter]()
## LLM
- [SMAT]()
- [MergeGen]()
