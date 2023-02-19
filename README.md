# Nginx Proxy Manager

O Nginx Proxy Manager (NPM) é um container Docker para gestão de Proxys feitos através do NGINX através de uma interface Web.
Home do projeto: https://nginxproxymanager.com/

O NPM servirá como Proxy Central das aplicações corporativas do Governo do Estado do Acre. Reduzindo a necessidade de distribuição de IP's externos entre aplicações.

Também é possível certificar sites através da interface da ferramenta. Tanto usando Let's Encrypt como outros certificados.

## Utilização

A interface de gerenciamento pode ser acessada através do endereço: http://npm.ac.gov.br:81 (somente rede interna)

O usuário de acesso está armazenado na documentação do projeto **SRVPRD095 - Nginx Proxy Manager.docx** (necessário senha para abrir);

## Instalação e Configuração

Faça modificações no arquivo **docker-compose.yml** e clone o projeto no servidor de destino. Altere as configurações de acordo com a necessidade.

