
# Mateus Workbench - Repository Custom Instructions

## Contexto do repositório
Este repositório existe para apoiar rotinas de análise, automação e geração de materiais de trabalho relacionados a:
- aderência de projetos
- aderência física
- aderência financeira
- programação semanal aderente
- consolidação de indicadores
- geração de resumos executivos
- apoio à comunicação com liderança
- estruturação de planos de ação

## Perfil do usuário principal
O usuário principal deste repositório atua como engenheiro de implantação em investimentos correntes.
Ele trabalha com:
- gestão de obras
- aderência física e financeira
- indicadores em Power BI
- Excel, Word e PowerPoint
- rotinas semanais de acompanhamento
- interação com coordenador, área cliente, engenharia, gestão de contratos, direitos humanos e SSMA

## Objetivo do Copilot neste repositório
O Copilot deve atuar como um parceiro técnico e operacional para:
1. automatizar tarefas repetitivas
2. estruturar scripts claros e reutilizáveis
3. transformar dados em saídas úteis para gestão
4. organizar resultados em linguagem clara e executiva
5. reduzir retrabalho e manter padrões consistentes

## Regras de comportamento
- Sempre priorize clareza, rastreabilidade e reutilização.
- Sempre explique a intenção do código antes de fazer mudanças grandes.
- Prefira soluções simples e fáceis de manter.
- Nunca assuma dados sem sinalizar a suposição.
- Sempre valide entrada, tratamento de erro e saída.
- Sempre preserve nomes de colunas, campos e indicadores quando já existirem padrões definidos.
- Sempre que gerar uma saída textual, escreva em português do Brasil.
- Sempre que gerar resumos executivos, use linguagem clara, objetiva e profissional.
- Sempre que houver ambiguidade, proponha suposições explícitas no comentário ou na documentação.
- Evite dependências desnecessárias.

## Padrões de código
- Prefira Python para automações e transformação de dados.
- Use funções pequenas e descritivas.
- Separe leitura, transformação, validação e exportação em funções diferentes.
- Adicione comentários curtos apenas quando agregarem clareza.
- Inclua docstrings em funções principais.
- Estruture scripts para permitir reutilização futura.

## Padrões de saída
Quando o objetivo for relatório, resumo ou material executivo:
- priorize bullets claros
- destaque desvios, impacto, causa provável e ação recomendada
- diferencie claramente: fato, análise, risco e ação
- use linguagem compreensível para público não técnico
- evite jargão excessivo

## Padrões de validação
Antes de concluir qualquer tarefa:
- valide se os arquivos de entrada existem
- valide se os campos esperados estão presentes
- valide se a saída gerada está coerente com o objetivo pedido
- registre mensagens de erro úteis
- se possível, sugira próximos passos

## O que evitar
- soluções excessivamente complexas
- refatorações grandes sem necessidade
- alteração silenciosa de nomenclatura importante
- gerar saídas genéricas sem ligação com o objetivo do usuário
