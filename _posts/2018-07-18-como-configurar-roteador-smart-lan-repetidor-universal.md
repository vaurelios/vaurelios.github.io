---
layout: post
title: Como configurar roteador SMART LAN em modo Repetidor Universal
published: true
---
## Como configurar roteador SMART LAN em modo Repetidor Universal

Nesse pequeno guia estarei mostrando como configurar o roteador __SMART LAN__ em modo Repetidor Universal (AP+Cliente), o roteador que tenho em mãos é o `APRIO150`.

Bem, o primeiro passo é acessar a página de configurações do roteador, por padrão de fábrica é acessível com seguintes dados:

  - Endereço: `http://192.168.1.254`
  - Usuário: `admin`
  - Senha: `admin`

O próximo passo é trocar o *Modo de operação* do roteador, para isso:

  1. Selecione `Modo de Operação` no menu.
  2. Selecione `Cliente`.
  3. Clique em `Aplicar`.
  
  ![Modo Cclinte]({{ "/img/2018-07-18-smartlan-modo-de-operacao.png" | absolute_url }})

Agora iremos configurar o cliente, para isso:

  1. Selecione `Wireless` no menu.
  2. Selecione `Configurações Básicas` no menu dentro de `Wireless`.
  3. Clique em `Site Survey`.
  4. Na janela que aparecer selecione o <abbr title="Access Point">AP</abbr> que você deseja repetir o sinal e clique em `Selecionar AP`, então o *SSID*, e o tipo de segurança serão selecionados automaticamente.
  5. Entre com a senha do <abbr title="Access Point">AP</abbr> no campo `Chave`.
  6. Clique em `Aplicar Alterações`.
  
  ![Configurações Básicas]({{ "/img/2018-07-18-smartlan-wireless-config-basicas.png" | absolute_url }})
  ![Site Survey]({{ "/img/2018-07-18-smartlan-wireless-site-survey.png" | absolute_url }})

E por último, e não menos importante, iremos configurar o <abbr title="Access Point">AP</abbr>, para isso:

  1. Selecione `Configurações do Repetidor` dentro do menu `Wireless`.
  2. Em `Interface Wireless` marque `Habilitado`.
  3. No campo `SSID` entre com o nome desejado para o <abbr title="Access Point">AP</abbr>.
  4. Selecione a criptografia desejada (recomendo `WPA2-PSK`).
  5. Entre com a senha no campo `Chave`.
  6. Clique em `Aplicar Alterações`.
  
  ![Configurações do Repetidor]({{ "/img/2018-07-18-smartlan-wireless-config-repet.png" | absolute_url }})
 
Pronto, seu roteador deve está conectado e funcionando em modo *Cliente + AP*, resolvi fazer este guia porque apesar de ser fácil fazer essa configuração a interface do __SMART LAN__ não é tão intuitiva como de alguns concorrentes.
