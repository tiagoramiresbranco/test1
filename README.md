# Visualização de Turnos e Escalas de Funcionários

Programa simples (front-end) para **cadastrar** agentes e **visualizar** turnos/escala em uma tabela com uma **linha do tempo** (turno + almoço).

## Como usar

- Abra o arquivo `index.html` no navegador.
  - Dica: em muitos editores (ex.: VS Code) você pode usar uma extensão tipo “Live Server”, mas não é obrigatório.

## O que dá para cadastrar

- **Nome do agente**
- **Função**: `telefone`, `chat` ou `email`
- **Entrada** e **Saída**
- **Almoço** (opcional): **Início** e **Fim**

## O que o app mostra

- Lista de todos os agentes em uma **tabela**
- Colunas com **entrada/saída/almoço**
- **Carga líquida** (turno menos almoço)
- **Visual**: barra do turno e marcador do almoço na linha do tempo
- **Busca por nome** e **filtro por função**
- **Editar** e **remover** agentes

## Persistência

Os dados ficam salvos no seu navegador via **`localStorage`** (não precisa de backend).