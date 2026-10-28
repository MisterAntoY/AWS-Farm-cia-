# Graph Report - AWS-Farm-cia-  (2026-10-28)

## Corpus Check
- 2 files · ~1,282 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 44 nodes · 42 edges · 8 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `0e7be4db`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- 123.md
- Etapa 2
- README.md
- Etapa 1
- Etapa 1
- Etapa 3
- Etapa 2
- Etapa 3

## God Nodes (most connected - your core abstractions)
1. `Etapa 1` - 5 edges
2. `Etapa 2` - 5 edges
3. `Etapa 3` - 5 edges
4. `Etapa 1` - 5 edges
5. `Etapa 2` - 5 edges
6. `Etapa 3` - 5 edges
7. `Descrição do Projeto` - 4 edges
8. `Descrição do Projeto` - 4 edges
9. `RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS` - 1 edges
10. `Introdução` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Communities (8 total, 0 thin omitted)

### Community 0 - "123.md"
Cohesion: 0.33
Nodes (5): Anexos, Assinatura do Responsável pelo Projeto, Conclusão, Introdução, RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

### Community 1 - "Etapa 2"
Cohesion: 0.33
Nodes (6): Benefícios obtidos:, Descrição do caso de uso:, Descrição do Projeto, Etapa 2, Foco da ferramenta:, Serviço AWS:

### Community 2 - "README.md"
Cohesion: 0.33
Nodes (5): Anexos, Assinatura do Responsável pelo Projeto, Conclusão, Introdução, RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

### Community 3 - "Etapa 1"
Cohesion: 0.33
Nodes (6): Benefícios obtidos:, Descrição do caso de uso:, Descrição do Projeto, Etapa 1, Foco da ferramenta:, Serviço AWS:

### Community 4 - "Etapa 1"
Cohesion: 0.40
Nodes (5): Benefícios obtidos:, Descrição do caso de uso:, Etapa 1, Foco da ferramenta:, Serviço AWS:

### Community 5 - "Etapa 3"
Cohesion: 0.40
Nodes (5): Benefícios obtidos:, Descrição do caso de uso:, Etapa 3, Foco da ferramenta:, Serviço AWS:

### Community 6 - "Etapa 2"
Cohesion: 0.40
Nodes (5): Benefícios obtidos:, Descrição do caso de uso:, Etapa 2, Foco da ferramenta:, Serviço AWS:

### Community 7 - "Etapa 3"
Cohesion: 0.40
Nodes (5): Benefícios obtidos:, Descrição do caso de uso:, Etapa 3, Foco da ferramenta:, Serviço AWS:

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Descrição do Projeto` connect `Etapa 2` to `123.md`, `Etapa 1`, `Etapa 3`?**
  _High betweenness centrality (0.183) - this node is a cross-community bridge._
- **Why does `Descrição do Projeto` connect `Etapa 1` to `README.md`, `Etapa 2`, `Etapa 3`?**
  _High betweenness centrality (0.183) - this node is a cross-community bridge._
- **Why does `Etapa 1` connect `Etapa 1` to `Etapa 2`?**
  _High betweenness centrality (0.082) - this node is a cross-community bridge._