# Biblioteca do Bairro

Projeto da Aula 01 de Programação Web 1 (IPCA, 2026/27). Pequeno site estático em HTML e CSS, feito para praticar a estrutura básica de uma página, as tags de texto e os seletores CSS, e para criar o primeiro repositório Git.

## Como abrir

Não precisa de instalar nada. Abra `index.html` num browser (duplo clique no ficheiro) ou use a extensão **Live Server** do VS Code para a página atualizar sozinha a cada alteração.

## Ficheiros

| Ficheiro | Conteúdo |
|---|---|
| `index.html` | Página principal da Biblioteca do Bairro: títulos (`h1`–`h3`), parágrafos e tags de formatação de texto |
| `index2.html` | Exercício de uma ementa de restaurante, usado para testar classes e ids no CSS |
| `sobre.html` | Página "Sobre", ainda vazia |
| `style.css` | Folha de estilos partilhada pelas páginas |

## O que se pratica

**HTML (`index.html`)**

- Estrutura do documento: `<!DOCTYPE html>`, `<html lang>`, `<head>`, `<meta charset>`, `<title>`
- Hierarquia de títulos `h1`, `h2` e `h3`
- Parágrafos `<p>`, quebra de linha `<br>` e linha horizontal `<hr>`
- Formatação de texto: `<strong>`, `<em>`, `<mark>`, `<sub>`, `<sup>`, `<abbr>`, `<code>`, `<small>`
- Entidades HTML: `&lt;`, `&gt;`, `&nbsp;`, `&copy;`

**CSS (`style.css`)**

| Tipo de seletor | Exemplo | Efeito |
|---|---|---|
| Elemento | `h2 { color: blue; }` | Todos os `h2` ficam azuis |
| Grupo | `h1, h4 { color: red; }` | Mesma regra para vários elementos |
| Pseudo-classe | `h3:hover { ... }` | Muda a cor quando o rato passa por cima |
| Classe | `.alcool { color: purple; }` | Elementos com `class="alcool"` |
| Id | `#horario { color: orange; }` | O elemento com `id="horario"` |

Em `index2.html`, o `h2` "Pratos do dia" tem a classe `alcool`, por isso fica roxo e não azul: a classe é mais específica do que o seletor de elemento.

## Por fazer

- Preencher `sobre.html`
- Em `index2.html`, mudar `lang="en"` para `lang="pt-PT"` e dar um título à página (atualmente "Document")
- Ligar as páginas entre si com `<a href="...">`

## Registo de ações

- Criei um repositório e fiz commit

## Identificação

- **Nome:** Antonio Machado
- **Email:** antonio.machado@gmail.com
