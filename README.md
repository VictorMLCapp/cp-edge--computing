# cp-edge--computing
trabalho arduino

O código descrito é para um projeto Arduino que utiliza um sensor de luz, chamado LDR (Resistor Dependente de Luz) para monitorar os níveis de luminosidade em um ambiente.
Conforme a intensidade da luz detectada, o sistema aciona diferentes LEDs: verde indica condições normais de luminosidade, amarelo sinaliza alerta, e vermelho denota condições críticas.
Os pinos de cada componente são configurados no início do programa, e a lógica de controle opera continuamente, com leituras a cada meio segundo. 
Tivemos que aprender a mecher com buzzer, alto resistores e aprender a utilizar a luminosidade dos LEDs.
Com o programa que utilzamos, enfrentamos o problema de passar a luminosidade de um LED para o outro.
Criamos uma função onde os LEDs serão apagados de acordo com o fotoresistor. 
Quando não tem alguma intensidade luminosa o LED ficará verde, utilizando o serial para mostrar que o LED corresponde corretamente ao código apartir do código "print".
Quando o LED está verde o Buzzer não emite som e mostra a intensidade da luz emitida pelo fotoresistor, e conforme for aumentando gradativamente ele muda para o amarelo e depois ao vermelho.
Quando chega ao LED amarelo o som é emitido pausadamente.
Quando chega ao LED vermelho o som do Buzzer é emitido intensamente mudando no serial também.

Para reproduzir este projeto, você precisará dos seguintes componentes:

1. Arduino Uno ou similar - A plataforma de microcontrolador usada para controlar o sistema.
2. Sensor LDR - Para medir a intensidade da luz.
3. LEDs - Um de cada cor: verde, amarelo e vermelho.
4. Resistores - Para limitar a corrente para os LEDs e adequar a sensibilidade do LDR.
5. Buzzer - Para emitir alertas sonoros.
6. Cabos de conexão - Para interligar os componentes.
7. Protoboard - Facilita a montagem dos componentes sem solda.
8. Software Arduino IDE - Para programar o
Arduino.

