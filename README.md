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


- `git branch`: explicação de que lista as branches do repositório, e que o `*` indica a branch atual.
    - Incluiu também `git branch -M main` (renomeia a branch atual para `main`, forçando mesmo se já existir).
- `git checkout <nome da branch>`: troca de branch.
    - Incluiu `git checkout -D <nome da branch>` para deletar a branch (com a observação de remover as alterações junto).
- `git merge <nome da branch>`: explicação de mesclar branches (exemplo com `main` e uma branch “teo”), com um callout destacando que a `main` deve ser “protegida” e alterações devem vir via branches.
- “Gerenciando conflitos”: seção nova explicando conflito de merge quando duas pessoas alteram a mesma linha, com exemplo (ana vs teo), e como resolver editando o arquivo e escolhendo o conteúdo correto (com prints do editor/markers e o passo de limpar e salvar).
- Novo capítulo: “Começando a fazer commits com o GitHub”, com:
    - Como criar repositório no GitHub (nome, descrição, público vs privado, README opcional).
    - “Setup” com as duas opções do GitHub (criar repo local novo ou conectar um repo local existente ao remoto) e uso de HTTPS (comentário de que SSH será visto depois).
    - “No Git”: passo a passo do fluxo de subir o repo local pro GitHub (remote add + `git push origin main`), com um callout dizendo que ele fez o `remote add` fora da `main` (na branch “teo”) e que não deu problema, mas recomenda fazer na `main`. Também foi adicionada a observação de que o README foi criado depois.

Criamos arquivos para desenvolver essa habilidade prática.