## Flows Nifi

Alguns exemplos de workflows NiFi.

Na lista possui exemplos simples de captação de Logs até Streaming de Dados.

Quem tiver interesse em testar os Flows.

Segue abaixo o container Docker que eu uso para meus treinos e estudos.

#### NIFI Docker 
docker run --name nifi \
  -v ~/nifi/saida:/opt/nifi/nifi-current/saida \
  -v ~/nifi/entrada:/opt/nifi/nifi-current/entrada \
  -p 8443:8443 \
  -d \
  -e SINGLE_USER_CREDENTIALS_USERNAME=admin \
  -e SINGLE_USER_CREDENTIALS_PASSWORD=ctsBtRBKHRAx69EqUghvvgEvjnaLjFEB \
  apache/nifi:latest

#### Para acessar o NIFI
 https://localhost:8443/nifi/ 
