## O que esta PR faz?

<!-- Descrição objetiva da mudança. Uma frase clara é suficiente. -->

## Tipo de mudança

- [ ] `feat` — nova funcionalidade
- [ ] `fix` — correção de bug
- [ ] `refactor` — sem mudança de comportamento
- [ ] `chore` — configuração, dependência ou build
- [ ] `docs` — documentação
- [ ] `perf` — melhoria de performance

## Escopo afetado

- [ ] card
- [ ] invoice
- [ ] transaction
- [ ] profile
- [ ] notification
- [ ] auth
- [ ] shared / theme / navigation
- [ ] infrastructure / mock

## Checklist técnico

- [ ] Arquitetura MVVM respeitada — sem lógica de negócio em View
- [ ] Nenhum `any` — tipos explícitos em tudo
- [ ] Nenhum `StyleSheet` — apenas Restyle
- [ ] Nenhuma string de marca hardcoded — usando `useBrandConfig()`
- [ ] Imports via aliases — sem caminhos relativos longos
- [ ] `testID` em elementos interativos novos
- [ ] Mocks com delay simulado se houver novo repository

## Checklist de processo

- [ ] Branch criada a partir de `develop`
- [ ] Commits seguem Conventional Commits
- [ ] `CHANGELOG.md` atualizado na seção `[Unreleased]`
- [ ] Testado no iOS (Expo Go)
- [ ] Testado no Android (Expo Go)

## Screenshots

<!-- Adicionar se houver mudança visual. Formato sugerido: -->
<!--
| Antes | Depois |
|-------|--------|
| img   | img    |
-->

## Observações

<!-- Decisões técnicas, trade-offs, débito técnico gerado, dependências de outras PRs -->
