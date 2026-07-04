# Hospedagem de Site Estático na AWS com S3 e CloudFront

Este projeto demonstra a implementação prática de uma infraestrutura em nuvem na AWS para hospedagem de um site estático, aplicando conceitos de alta disponibilidade, segurança e otimização de custos.

## Arquitetura do Projeto

O projeto foi estruturado seguindo as melhores práticas recomendadas pela AWS:

* Amazon S3: Utilizado para o armazenamento seguro dos arquivos estáticos do site (`index.html`), mantendo o balde (bucket) totalmente privado, sem exposição direta à internet.
* Amazon CloudFront: Configurado como CDN (Content Delivery Network) para distribuir o conteúdo globalmente com baixa latência.
* Segurança (OAC & HTTPS): Utilizei o *Origin Access Control* (OAC) para permitir que apenas o CloudFront acesse os arquivos do S3, além de forçar o redirecionamento de todo o tráfego de HTTP para HTTPS.

## Tecnologias e Ferramentas

* Cloud: Amazon Web Services (S3, CloudFront, IAM)
* Frontend: HTML5 / CSS3
* Controle de Versão: Git e GitHub

## Link do Projeto
Você pode acessar o site resultante deste projeto rodando na infraestrutura da AWS através do link: 
d2zeodqorcog6u.cloudfront.net
