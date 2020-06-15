# Hardware_Super_Truck
 Exemplo de hardware para desenvolvimento da solução IoT para a pedaleira do pânico na plataforma Super Truck.


Aqui está uma das várias soluções de IoT para funcionamento da pedaleira.
Neste repositorio está uma solução que utiliza uma Rasoberry Pi e o protocolo de comunicação MQTT.
O código é bem simples e exemplica apenas como contabilizar os acionamentos da pedaleira dentro de um tempo específico sem que a operação habitual de acionamentos de freio e acelerador seja interpretada como perigo.

Outros hardware como arduíno, minicomputadores e microcrocontroladores podem ser utilizados para essa solução.
A respeito do Raspberry, foi utilizada a plataforma Codesys para transformar o computador em um controlador lógico programável, onde os sensores são conectados através da GPIO.