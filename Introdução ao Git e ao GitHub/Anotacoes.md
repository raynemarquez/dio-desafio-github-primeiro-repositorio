[Download do Git](https://git-scm.com/downloads)

Principais comandos Git:

* Git status
Permite ver quais arquivos estão sendo “rastreados” pelo git e quais modificações já foram enviadas para o stage. Permite ver o status de cada arquivo para confirmar o que esta sendo enviado

* Git add
Adiciona os arquivos solicitados ao ambiente de stage, as modificações daquele arquivo serão gravadas na próxima remessa. 
Com git add . serão adicionados todos os arquivos na pasta.

* Git commit
Para gravar as modificações, cria um "Snapshot" do estado atual do nosso projeto. 
A forma mais usada é git commit -m “descrição das atualizações do projeto” onde o -m é uma é a mensagem de descrição desse commit

* Git push
Para subir as modificações no nosso repositório remoto, para isso basta utilizar o comando git push e, se já estiver tudo devidamente configurado, os arquivos serão salvos no repositório remoto correspondente ao seu repositório local

