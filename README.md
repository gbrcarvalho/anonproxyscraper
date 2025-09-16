# Varredor de Proxies Anônimos - Aplicação CLI

Um varredor de proxies anônimos desenvolvido com Scrapy no curso de Especialização em Automações Python da DevAprender.

Um web scraper simples escrito em Python, que coleta dados de proxies públicos do site us-proxy.org usando o framework Scrapy.

## Funcionalidades

- **Web Scraping** - Extrai dados de forma automatizada
- **Múltiplos Campos** - Coleta IP, porta, país, anonimato e outras informações
- **Estrutura Organizada** - Dados estruturados em formato JSON
- **Framework Scrapy** - Utiliza o framework Scrapy para web scraping
- **Dados Atualizados** - Obtém informações em tempo real do site us-proxy.org

## Dados Coletados

- **Endereço IP** - Endereço IP do servidor proxy
- **Porta** - Número da porta do proxy
- **Código** - Código do país
- **País** - Nome do país do servidor
- **Anonimato** - Nível de anonimato (Elite, Anonymous, Transparent)
- **Google** - Compatibilidade com serviços Google
- **HTTPS** - Suporte para conexões HTTPS
- **Última Verificação** - Timestamp da última verificação do proxy

## Requisitos

- Python 3.11
- Framework Scrapy

## Instalação para sistemas Windows

1. Criar ambiente virtual:
   ```
   > virtualenv venv -p Unidade:\Caminho\Para\o\Python_3_11\python.exe
   ```

2. Ativar ambiente virtual:
   ```
   > .\venv\Scripts\activate
   ```

3. Instalar o Scrapy:
   ```
   > pip install scrapy
   ```

## Como executar

1. Entrar na pasta do projeto:
   ```
   > cd .\anon_proxy_scraper\
   ```

- Obter arquivo .csv na saída:
   ```
   > scrapy crawl us_proxy -o proxies.csv
   ```

- Obter arquivo .json na saída:
   ```
   > scrapy crawl us_proxy -o proxies.json
   ```

- Obter arquivo .xml na saída:
   ```
   > scrapy crawl us_proxy -o proxies.xml
   ```

## Licença

Este é um projeto educacional desenvolvido para demonstrar técnicas de web scraping com Python e Scrapy. Sinta-se livre para usar e modificar conforme necessário.

**Nota**: Respeite sempre os termos de uso dos sites ao realizar web scraping e utilize os dados de forma ética e responsável.
