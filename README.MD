# Versionamento Semântico Automático

Exemplo de versionamento automático utilizando a action `release-please` do Google.

## Regras de versionamento semântico

- **major (X.0.0)** → Quando há mudanças incompatíveis na API
  Exemplo: feat!: mudança que quebra compatibilidade
- **minor (0.X.0)** → Quando há novos recursos sem quebrar compatibilidade
  Exemplo: feat: adiciona suporte a múltiplos usuários
- **patch (0.0.X)** → Quando há correções de bugs ou melhorias internas
  Exemplo: fix: corrige erro ao carregar imagem
