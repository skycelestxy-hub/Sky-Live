SKY LIVE — GitHub Pages

ARQUIVOS:
- index.html: painel de controle (página inicial)
- live.html: tela pública da transmissão

PUBLICAR:
1. Extraia este ZIP.
2. Crie um repositório no GitHub.
3. Envie index.html e live.html para a raiz do repositório.
4. Abra Settings > Pages.
5. Em Build and deployment, escolha Deploy from a branch.
6. Selecione a branch main e a pasta /(root), depois Save.

USAR:
- Painel: https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/
- Live: https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/live.html

Abra as duas páginas no mesmo navegador. A sincronização entre abas usa BroadcastChannel/localStorage.
Não sincroniza entre dispositivos ou navegadores diferentes. Não usa Firebase nem servidor local.

SOM:
- Os sons são gerados no navegador (Web Audio), sem arquivos extras.
- Na live, clique em "Ativar som" ao abrir (os navegadores exigem um clique para liberar áudio).
- O botão "Som ligado/desligado" na live silencia tudo; a escolha fica salva.
- No painel, "Testar som na live" toca um bipe para conferir.
- Sons: troca de tela, alerta de donate, donate ON/OFF.

Donate é apenas demonstrativo e não processa pagamentos reais.
