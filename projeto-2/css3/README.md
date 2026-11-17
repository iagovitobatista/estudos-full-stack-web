# 🎨 CSS3 — Primeiros exercícios práticos

Esta pasta registra a continuidade do estudo de **HTML e CSS3 no Visual Studio Code**. Os exemplos foram revisados para deixar a estrutura HTML mais consistente e os códigos mais fáceis de entender, preservando os temas estudados no ZIP da aula.

## Assuntos praticados

| Conteúdo | Exercício |
| --- | --- |
| CSS externo e navegação entre páginas | [index.html](index.html), [produtos.html](produtos.html) e [contato.html](contato.html) |
| CSS inline, interno e externo | [contato.html](contato.html), [fontes-cores.html](fontes-cores.html) |
| Seletores de classe e ID | [class-id-exercicio.html](class-id-exercicio.html) |
| Uso de div e span | [div-span.html](div-span.html) |
| Fontes e cores (RGB, HEX e RGBA) | [fontes-cores.html](fontes-cores.html), [fontescores.html](fontescores.html) |
| Bordas, arredondamento e espaçamento | [bordas.html](bordas.html) |
| Box Model: margin, padding, border | [modelo-caixa.html](modelo-caixa.html), [margin-padding.html](margin-padding.html) |
| Exercícios de layout inspirados em lojas | [index-americanas.html](index-americanas.html), [celulares-americanas.html](celulares-americanas.html), [magalu.html](magalu.html) |

## Estrutura

```text
projeto-2/
└── css3/
    ├── css/
    │   └── estilo.css
    ├── img/             # mídias da aula ainda pendentes de envio ao GitHub
    ├── index.html
    ├── produtos.html
    ├── contato.html
    ├── bordas.html
    ├── modelo-caixa.html
    └── outros exercícios .html
```

## Como visualizar

Abra um dos arquivos `.html` diretamente no navegador, ou use o **Live Server** no VS Code. Os arquivos que usam imagens fazem referência ao diretório relativo `img/`, que precisa conter as imagens da aula.

**Importante:** o material original do ZIP incluiu 17 imagens e arquivos de estudo do curso. As imagens grandes **ainda não foram enviadas ao repositório pelo assistente**; por isso algumas páginas podem aparecer sem elementos visuais até que a pasta `img/` seja adicionada ao GitHub.

## Melhorias nesta revisão

- Estrutura padronizada com `<!DOCTYPE html>`, `lang="pt-BR"`, `meta charset` e `viewport`;
- Correção de fechamento de tags e padronização de `head` e `body`;
- Navegação corrigida para os arquivos existentes;
- Textos alternativos nas imagens (`alt`);
- Exemplos de `margin`, `padding`, `border`, `class` e `id` mantidos e comentados;
- Textos comerciais substituídos por descrições de exercício quando necessário.

## Transparência e créditos

As páginas com referências a **Americanas, Magalu, Mercado Livre e Fórmula 1** são **reproduções de estudo**, não sites oficiais, e não são afiliadas a essas marcas. Elementos gráficos do material da aula podem pertencer aos respectivos titulares. Verifique os direitos de uso antes de publicar as mídias em um repositório público.

**Etapa atual:** HTML + introdução prática ao CSS3. JavaScript, Node.js, TypeScript e n8n continuam como estudos futuros neste repositório.
