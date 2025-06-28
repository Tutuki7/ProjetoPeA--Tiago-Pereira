# Projeto PE&A – Sistema de Gestão de Objetos Perdidos (Distribuído)

Este projeto foi desenvolvido no âmbito da unidade curricular "Projeto de Tecnologias de Rede" e "Projeto de Tecnologias de Informação" da Licenciatura em Tecnologias de Informação (FCUL, 2023/2024).

## Objetivo
Criar uma aplicação web distribuída para o registo, cruzamento e leilão de objetos perdidos/encontrados.

## Tecnologias principais
- Laravel (backend e API REST)
- MongoDB (bases de dados replicadas)
- HAProxy + Keepalived (balanceamento de carga com failover)
- Apache2 + TLS (HTTPS via Let's Encrypt)
- Scripts Bash para escalabilidade automática e verificação de estado
- APIs externas: PayPal (pagamentos) e TomTom (mapas)
- Autenticação com Laravel Sanctum (Bearer tokens)

## Contributo pessoal
- Desenvolvimento backend em Laravel (autenticação, licitações, cruzamento de objetos)
- Configuração de autenticação e permissões
- Firewalls externas e internas (iptables)
- Documentação técnica e testes de segurança

> Projeto realizado em equipa (5 membros). Esta versão representa o meu contributo técnico e serve como portefólio pessoal.
