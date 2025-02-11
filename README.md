Projeto de arquitetura MQTT 

Desenvolvido na aula de desenvolvimento de sistemas na escola SESI Caçapava 


Para implementar o MQTT em Python, primeiro você precisa instalar a biblioteca cliente com a qual escolheu trabalhar. Utilizando a biblioteca Paho a instalação funciona assim: 


No terminal ou prompt de comando utilize o seguinte comando: 


pip install paho-mqtt

Após concluído o download, é necessário importar no código.

Para importar a biblioteca paho-mqtt no Python, basta adicionar esta linha no seu código de um arquivo .py: 

import paho.mqtt.client as mqtt


Crie o arquivo subscriber.py e adicione o código, e faça o mesmo com o arquivo publisher.py

Para testar digite no terminal: python subscriber.py e após digite: python publisher.py

No terminal do publisher escreva a mensagem que desejar, e no terminal do Subscriber, a mensagem será exibida quando enviada pelo Publisher.

Se a mensagem aparecer corretamente, o ambiente MQTT está funcionando.


Nessa atividade realizada em sala, foi preciso testar em um web site, o Google colab, então instalamos a biblioteca e inserimos o código na parte determinada, e foi realizado o teste, no qual funcionou corretamente.
