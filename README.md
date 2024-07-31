# Aplicações em Docker Compose: Zabbix, Grafana e MySQL

Este projeto configura um ambiente integrado utilizando Docker Compose para rodar contêineres do Zabbix, Grafana e MySQL. O Zabbix é utilizado para monitoramento, o Grafana para visualização de dados e o MySQL como banco de dados.

## Pré-requisitos

- Docker
- Docker Compose

## Estrutura do Projeto

- `docker-compose.yml`: Arquivo de configuração do Docker Compose para orquestrar os contêineres.

## Serviços

### Zabbix

O Zabbix é uma plataforma de monitoramento que permite coletar e analisar dados de desempenho de diversos sistemas.

### Grafana

O Grafana é uma ferramenta de visualização de dados que se integra ao Zabbix para fornecer dashboards interativos.

### MySQL

O MySQL é um sistema de gerenciamento de banco de dados relacional utilizado pelo Zabbix para armazenar dados.

## Instalação

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    cd seu-repositorio
    ```

2. Execute o Docker Compose:
    ```bash
    docker compose up -d
    ```

## Configuração do Plugin do Zabbix no Grafana

1. Acesse o Grafana através do navegador:
    ```
    http://localhost:3000
    ```

2. Faça login com as credenciais padrão (usuário: `admin`, senha: `admin`).

3. Navegue até a seção de plugins e instale o plugin do Zabbix.

4. Configure o plugin do Zabbix com as informações do seu servidor Zabbix.

## Uso

Após a configuração, você poderá visualizar os dados de monitoramento do Zabbix diretamente no Grafana.

## Contribuição

Sinta-se à vontade para abrir issues e pull requests para melhorias.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
