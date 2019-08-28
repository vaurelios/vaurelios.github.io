---
layout: post
title: Windows 7 não conecta em redes protegidas (WPA / WPA2)
published: true
---
## Windows 7 não conecta em redes protegidas (WPA / WPA2)

A pedido de um cliente instalei o *Windows 7* em seu notebook, como primeiro
passo após a instalação tomei a instalação dos drivers de rede para prosseguir
com a instalação dos demais.

Após instalação bem sucedida do driver WLAN (Realtek) o qual obtive no site do
fabricante (HP) tentei conectar a minha rede (WPA2) e para minha surpresa logo
após inserir a senha o mini assistente do Windows me retornava erro.

Ao tentar conectar em uma rede aberta a conexão foi bem sucedida e funcionou
tudo normal.

Voltei ao site do fabricante e notei que o driver que tinha obtido era para
Windows 8.1 e que não tinha nenhum disponível para o *7*, partindo dai
procurei outro driver especifico para Windows 7 após conseguir instalei, e
consegui me conectar com sucesso a minha rede protegida.

Resumindo: Procurem sempre drivers específicos para sua versão do
<abbr title="Sistema Operacional">SO</abbr> e evitem esta dor de cabeça.
Abaixo deixo o link do driver que usei neste caso.

- HP Pavilion x360 11-n026br:
  - WLAN Realtek: [Windows 7 x64](http://dl.drp.su/driverpacks/repack/WLAN-WiFi/Ralink/FORCED/7x64/2860_5.00.59/Ralink-FORCED-7x64-2860_5.00.59-drp.zip)
