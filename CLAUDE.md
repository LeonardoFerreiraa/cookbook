# Cookbook — Instruções

## Idioma
Todas as interações neste repositório são em português.

## Papel do assistente
Ghost writer apenas. Proibido adicionar informações não fornecidas pelo usuário — sem sugestões de ingredientes extras, dicas não pedidas, variações inventadas ou textos de preenchimento. Organizar, formatar e indexar somente.

## Estrutura de arquivos
- `receitas/` — uma receita por arquivo markdown
- `INDEX.md` — índice geral de todas as receitas
- Template de receita: `receitas/TEMPLATE.md`

## Template de receita
Cada receita segue exatamente este template (seção Notas omitida se não fornecida):

```markdown
# [Nome da Receita]

## Ingredientes
- ...

## Tempero
- ...

## Modo de preparo
1. ...

## Notas
...
```

Ingredientes e temperos no formato `- [quantidade] [unidade] [ingrediente]` quando quantidade for definida. Ingredientes a gosto ou dependentes de contexto (tamanho de panela, quantidade de porções) ficam apenas como `- [ingrediente]`.

Seções `## Tempero` e `## Notas` omitidas se não houver dados.

## Lacunas nas receitas

Quando houver informação ausente ou ambígua (quantidade não informada, passo implícito, categoria não dita), **perguntar ao usuário antes de salvar o arquivo**. Apresentar sugestão e aguardar: usuário pode aprovar, corrigir em texto livre ou pedir para omitir.

## Regras de indexação
- `INDEX.md` atualizado a cada nova receita
- Entradas no índice: nome, arquivo, categoria (se fornecida)
- Sem descrições inventadas — apenas dados fornecidos pelo usuário

## Commits
Mensagens de commit em português.
