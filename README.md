# conversao-distancia
Testando conexão com Docker e Linux
Atividade desafio 1 - Docker

Informações do desafio

Cenário
A empresa "FakeShop" está em um processo de modernização de suas aplicações e decidiu adotar contêineres para padronizar o ambiente e melhorar a escalabilidade. Você faz parte dessa equipe de modernização e a sua primeira tarefa é criar um ambiente Docker para uma aplicação demo que utiliza a mesma estrutura e linguagem da aplicação de e-commerce. A aplicação é responsável por converter métricas de distância (como metros para quilômetros e milhas para metros) e foi desenvolvida em Python. Então como primeiro objetivo, você deve utilizar Docker para executar esse piloto.


Tarefa Prática

1. Configuração do Ambiente
Faça um fork do repositório original e clone o novo repositório da aplicação "Conversão de Distâncias" no GitHub: https://github.com/KubeDev/conversao-distancia.
Crie um Dockerfile que atenda aos requisitos do projeto.

![Fork do repositório](https://github.com/GilsonRavaiani/conversao-distancia/blob/main/images/01-Fork.png?raw=true)

**FIGURA 01** Fork do repositório

2. Criação e Teste do Contêiner

Gere uma imagem Docker a partir do Dockerfile criado.

![Docker com imagem](https://github.com/GilsonRavaiani/conversao-distancia/blob/main/images/02-Docker.png?raw=true)

**FIGURA 02** Docker com imagem

Execute um contêiner a partir da imagem para garantir que a aplicação esteja acessível na porta 5000.
Realize testes básicos na aplicação para verificar a funcionalidade de conversão de métricas.

![Acesso porta 5000 e aplicação funcionando](https://github.com/GilsonRavaiani/conversao-distancia/blob/main/images/03-porta_5000.png?raw=true)

**FIGURA 03** Acesso porta 5000 e aplicação funcionando

Implantando k8s