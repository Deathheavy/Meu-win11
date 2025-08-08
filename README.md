# Windows 11 Home Customizado + Recomendações

ISO leve e focada em privacidade do Windows 11 Home, sem bloatware e telemetria, otimizada para melhor segurança e desempenho.<br>
🔗[Baixar ISO Windows 11 Home 24H2 (NTLite)](https://drive.usercontent.google.com/download?id=1B7Tz8lOW5djMuqD7Y7Dm9o0QuYOpp_0N)


## Rufus

Rufus é uma ferramenta que ajuda a formatar e criar drives USB inicializáveis, como chaves/drives USB, cartões de memória e também remover os requisitos de instalação que a Microsoft decidiu adicionar ao Windows 11<br>
🔗[RUFUS](https://rufus.ie/pt_BR/)


## Como Usar

1. Baixe a ISO personalizada do Windows 11.
2. Use o Rufus para criar um pendrive bootável.
3. Instale o Windows 11 Home usando a ISO personalizada.

---

## Recomendação de programas adicionais

1. [WPD](https://wpd.app) - Bloquear a telemetria e os aplicativos do windows 11
2. [OOSU10](https://www.oo-software.com/en/shutup10) - Ferramenta para controlar e desativar funções de telemetria e coleta de dados no Windows.
3. [Revo Uninstaller](https://www.revouninstaller.com/br/revo-uninstaller-free-download/) - Aplicativo para limpar o sistema e também remover aplicativos do sistema
4. [Proton VPN](https://protonvpn.com) - A VPN aprimora a privacidade e a segurança online criptografando a conexão e mascarando sua IP
5. [Brave](https://brave.com) - Navegador baseado no Chrome com foco em privacidade e com Ublock Origin integrado
6. [VLC](https://www.videolan.org/vlc) - Reprodutor multimídia versátil que suporta praticamente todos os formatos de vídeo e áudio.
7. [qBittorrent](https://www.qbittorrent.org/download) - Cliente de torrent leve e de código aberto para download de arquivos P2P.
8. [WinRAR](https://www.win-rar.com/download.html) - Programa para compactar e descompactar arquivos em vários formatos.
9. [Autoruns](https://learn.microsoft.com/pt-br/sysinternals/downloads/autoruns) - Utilitário avançado para gerenciar programas que iniciam com o Windows.
10. [Notepad++](https://notepad-plus-plus.org/downloads/) - Editor de texto avançado para programadores e uso geral, com suporte a várias linguagens.


## Alterar o seu DNS para o da Cloudflare:
[DNS](https://one.one.one.one/help/) - Site da Cloudflare com guia para o setup da dns

**1.1.1.1**<br>
**1.0.0.1**

[Tutorial](https://youtu.be/tHmfMhdqlNk?t=199) - Video no youtube mostrando como editar sua dns


## Comandos e caminhos do sistema

CMD > Abrir como administrador

**DISM /Online /Cleanup-Image /RestoreHealth** - Repara a imagem do Windows usada para restaurar arquivos.<br>
**sfc /scannow** - Verifica e repara arquivos de sistema corrompidos.<br>
**chkdsk /f** - Verifica e corrige erros no sistema de arquivos do disco.<br>
**tasklist** - Lista processos em execução.<br>
**taskkill /IM nome.exe /F** - Encerra um processo específico.<br>
**ipconfig /displaydns** - Mostra o cache DNS armazenado localmente (endereços visitados recentemente).<br>
**ipconfig /release** - Libera o endereço IP atual atribuído à sua conexão.<br>
**ipconfig /renew** - Solicita um novo endereço IP ao servidor DHCP.<br>
**ipconfig /flushdns** - Limpa o cache DNS, útil para resolver problemas de acesso a sites.<br>
**net user nome /add** - Cria um novo usuário.<br>
**ping site.com** - Testa a conectividade com um servidor.<br>
**tracert site.com** - Mostra o caminho que os pacotes percorrem até um destino.<br>
**nslookup site.com** - Mostra o IP associado a um domínio.<br>


Comandos do Executar (Win + R)

**%temp%** - Abre a pasta de arquivos temporários do usuário.<br>
**temp** - Abre a pasta de arquivos temporários do sistema.<br>
**prefetch** - Abre a pasta onde o Windows armazena arquivos de pré-carregamento de programas.<br>
**msconfig** - Abre a Configuração do Sistema, onde é possível gerenciar inicialização, serviços e modo de boot.<br>
**msinfo32** - Abre a Ferramenta de Informações do Sistema com detalhes de hardware, drivers e software.<br>
**dxdiag** - Abre o Diagnóstico do DirectX, mostrando informações detalhadas de vídeo, som e drivers.<br>
**regedit** - Abre o Editor do Registro do Windows.<br>
**mrt** - Abre o utilitário oficial da Microsoft para detectar e remover malwares.<br>
**shell:startup** - Abre a pasta de inicialização automática de programas.<br>
**services.msc** - Abre a lista de serviços do Windows.<br>
**devmgmt.msc** - Abre o Gerenciador de Dispositivos, onde você vê hardware, drivers e atualizações de componentes.<br>

---

## Lista de sites confiáveis para torrent(Recomendado usar Adblock):

1. https://1337x.to - Torrents no geral, faça o download somente de uploaders confiáveis
2. https://fitgirl-repacks.site - A melhor repacker de jogos da web e a melhor fonte de jogos confiáveis
3. https://byxatab.com - Fonte de jogos confiáveis
4. https://elamigos.site - Fonte de jogos e updates para jogos crackeados
5. https://online-fix.me - Concede soluções para jogar COOP em jogos crackeados

## Assistir séries e filmes PC/Smarthphone

1. Acesse [Stremio](https://www.stremio.com/translation/br)
2. Clique em "Login" no canto superior direito
3. clique em Sign up with email
4. Preencha os campos solicitados
5. Após criar a conta, faça o download do aplicativo e acesse a sua conta
6. Acesse [Torrentio](https://torrentio.strem.fun/configure)
7. Em Providers: Desmarque os providers com RU, FR, IT, ES, MX, PL e Magnet DL
8. Em Sorting: By Seeders
9. Em Exclude qualities/resolutions: Marque para excluir Screner e Cam
10. Clique em Install com o seu aplicativo Stremio aberto e confirme a instalação no aplicativo.

Obs. Para assistir em seu smarthphone basta fazer o download do Stremio e acessar com uma conta que já foi configurada no PC.

---

## Sobre este Projeto

Este projeto tem como objetivo fornecer uma versão mais leve, segura e rápida do Windows 11 Home, removendo serviços de telemetria e programas pré-instalados (bloatware).

## Ferramentas Utilizadas

Programa utilizado para editar a ISO, removendo componentes indesejados e ajustando configurações.<br>
[NTLite](https://www.ntlite.com/download)<br>
[ISO](https://www.microsoft.com/pt-br/software-download/windows11)


## Fonte

Tutorial em inglês de como editar uma ISO<br>
▶️[Create A Custom Windows 10 or 11 ISO](https://www.youtube.com/watch?v=_gMJNQ3yWNE)
