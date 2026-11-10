# 💬 Exercício de HTML — Página inspirada no Discord

Esta pasta reúne um exercício de reprodução da estrutura de uma página inspirada no Discord, realizado durante os **estudos de HTML**.

## O que estou praticando

- Estrutura básica de um documento HTML;
- Cabeçalhos, parágrafos, links, imagens e listas;
- Organização de seções: navegação, destaque, conteúdo e rodapé;
- Uso de caminhos relativos, como `img/logo.svg`.

## Organização verificada no GitHub

```text
licoes/discord/
├── index.html
├── README.md
├── css/
│   ├── style.css
│   ├── font.ginto.css
│   └── font.whitney.css
├── imagens/
│   ├── logo.svg
│   ├── grupo-estudo.svg
│   ├── canal-voz.svg
│   ├── membros.svg
│   ├── relaxando.svg
│   └── demais ícones e recursos visuais
├── java/
│   └── stylesheet.js
└── fonts/
    └── arquivos de fontes utilizados pelo material da aula
```

Os nomes **`imagens/`** e **`java/`** foram escolhidos ao enviar o material e estão preservados. O HTML tinha referências a `img/`, mas os arquivos estavam em `imagens/`: esses caminhos foram corrigidos. Também foram ajustados caminhos dentro dos arquivos de apoio CSS e JavaScript.

### Dependências e execução

O `index.html` carrega o script externo `https://unpkg.com/@codans/discord`, portanto a reprodução da estilização depende de uma conexão e da disponibilidade desse recurso de terceiros. Há também um script local em `java/stylesheet.js` (material fornecido), que está guardado para estudo; **não foi adicionado automaticamente ao HTML**, para não misturar duas formas de inicialização. A presença dos arquivos de apoio **não representa domínio de CSS ou JavaScript** nesta etapa.

Para estudar, abra `index.html` no navegador (de preferência com Live Server no VS Code). **O resultado visual final ainda não foi validado em navegador nesta atualização.**

> Foram identificados arquivos auxiliares de 1 byte e um `.DS_Store` legado, que não são necessários para o exercício. Permanecem no repositório até uma limpeza específica. Um `bg-cloud.svg` vazio também merece revisão. Fontes e outros recursos obtidos no material da aula podem ter restrições de redistribuição: confirme a licença antes de manter esses binários em um repositório público.

## Fonte e atribuição

Este é um **exercício de estudo**, não uma página oficial do Discord nem um projeto comercial. O material fornecido possui referências a `@codans/discord` e ao repositório da aula: https://github.com/jamiltondamasceno/web-com-javascript/tree/main/discord. Marcas, imagens e códigos de terceiros pertencem aos respectivos autores.

## Próximos ajustes

- Revisar a semântica da página;
- Diferenciar links de botões e ajustar as estruturas de navegação;
- Revisar textos alternativos das imagens;
- Aprender CSS para estilizar as seções diretamente;
- Reproduzir o layout com estilos próprios futuramente.
