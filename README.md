# Curso TMW Git & GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub.

Aprendizado:

- O problema que o Git ajuda a resolver: como lidar com muitas alterações no projeto, tomar decisões reversíveis, colaborar com vários contribuidores e distribuir o trabalho.
- O que é o Git: um software de controle/gerenciamento de versão para arquivos de texto, criado por Linus Torvalds (no contexto do kernel do Linux), open-source e multiplataforma.
- Conceitos:
    - Commit: cada etapa vira uma “versão/salvamento” (ponto de controle), permitindo criar linhas secundárias (branches). Há uma imagem ilustrando commits como nós.
- Uma lista de comandos básicos (principalmente de terminal e Git), com breves explicações e imagens:
    - `ls`: lista itens do diretório
    - `ls -a`: mostra arquivos ocultos (que começam com `.`)
    - Observação sobre pasta mãe: `../` para subir um diretório
    - `cd`: muda de diretório
    - `pwd`: mostra o caminho absoluto atual
    - `cat`: abre/exibe um arquivo (conforme descrito no texto)
    - `git init .`: inicia um repositório Git no diretório
    - `rm -rf`: remove o diretório do Git (e arquivos dentro, como descrito)
    - `git status`: mostra o estado do diretório/repositório
    - `git add`: adiciona arquivos para irem ao commit (stage)
    - `git commit -m "texto descritivo"`: cria o commit com mensagem
    - Nota de configuração de usuário: `git config --global user.email "..."` e `git config --global user.name "..."`
    - `git diff <arquivo>` ou `git diff .`: mostra diferenças
    - `git reset <nome do arquivo>`: remove arquivo do stage antes de commitar

Criamos arquivos para desenvolver essa habilidade prática.