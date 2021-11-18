# TravaEletronicaArduino

Projeto criado para o componente de Objetos inteligentes conectados com intuito de desenvolver um programa usando arduino junto do protocolo firmata e Broker MQTT.

Funcionamento: assim que ligado, o circuito conta o numero de vezes em que o usuario interage com o sensor, após as interações o usuario possui opções no dashboard, 
essas opções são: abrir (onde sera comparado o numero de vezes que o usuario interagem com o sensor, com uma senha pré estabelecida), abrir sem senha (onde o arduino mandará um sinal para que a trava elétrica seja acionada sem precisar de senha) e alterar senha (onde o sistema pega o numero de vezes que o usuario interagiu com o sensor e define esse número como senha).

O projeto funciona em conjunto com um dashboard, criado no Node-Red, e protocolo firmata. Os códigos para arduino foram desenvolvidos e testados na IDE arduino.

lista de materiais:
  Arduino Uno
  Mini trava elétrica
  Módulo Relé 5V
  Fonte de alimentação 12V
  Led's
  Buzzer ativo
  ProtoBoard 400 furos
  Mósulo sensor de vibração sw420 
  Resistores 330 ohms
  
  Documentação de referência:
    Arduino IDE: https://www.arduino.cc/reference/pt/
    Biblioteca Firmata no arduino: https://www.arduino.cc/en/reference/firmata
    Node-Red: https://nodered.org/docs/
