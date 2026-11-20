# visual-docs

Plugin que ajuda o Claude a criar documentos (Word e PDF) com identidade visual própria, em vez do visual padrão de template.

## O que faz

A skill `documento-autoral` entra em ação quando você pede um documento com "visual diferente", "fora do padrão" ou "criativo". Ela escolhe uma direção estética (editorial, brutalista, minimalista, blueprint, retrô, noturno ou zine), define fontes, cores e grade, gera o arquivo e confere o resultado visualmente antes de entregar.

## Exemplos de pedidos

- "Faça o relatório do projeto de banco de dados com visual diferente"
- "Quero uma proposta com cara de revista"
- "Documento em estilo blueprint para a modelagem do sistema"

## Estrutura

- `skills/documento-autoral/SKILL.md`: fluxo e regras de design
- `skills/documento-autoral/references/direcoes-esteticas.md`: catálogo de direções

## Observação

Trabalhos com norma obrigatória (como ABNT) mantêm a formatação exigida; a ousadia visual fica restrita às partes livres, como capa e destaques.

## Autor e licença

Autor: JLemosDev. Licença MIT (veja o arquivo `LICENSE`).
