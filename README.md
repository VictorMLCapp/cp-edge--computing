# cp-edge--computing
trabalho arduino

Tivemos que aprender a mecher com buzzer, alto resistores e aprender a utilizar a luminosidade dos LEDs
Com o programa que utilzamos, enfrentamos o problema de passar a luminosidade de um LED para o outro
Criamos uma função onde os LEDs serão apagados de acordo com o fotoresistor. 
Quando não tem alguma intensidade luminosa o LED ficará verde, utilizando o serial para mostrar que o LED corresponde corretamente ao código apartir do código "print".
Quando o LED está verde o Buzzer não emite som e mostra a intensidade da luz emitida pelo fotoresistor, e conforme for aumentando gradativamente ele muda para o amarelo e depois ao vermelho gradativamente.
Quando chega ao LED amarelo o som é emitido pausadamente.
Quando chega ao LED vermelho o som do Buzzer é emitido intensamente mudando no serial também.
