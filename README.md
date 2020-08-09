# Project Argo

Siga os passos seguintes para criar um servidor de Project Argo.

1) Siga para https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip e baixe o SteamCMD. Faça o download, extraia em C: em uma pasta, para manter a organização. Depois de extrair, execute o arquivo "steamcmd.exe".

2) Depois que executar o steamcmd.exe e terminar de atualizar, digite os seguintes comandos no console:

login anonymous

app_update 563930 -beta server validate

3) Depois de baixar o servidor, baixe os dois arquivos do repositório "server.cfg" e "start_Argoserver.bat" e cole na pasta principal onde o jogo foi baixado (onde o arquivo "argoserver.exe" está).

4) Altere o arquivo "server.cfg" e o arquivo "start_Argoserver.bat" usando o bloco de notas ou o Notepad++. No arquivo "server.cfg" altere o nome do servidor, a senha de administrador e as mensagens de boas vindas. No arquivo "start_Argoserver.bat", altere a porta de conexão por uma porta que você preferir (não se esquece de abrir a porta para conexão). O servidor Argo usa 2 portas UDP, sendo uma configurável no "start_Argoserver.bat" e a outra não configurável, sendo sempre a porta seguinta a porta configurada, exemplo: se você escolheu a porta 33036 no "start_Argoserver.bat", você deve liberar a porta 33036 UDP e a próxima porta, a 33037 UDP também.

5) Feito isso, pode iniciar o servidor executando o arquivo "start_Argoserver.bat". Ele irá aparecer na lista de servidores para que os usuários se conectem. O modo de jogo configurado será o COOP - Combat Patrol.
