# dockerized-irpf-2018

Atualizado para o IRPF 2018

# dockerized-irpf-2017
Dockerized Brazilian income tax declaration app - 2107

*Apenas para Unix*

Para utilizar o IRPF 2017 basta executa o script *dockerized-irpf-2017* localmente (do repositorio GIT).
Ele irá realizar o build da imagem e iniciar o container automaticamente.

Infelizmente não é possível automatizar a instalação do programa de declaração de imposto de renda. Então a primeira execução do container pedirá que você para você instalar o programa da declaração do imposto de renda. Simplesmente deixe toda as opções **com o valor default** e termine a instalação clicando em "Avançar".

As execuções seguintes deste container não vão mais pedir a instalação do programa.

A imagem no Docker Store está hospedada aqui: https://store.docker.com/community/images/eszanon/dockerized-irpf-2017
