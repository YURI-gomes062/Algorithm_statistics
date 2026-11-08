### Convenção de Commits (Conventional Commits)

| Tipo | Descrição / Quando Usar | Exemplo |
|---|---|---|
| `feat` | Adição de uma nova funcionalidade no sistema. | `feat(auth): adiciona validacao de token JWT` |
| `fix` | Correção de um bug ou erro no código. | `fix(db): corrige vazamento de conexao no pool` |
| `docs` | Alterações exclusivas na documentação. | `docs(readme): atualiza instrucoes de instalacao` |
| `style` | Mudanças que não afetam o sentido do código (formatação, ponto e vírgula, lint). | `style(eslint): aplica regras de formatacao` |
| `refactor` | Refatoração de código sem alterar comportamento (sem nova feat/fix). | `refactor(user): simplifica logica de busca` |
| `perf` | Alteração de código focada em melhoria de desempenho. | `perf(queries): otimiza consulta de relatorio` |
| `test` | Adição ou correção de testes automatizados. | `test(auth): adiciona testes unitarios para login` |
| `chore` | Atualização de tarefas de build, configurações ou dependências. | `chore(deps): atualiza versao do pacote express` |
| `ci` | Mudanças nos arquivos de integração/entrega contínua (CI/CD). | `ci(github): adiciona pipeline de deploy` |
