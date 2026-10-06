# PPDM - Flutter Getting Started

## Unidade Curricular

Programação para Dispositivos Móveis (PPDM)

## Tópicos

- 01 - Dispositivos Móveis
- 02 - Criação de Interface

## PARTE 1 - Respostas Conceituais

### 1. Diferença de Arquiteturas

O desenvolvimento Nativo é feito especificamente para uma plataforma, como Android ou iOS, utilizando as tecnologias próprias de cada sistema. Já o desenvolvimento Cross-Platform, como o Flutter, permite desenvolver aplicações para diferentes plataformas utilizando uma base de código compartilhada.

### 2. Ciclo de Vida e Widgets

Um StatelessWidget é um widget que não possui um estado que muda durante a execução da aplicação. Ele é indicado para elementos que não precisam ser alterados, como textos, ícones e informações fixas.

Um StatefulWidget possui um estado que pode ser alterado durante a execução da aplicação. Ele é indicado para elementos interativos, como contadores, formulários e telas que precisam atualizar informações.

### 3. Gerenciamento de Estado

Quando o método setState() é chamado dentro de um StatefulWidget, o Flutter é informado de que o estado do widget foi alterado. Com isso, o método build() é executado novamente e a interface é atualizada para apresentar os novos valores.