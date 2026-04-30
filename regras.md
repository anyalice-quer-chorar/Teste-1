# Regras do Projeto
  
---------------------------------------------------------------------

## Regras da Branch Principal (main)
- Proibido fazer push direto na main
- Todas as alterações devem ser feitas via Pull Request (PR)
- PR deve ter pelo menos 1 aprovação
- PR só pode ser aprovado se passar pela revisão e teste

-------------------------------------------------------------------

## Fluxo de Trabalho
- Criar uma branch
- Fazer as alterações
- Realizar commits seguindo o padrão
- Abrir um Pull Request (PR)
- Aguardar revisão
- Após aprovação e testes OK - merge na `main`

-------------------------------------------------------------------
  
## Revisão de Código (Obrigatória)

Todo Pull Request deve ser revisado por outro membro da equipe.
##
O que deve ser analisado:
- Funcionamento do código
- Possíveis impactos em outras partes do sistema
- Organização e clareza do código
- Seguir o padrão definido

-------------------------------------------------------------------
  
## Testes Automáticos
Utilizamos GitHub Actions para:

- Executar testes automaticamente
- Validar o funcionamento do sistema
- Bloquear merges em caso de erro

-----------------------------------------------------------------

## Boas Práticas de Código

- Testar antes de fazer commit
- Não subir código quebrado
- Manter organização e legibilidade
- Comentar apenas quando necessário
  
-------------------------------------------------------------------
## Pradronização de Commit

- feat - nova funcionalidade
- fix - correção de bug
- docs - documentação
- style - formatação (sem mudar lógica)
- refactor - melhoria no código
- test - testes
- chore - tarefas internas (config, build)

## A descrição precisa ser objetiva

Ex:
  
   `feat: adiciona tela de login`
   
   `fix: corrige erro de autenticação`

----------------------------------------------------------------

## O que NÃO fazer

- Commit direto na main
- Ignorar revisão de código
- Subir código sem testar
- Fazer mudanças grandes sem explicação
