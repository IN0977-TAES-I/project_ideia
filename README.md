
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

# Referências de Tecnologias
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
 # Conjunto de Dados
