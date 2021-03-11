
# FULL-CYCLE-2.0 - Docker - DESAFIO 1 

Este projeto cria um container com uma aplicação em GO que exibe o seguinte resultado no STDOUT:do ``Code.education Rocks!``

## Para executar a imagem carregada no Docker Hub

``docker run martinharano/codeedu``

## Comando utilizado para construir imagem:

``docker build -t martinharano/codeedu -f ./codeEduRocks/Dockerfile.prod ./codeEduRocks/`` 

## Comando utilizado para carregar imagem no Docker Hub
``docker push martinharano/codeedu``