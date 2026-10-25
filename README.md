# Olá, eu sou o João 👋

**Desenvolvedor de Software** · Sistemas, integrações e infraestrutura · Estância, SE

Programo desde 2017 e, desde 2022, desenvolvo sistemas para o mercado financeiro. Cuido do sistema inteiro, do código ao servidor: backend, banco de dados, deploy, DNS, Cloudflare e correção de problemas em produção.

Gosto de resolver problemas e não largo um até resolver. Já aprendi C++ para fazer uma integração funcionar, desmontei código ofuscado para entender como funcionava e reescrevi meus próprios sistemas até ficarem sólidos.

## O sistema que construí, em números

O **SistemaBT**, plataforma de assinaturas que criei e mantenho em produção, já:

| O que | Quanto |
| --- | --- |
| 💰 Processou em vendas | cerca de **R$ 1 milhão** |
| 🛒 Processou em compras | **9 mil+** |
| 🌐 Atendeu em 12 meses | **11,3 milhões** de requisições, de usuários em **57 países** |
| 👥 Chegou a | cerca de **1.000** assinantes ao mesmo tempo |

## Tecnologias

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![MQL5](https://img.shields.io/badge/MQL5-1A5FB4?style=flat)

**Backend e dados**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

**Infraestrutura**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## Projetos

> Os códigos são privados, porque são sistemas de clientes em produção. Abaixo, o que cada um faz e como foi construído.

### SistemaBT · plataforma de assinaturas e acessos
`Python` `FastAPI` `PostgreSQL` `React` `Nginx` `systemd`

Recebe as vendas por webhook (Kiwify, Lastlink, Cakto) e libera ou corta o acesso automaticamente no Discord, no Telegram, no TradingView e nos indicadores do MetaTrader 5. A versão 2, em produção, roda em 9 processos isolados, com cerca de 990 testes automatizados.

### ADT Copilot · fluxo de ordens em tempo real
`TypeScript` `Node.js` `React` `Redis` `NATS` `Rust/WASM`

Plataforma web com footprint, heatmap e boleta integrada à corretora Exness. Recebe dados de MetaTrader 5, Binance, BingX e Bookmap por WebSocket. Nova versão em construção com Rust, Go e WebGL2.

### GerenciaBT · indicador para MetaTrader 5
`MQL5`

17 módulos de análise de volume, compilados em 4 versões otimizadas por processador (x64, AVX, AVX2 e AVX-512). Licença com criptografia, trava por hardware e atualização automática.

### ObProfit · ponte de cotações para corretoras sem API
`C++` `Qt` `C#` `WPF` `Selenium`

Captura cotações de corretoras que não oferecem API e as entrega ao MetaTrader e a um gráfico próprio. O orquestrador é em C++ com Qt, com servidor TCP e protocolo de comandos próprio.

## Trajetória

- **2017:** primeiros trabalhos pagos, com plugins em Java para servidores de Minecraft
- **2022:** engenharia reversa de uma ferramenta de volume e meu primeiro serviço de dados de mercado
- **2023:** ObProfit em C++, C# e MQL5, e os primeiros indicadores
- **2024–2025:** GerenciaBT e o SistemaBT em produção
- **2026:** ADT Copilot e reescritas com arquitetura própria

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jvcardosooo)
[![E-mail](https://img.shields.io/badge/E--mail-contatojoaocardosoo%40icloud.com-555555?style=flat&logo=icloud&logoColor=white)](mailto:contatojoaocardosoo@icloud.com)
