# AzureBootCamp2018
Step By Step - Azure Bootcamp 2018 - MVC + Docker

### Verificar instalação do Docker

```
docker --version
```

Instalação: https://store.docker.com/search?type=edition&offering=community

### Rodar um Container Linux no Windows

```
docker run -t felipecrestani/hab
```

### Verificar versão do .Net Core instalado

```
dotnet --version
```

Instalação: https://www.microsoft.com/net/learn/get-started/windows


### Criar um novo site MVC ASP.NET Core

Criar uma nova pasta do site e executar o comando abaixo:

```
dotnet new mvc --auth Individual
```

--auth Individual cria o site com autenticação usando Microsoft Identity

Na pasta raiz do site MVC executar:

```
dotnet run
```

Acessar a porta http://localhost:5000


# Docker

Dockerfile - Arquivo de execução de Script do Docker
Imagem - Imagem docker compilada
Registro - Repositório de imagens
Container - Imagem docker em execução




