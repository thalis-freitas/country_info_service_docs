# CountryInfoService

Este repositório documenta o serviço CountryInfoService, uma API SOAP para obter informações sobre países. O serviço permite realizar consultas sobre continentes, moedas, idiomas, informações completas de um país, etc. Foi utilizada a ferramenta Bruno para documentar, organizar e testar as requisições desse serviço.

## Ferramenta Utilizada: Bruno

Bruno é uma ferramenta útil para desenvolvimento e teste de APIs. Tem uma interface intuitiva, é fácil organizar coleções de endpoints, adicionar variáveis de ambiente e realizar testes de integração.

### Como usar o Bruno
Para utilizar as requisições armazenadas neste repositório com o Bruno, siga os passos abaixo:

1. **Instalação do Bruno:**
  Acesse o [site oficial do Bruno](https://www.usebruno.com/downloads), baixe e instale a versão mais recente compatível com seu sistema operacional.

2. **Clone este repositório:**
   ```bash
   git clone git@github.com:thalis-freitas/country_info_service_docs.git
   ```
   
3. **Acessar requisições com o Bruno**:
Abra o Bruno e direcione-o para a pasta clonada, ele irá carregar todos os arquivos `.bru` disponíveis. Você agora poderá visualizar, editar e enviar requisições diretamente pelo Bruno.

### Configurando o Ambiente no Bruno

Para facilitar os testes, está configurado o ambiente `Default` no Bruno, contendo variáveis comuns que são utilizadas em todas as requisições. Certifique-se de utilizar o ambiente `Default` para uma experiência de teste mais simples e organizada.

### Variáveis de Ambiente

As variáveis de ambiente configuradas no ambiente `Default` são:

- `BASE_URL`: URL base do serviço

- `SERVICE_PATH`: Caminho do serviço

- `ENVELOPE_START`: Início do envelope SOAP

- `ENVELOPE_END`: Final do envelope SOAP

- `NAMESPACE`: Namespace utilizado nos métodos SOAP
