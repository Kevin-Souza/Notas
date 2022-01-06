# GIT

link para download: [https://git-scm.com/download](https://git-scm.com/download)

link do vídeo: [https://www.youtube.com/watch?v=2alg7MQ6_sI](https://www.youtube.com/watch?v=2alg7MQ6_sI)

link documentação da chave SSH: [https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

---

### Git inicio/comandos básicos e repositório local

- git init _ inicia a linha do tempo.
- git add +nome do arquivo _ adiciona ou atualiza mudanças para irem para a linha do tempo.
    - git add . _ o ponto permite adicionar todos os itens da pasta de uma só vez.
- git commit -m "mensagem" _ adiciona um ponto na linha do tempo.
    - git commit -am "mensagem" _ já adiciona ou atualiza mudanças e já cria um ponto na linha do tempo com as alterações.
- git log _ visualiza os pontos na linha do tempo _ commit.
- git status _ informa o estado das alterações do nosso projeto.
- git show +numero do commit(ou nada para mostrar o ultimo ponto na história) _ apresenta determinado ponto do tempo.
- git branch +nome desejado_ gerenciar novas linhas do tempo, pode ser usado para testar alterações antes de serem adicionadas no código final, sem risco de danificar ou quebrar o código principal.
    - git branch -D +nome da branch _ exclui a branch citada.
- git checkout +nome da branch _ manipula as linhas do tempo.
    - git checkout -b + nome da branch _ cria uma branch nova e já é direcionado para ela.
    - git checkout +ponto da linha do tempo — nome do arquivo _ retorna um determinado arquivo para um determinado ponto da linha do tempo.
- git merge +nome da branch_ unir linhas do tempo.

---

### Git para repositórios remotos

- git remote add origin +link _ adiciona um repositório remoto(nuvem).
- git remote -v _ permite visualizar os repositórios remotos.
- git push _ envia alterações locais para o repositório remoto.
    - git push -u origin master _ na primeira vez que der um git push no repositório para que seja criada a branch master.
- git clone + link _ clonar um projeto / Repositório.
- git pull _ puxa do repositório remoto(atualizações do repositório), aconselhável realizar o git pull antes de realizar o envio de dados para não ocorrer conflitos.
- git config credencial.helper store _ guarda as credenciais de usuário e senha do github assim não exigindo-os a cada ação no repositório remoto.

---