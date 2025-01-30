# ServeRest-API
Teste de API Rest do manual a CI/CD

## O que é
Este repositório foi criado Teste de API Rest.

## Tecnologias utilizadas
- Postman versão web
- node version v20.17.0
- newman v6.2.1
- newman-reporter-html
## Documentações
Analise Técnica: Analise/
Doc da API: Consulte Swagger
## Como instalar o ambiente
- Primeiro: instale o node em seu computador baixe aqui
- Segundo: realize a instalação do newman de forma global baixe aqui a dependência
npm install -g newman
- Terceiro: realize a instalação da dependência dos relatórios (opcional) newman-reporter-html
npm install -g newman-reporter-html
## Como rodar os testes
## Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os teste de forma manual ou automatizada
## Pelo newman
- Abra o console de preferência
- Execute a seguinte linha de comando para rodar os testes
- newman run ServeRest.postman_collection.json -e ServeRest.postman_environment.json -r cli
- Execute os teste com relatório
- newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
## Report
Se você optou por rodar os teste com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta newman que foi criada no local em que os arquivos de collection e environment se encontram.


