# Contribuindo

Contribuições são bem-vindas, desde que preservem a clareza, a rastreabilidade e o caráter incremental do projeto.

## Boas práticas

- Documente a origem de qualquer dado adicionado ao repositório.
- Preserve dados brutos sem modificações em `data/raw/`.
- Registre dados derivados ou tratados em `data/processed/` apenas quando a transformação estiver documentada.
- Mantenha cadastros de referência, como fontes, tipos de objetos e regiões, em `data/reference/`.
- Evite introduzir tecnologias, dependências ou frameworks sem discussão e justificativa prévia.
- Prefira mudanças pequenas, revisáveis e alinhadas à visão do projeto.
- Use linguagem clara em documentos e comentários.
- Não inclua dados sensíveis, privados ou de origem incerta.

## Organização de dados

Sempre que uma nova fonte for considerada, inclua informações sobre:

- Origem da fonte.
- Data de acesso ou coleta.
- Licença ou condições de uso.
- Escopo geográfico.
- Limitações conhecidas.

## Revisão

Antes de propor mudanças, verifique se elas:

- Mantêm a separação entre documentação, dados brutos, dados processados e ativos.
- Não antecipam decisões técnicas ainda não tomadas.
- Não adicionam arquivos, ferramentas ou automações desnecessárias.
