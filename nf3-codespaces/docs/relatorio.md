# Relatório NF3
Equipe e contribuições: Thiago Cruzeiro e Daniel
Data, versão MySQL e commit:


## Respostas



**Tarefa:** desenhe o esquema lógico, com PK/FK, cardinalidades e participação. Proponha uma estratégia transacional para validar totalidade/disjunção; discuta concorrência e como impedir que duas sessões criem subtipos incompatíveis. FKs preservam existência do supertipo, não a regra “um ou outro”. Explique também por que pedido CONCLUIDO com ao menos um item exige validação além da FK ITEM→PEDIDO.


## Modelagem e normalização
Cardinalidades, chaves, dependências, formas normais e limitações das FKs.

## Consultas
SQL próprio, resultado esperado, resultado observado, interpretação.

## Administração
Plano antes/depois do índice; custo de escrita; view e trigger; permissões.

## Transações
| Cenário | Ordem A/B | Resultado observado | Causa | Correção |
|---|---|---|---|---|
| Leitura suja | | | | |
| Não repetível | | | | |
| Fantasma | | | | |
| Atualização perdida | | | | |
| Bloqueio | | | | |
| Deadlock | | | | |

## Recuperação
Arquivo, checksum, base restaurada, comparação de conteúdo e tempo medido.

## Modelos e distribuição
Partição x réplica; desatualização; objetos persistentes; JSON, chave-valor e grafos.

## Limitações e autoria
Separe medição, simulação e proposta. Não anexar senhas ou .env.
