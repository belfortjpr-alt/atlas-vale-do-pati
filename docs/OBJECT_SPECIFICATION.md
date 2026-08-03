# Especificação de Objeto Geográfico

## O que é um Objeto Geográfico

Um Objeto Geográfico é qualquer entidade territorial identificável dentro do Atlas Vale do Pati.

Um objeto pode representar um elemento natural, uma construção, um ponto de referência, uma rota, uma área, uma ocorrência observada ou qualquer elemento espacial relevante para compreender o território.

Um Objeto Geográfico deve existir como unidade conceitual independente de mapas, interfaces, aplicativos ou formatos técnicos. Sua existência no Atlas depende de identidade, contexto, evidências e relações documentadas.

## Tipos de Objetos

Os tipos iniciais de Objetos Geográficos são:

- Rio
- Cachoeira
- Poço
- Trilha
- Waypoint
- Mirante
- Formação Geológica
- Casa de Apoio
- Camping
- Travessia
- Nascente

Essa lista é conceitual e poderá ser ampliada conforme novas necessidades de representação territorial forem identificadas.

## Identidade

Cada Objeto Geográfico possui um identificador permanente e único dentro do Atlas Vale do Pati.

O identificador deve permitir que o objeto continue sendo reconhecido ao longo do tempo, mesmo quando seu nome, geometria, classificação, interpretação, estado de conservação ou conjunto de evidências for atualizado.

A identidade de um objeto não deve depender de uma fonte específica, de uma representação cartográfica específica ou de uma interface de consulta.

## Relações

Objetos Geográficos podem possuir relações com outros objetos.

As relações ajudam a representar contexto territorial, dependências espaciais, conexões físicas, hierarquias e vínculos de significado entre objetos.

Exemplos de relações incluem:

- pertence a
- contém
- conecta-se a
- cruza
- deságua em
- localiza-se em

Uma relação deve ser documentada com o mesmo cuidado que qualquer outra informação do Atlas, incluindo evidências, incertezas e conflitos quando existirem.

## Evidências

Toda informação associada a um Objeto Geográfico deve possuir uma ou mais evidências.

Evidências podem incluir fontes cartográficas, imagens, publicações, relatos, observações de campo, registros fotográficos, tracklogs ou outras referências documentadas.

A evidência deve permitir compreender de onde a informação veio, em qual contexto foi registrada e quais limitações podem afetar sua interpretação.

Informações sem evidência suficiente podem ser mantidas como hipótese, desde que essa condição esteja explícita.

## Confiabilidade

Informações sobre Objetos Geográficos possuem níveis de confiabilidade.

A confiabilidade deve considerar a origem da informação, a quantidade e qualidade das evidências, a consistência entre fontes, a atualidade do registro e o grau de incerteza associado.

A escala de confiabilidade ainda não está definida neste documento.

## Histórico

Objetos Geográficos nunca perdem histórico.

Alterações de nome, geometria, classificação, interpretação, relações, evidências ou confiabilidade devem preservar o contexto anterior sempre que esse contexto for relevante para a compreensão do objeto.

O histórico deve permitir entender como o conhecimento sobre um objeto evoluiu ao longo do tempo, incluindo revisões, correções, conflitos e hipóteses descartadas ou substituídas.

## Nomenclatura

Um Objeto Geográfico pode possuir múltiplos nomes.

Esses nomes podem incluir nomes oficiais, nomes populares, nomes históricos, variações ortográficas, nomes usados por comunidades locais, nomes presentes em mapas e nomes registrados em relatos ou publicações.

Nenhum nome deve ser tratado como definitivo sem evidência e contexto. Quando houver conflito entre nomes, o conflito deve ser documentado em vez de eliminado.

## Objetivo

Este documento estabelece apenas a modelagem conceitual de Objetos Geográficos no Atlas Vale do Pati.

Ele não define implementação, banco de dados, estruturas JSON, APIs, formatos de arquivo, interfaces ou tecnologias.
