# CountryInfoService

Este repositório documenta o serviço CountryInfoService, uma API SOAP para obter informações sobre países. O serviço permite realizar consultas sobre continentes, moedas, idiomas, informações completas de um país, etc. Foi utilizada a ferramenta Bruno para documentar, organizar e testar as requisições desse serviço.

## Ferramenta Utilizada: Bruno

Bruno é uma ferramenta útil para desenvolvimento e teste de APIs, incluindo serviços SOAP. Tem uma interface intuitiva, é fácil organizar coleções de endpoints, adicionar variáveis de ambiente e realizar testes de integração.

### Instalação do Bruno

Acesse o [site oficial do Bruno](https://www.usebruno.com/downloads), baixe e instale a versão mais recente compatível com seu sistema operacional.

### Configurando o Ambiente no Bruno

Para facilitar o teste dos endpoints, está configurado o ambiente `Default` no Bruno, contendo variáveis comuns que são utilizadas em todas as requisições. Certifique-se de utilizar o ambiente `Default` para uma experiência de teste mais simples e organizada.

### Variáveis de Ambiente

As variáveis de ambiente configuradas no ambiente `Default` são:

- `BASE_URL`: URL base do serviço

- `SERVICE_PATH`: Caminho do serviço

- `ENVELOPE_START`: Início do envelope SOAP

- `ENVELOPE_END`: Final do envelope SOAP

- `NAMESPACE`: Namespace utilizado nos métodos SOAP
