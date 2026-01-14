# 📌Aprendendo Git, GitHub e Versionamento de Código

## O que é Git
Sistema de controle de versão que registra alterações no código, permitindo histórico, colaboração e recuperação de versões anteriores.

## O que é GitHub
Plataforma online que hospeda repositórios Git e facilita o trabalho colaborativo, revisão de código e versionamento remoto.

## O que é Versionamento de Código
Prática de acompanhar e gerenciar mudanças no código ao longo do tempo, mantendo organização e histórico do projeto.

---

# 📌 Comandos Git — Resumo

## Básicos
- `git version`  
  Mostra a versão do Git instalada.

- `git init`  
  Inicializa um repositório Git na pasta atual.

- `git status`  
  Mostra o estado dos arquivos no repositório.

---

## Adição e Commit
- `git add <arquivo>`  
  Adiciona um arquivo ao stage.

- `git add .`  
  Adiciona todos os arquivos modificados ao stage.

- `git commit -m "mensagem"`  
  Salva as alterações com uma mensagem descritiva.

---

## Branches
- `git branch`  
  Lista as branches existentes.

- `git branch -m <nome>`  
  Renomeia a branch atual.

- `git checkout -b <nome>`  
  Cria e muda para uma nova branch.

- `git checkout <branch>`  
  Muda para uma branch existente.

- `git merge <branch>`  
  Mescla outra branch à branch atual.

---

## Repositório Remoto
- `git remote add origin <link>`  
  Conecta o repositório local ao remoto.

- `git remote -v`  
  Lista os remotes configurados.

- `git remote rm <nome>`  
  Remove um remote.

- `git remote remove <nome>`  
  Remove um remote (mesma função).

---

## Envio e Atualização
- `git push -u origin <branch>`  
  Envia commits para o repositório remoto.

- `git pull`  
  Atualiza o repositório local com mudanças do remoto.

- `git clone <link>`  
  Clona um repositório remoto para a máquina local.

---

## Outros
- `clear`  
  Limpa a tela do terminal.

- **Pull Request (PR)**  
  Solicitação para revisar e integrar alterações no GitHub.
