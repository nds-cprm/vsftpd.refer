f4788fa2-0f32-11eb-a154-0fd310ec83e9 Thu, 15 Oct 2020 19:08:28 -0300
<<<<<<< HEAD
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project is simple Lorem ipsum dolor generator.
    
## Technologies
    Project is created with:
    * Lorem version: 12.3
    * Ipsum version: 2.33
    * Ament library version: 999
        
## Setup
        To run this project, install it locally using npm:

        ```
        $ cd ../lorem
        $ npm install
        $ npm start

        ```
=======
# vsftpd-refer
Instalação para servidor de vsftpd (https://security.appspot.com/vsftpd.html), versao 3.0.3 em imagem linux debian:buster-slim, para container no formato docker.

## Especificações
Utiliza as portas 20, 21, 63000-63100.

A configuração inicial, define: 
  sem acesso TLS/SSL, 
  sem acesso anonymous, 
  sem acesso de usuarios virtuais,
  com acesso restrito de usuarios de sistema, definidos no mesmo grupo, sem acesso a shell e sem diretorio, 
  com acesso compartilhado de area comum /data, compartilhada com permissão 1775

A area comum /data é definida como volume externo ao container;  

Os usuarios devem ser criados por acesso direto ao container, usando o script /bin/ftponly e definindo as passwords, e terao acesso aos diretorios /data e /tmp;

## Aviso Legal (Disclaimer)
Isenção de responsabilidade. Quem usa este site o  faz por sua conta e risco.  A CPRM, seus parceiros, colaboradores, funcionários e representantes não se responsabilizam por quaisquer erros ou omissões que possam afetar o conteúdo deste site ou outro conteúdo que possa ser acessado através dele. A CPRM, seus parceiros, colaboradores, funcionários  e representantes não podem ser responsabilizados por quaisquer danos decorrentes do uso deste site, nem por qualquer ação tomada com base nas informações nele fornecidas. As informações contidas neste site são fornecidas sem garantia de qualquer tipo, expressa ou implícita, e podem ser alteradas ou atualizadas sem aviso prévio. A CPRM não garante a ausência de vírus, worms ou outros elementos nocivos ao computador que possam causar danos ou alterações no sistema de computador, nos documentos eletrônicos ou nos arquivos do usuário deste site. Consequentemente, a CPRM não responde pelos danos que tais elementos possam causar ao usuário ou a terceiros. Da mesma forma, não se responsabiliza ou garante a disponibilidade e continuidade do acesso a este site ou que ele esteja livre de erros, correspondendo ao usuário do site, em qualquer caso, a obrigação de fornecer ferramentas adequadas para a detecção e desinfecção de programas de computador prejudiciais ou lesivos. O usuário será responsável pelos danos e prejuízos de qualquer natureza que a CPRM venha a sofrer em decorrência do descumprimento de qualquer uma das obrigações qual esteja sujeita devido as presentes condições. O usuário está ciente e aceita voluntariamente que o uso de qualquer conteúdo deste site ocorre, em qualquer caso, sob sua única e exclusiva responsabilidade.

## Licença
GNU versao 3.0 (https://www.gnu.org/licenses/gpl.txt)
>>>>>>> b8dbcbcfd80f75a22f3a4e1017b9713ea268531a
