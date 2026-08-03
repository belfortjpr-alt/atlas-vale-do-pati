# Organização dos objetos geográficos

Este diretório será usado para organizar os objetos geográficos reais do Atlas Vale do Pati.

Nenhum objeto está cadastrado nesta etapa. Este documento define apenas a estrutura esperada para organização futura dos arquivos.

## Estrutura por categoria

Cada categoria de objeto geográfico possuirá seu próprio diretório dentro de `data/entities/`.

As categorias iniciais são:

```text
rivers/
waterfalls/
pools/
trails/
viewpoints/
campsites/
houses/
caves/
geological_features/
bridges/
crossings/
access_points/
```

## Arquivos individuais

Cada objeto geográfico será representado por um único arquivo YAML individual dentro do diretório da sua categoria.

Um objeto nunca compartilhará arquivo com outro objeto. Cada arquivo deverá representar exatamente um objeto geográfico.

Este documento não define atributos, formatos internos, relações, validações ou implementação.
