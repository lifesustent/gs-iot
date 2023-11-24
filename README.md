# SPRINT 04 - ESR1

[Repositório Github](https://github.com/lifesustent/gs-iot).

Apresentação do projeto disponível no [Youtube]().

Projeto no [Wokwi](https://wokwi.com/projects/382318763288964097).

## Alunos

- Fabrizio El Ajouri Romano – **RM 550410**
- Guilherme Jacob Soares da Costa – **RM 84581**

# Resumo

Este projeto emprega o sensor MQ135 para medição da qualidade do ar, a biblioteca DHT para sensores ESPx para registrar a umidade e a temperatura. Além disso, utiliza um buzzer para alertas sonoros e se integra ao sistema MQTT por meio do PubSubClient para transmitir dados.

## Objetivo
O objetivo principal é monitorar a qualidade do ar, umidade e temperatura para fornecer informações cruciais para insights médicos e alertas importantes ao usuário final. Esses dados são encaminhados para um sistema MQTT que os utiliza na geração de insights médicos e para acionar alertas.

## Componentes Utilizados
Sensor de qualidade do ar MQ135
Biblioteca DHT para sensores ESPx
Buzzer para alertas sonoros
PubSubClient para comunicação MQTT
LiquidCrystal I2C para exibição de dados

## Funcionamento
O sistema realiza as seguintes operações:

- Coleta os dados de qualidade do ar, umidade e temperatura através dos sensores MQ135 e DHT.
- Converte esses dados em um formato compatível para transmissão.
- Utiliza o PubSubClient para estabelecer a comunicação MQTT e envia os dados para um servidor MQTT.
- O servidor MQTT processa os dados, gerando insights médicos e acionando alertas conforme necessário para o usuário final.

## Implementação
Para executar o projeto:

- Configure os pinos e as conexões de hardware para o sensor MQ135, o sensor DHT e o buzzer.
- Garanta que as bibliotecas necessárias estejam instaladas, como a DHT para ESPx, PubSubClient e LiquidCrystal I2C.
- Carregue o código para o dispositivo.
- Verifique a transmissão dos dados nos canais MQTT para garantir que os dados estão sendo transmitidos corretamente.
- Monitore os insights médicos e os alertas gerados a partir dos dados coletados.

## Observação
Para mais detalhes sobre a implementação e a configuração do projeto, consulte o repositório do projeto no github.
