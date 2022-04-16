# Git/GitHub :computer:
Comandos git/github

- openssl sha1 *nome_do_arquivo.extensao* :arrow_right: O git por trás dos panos, codifica arquivos em códigos de 40 caracteres tornando-os mais seguros
- git config :arrow_right: Aparece todos os comandos de configuração
- - git config --list :arrow_right: Lista as configurações já definidas
- - git config --global --unset *config.escolhida* :arrow_right: Apaga a configuração escolhida
- git init :arrow_right: Inicia um repositório GIT na pasta
- git add *nome do arquivo* :arrow_right: Adiciona os arquivos que foram criados ou que foram modified
- - git add . :arrow_right: Adiciona **TODOS** os arquivos de uma única vez
- - git add * :arrow_right: Adiciona **TODOS** os arquivos de uma única vez
- git commit -m "*algum nome identificador do commit*" :arrow_right: 'Commita' tudo o que foi adicionado/modificado
- - -m :arrow_right: Pula a solicitação do editor de texto em favor de uma mensagem integrada
- git status :arrow_right: Verifica em que estado está os arquivos
- git remote add *origin* *URL* :arrow_right: Envia os commits da máquina local para o GITHUB
- - **origin** :arrow_right: "apelida" a URL para não precisar digitá-la todas as vezes
- - git remote add -v :arrow_right: Lista dos repositórios remotos cadastrados
- git push *origin* *master* :arrow_right: Empurra os commits da máquina para o GITHUB
- - **master** :arrow_right: Branch em que está sendo enviado os commits
- git pull *origin* *master* :arrow_right: Puxa os commits do GITHUB para a máquina local
- git clone *URL* :arrow_right: Clona para máquina projetos que estão no GITHUB

[:leftwards_arrow_with_hook: MENU](README.md)