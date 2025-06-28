# Projeto PE&A – Sistema de Gestão de Objetos Perdidos (Distribuído)

Este projeto foi desenvolvido no âmbito das unidades curriculares **Projeto de Tecnologias de Rede (PTR)** e **Projeto de Tecnologias de Informação (PTI)** da Licenciatura em Tecnologias de Informação (FCUL, 2023/2024).

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
- Desenvolvimento **frontend** (interfaces com autenticação, registo de objetos, e leilões)
- Implementação do **backend em Laravel**, incluindo APIs REST e autenticação com Laravel Sanctum
- Criação, configuração e administração da **base de dados MongoDB** (cluster com redundância)

## Créditos e equipa

Este projeto foi realizado em grupo no âmbito das unidades curriculares **Projeto de Tecnologias de Rede (PTR)** e **Projeto de Tecnologias de Informação (PTI)** da FCUL – 2023/2024.

**Equipa:**
- Mariana Valente (GitHub: [@mariannerv](https://github.com/mariannerv))
- Gabriel Cordeiro (GitHub: [@gabrielprojeto01](https://github.com/gabrielprojeto01))
- Tomás Rodrigues (GitHub: [@tomasrodrigues01](https://github.com/tomasrodrigues01))
- Diogo Forte (GitHub: [@dramataparty](https://github.com/dramataparty))
- Tiago Pereira (este repositório)

Este repositório representa uma versão pessoal e documentada para efeitos de portefólio, com base no trabalho desenvolvido em grupo.
