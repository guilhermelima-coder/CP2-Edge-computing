# Projeto Vinheria Agnello segunda fase.

A vinheria Agnello nos contratou para desenvolver um sistema de monitoramento a ser instalado no ambiente em que os vinhos são armazenados. Nós apresentamos a primeira parte do projeto para os proprietários da Vinheria e eles nós passaram uma segunda fase do projeto com os seguintes novos requisitos:
Precisamos medir a temperatura e umidade do ambiente, para isso vocês escolheram o sensor integrado DHT11. Os proprietários querem ver os valores de temperatura, umidade e luminosidade de alguma forma, nós usamos um display LCD para mostrar esses valores. Os sinais de alerta foram bem aceitos, e os proprietários querem estender essa funcionalidade para temperatura e umidade, portanto, além de sinalizar com os LEDs e o Buzzer a luminosidade, nós também precisamos indicar quando a temperatura e/ou a umidade estiverem em níveis críticos.

Em uma vinheria o ambiente é um fator determinante para a produção de vinhos tendo algumas condições principais a serem seguidas como por exemplo, A iluminação deve ser muito suave. Os vinhos agradecem lugares com penumbra, especialmente os brancos e espumantes, que sofrem mais com o contato com a luz. Raios ultravioletas, por exemplo, causam alterações nos compostos orgânicos, iniciando reações químicas que podem gerar resultados desagradáveis. Outra condição importante é O calor excessivo rapidamente termina com a vida do vinho e as flutuações térmicas de mais de 3°C podem causar o aparecimento de aromas indesejados. A situação perfeita seria que ficassem constantemente sob uma temperatura de cerca de 13°C (segundo estudo de Alexander Pandell, PhD, Universidade da Califórnia). Podemos destacar a umidade como mais um fator determinante, A falta de umidade pode levar, por exemplo, ao ressecamento do vedante, provocando uma má vedação da garrafa, com risco de oxidação do líquido. Já o excesso de umidade pode danificar os rótulos, bem como promover a proliferação de fungos. O ideal é que seja próxima a 70% (com variação em torno de 60% a 80%).

Em lista esses foram os principais requisitos apresentados:

1. Enquanto o ambiente estiver escuro, o LED Verde deve ficar aceso;
2. Enquanto o ambiente estiver a meia luz, o LED amarelo deve ficar aceso e mensagem de “Ambiente a meia luz” deve ser mostrado no Display;
3. Enquanto o ambiente estiver totalmente iluminado, o LED vermelho deve ficar aceso e a mensagem “Ambiente muito claro” deve ser mostrado no display;
4. Enquanto o ambiente estiver totalmente iluminado, o Buzzer deve ficar ligado continuamente;
5. Enquanto o ambiente estiver com uma temperatura entre 10°C e 15°C, o Display deve informar “Temperatura OK” e também mostrar o valor da temperatura;
6. Enquanto o ambiente estiver com uma umidade entre 50% e 70%, o Display deve informar “Umidade OK”, e também mostrar o valor da umidade;
7. Os valores apresentados no display devem ser a média de pelo menos 5 leituras dos sensores, e os valores devem ser apresentados a cada 5 segundos;
8. Enquanto a temperatura estiver fora da faixa ideal, o LED Amarelo deve ficar aceso e o Buzzer deve ligar continuamente;
9. Enquanto a temperatura estiver fora da faixa ideal, o Display deve informar “Temp. Alta”, para valores acima de 15°C e também mostrar a temperatura;
10. Enquanto a temperatura estiver fora da faixa ideal, o Display deve informar “Temp. Baixa”, para valores abaixo de 10°C e também mostrar a temperatura;
11. Enquanto a umidade estiver fora da faixa ideal, o LED Vermelho deve ficar aceso e o Buzzer deve ligar continuamente;
12.Enquanto a umidade estiver fora da faixa ideal, o Display deve informar “Umidade. Alta”, para valores acima de 70% e também mostrar a umidade;
13.Enquanto a umidade estiver fora da faixa ideal, o Display deve informar “Umidade. Baixa”, para valores abaixo de 50% e também mostrar a umidade;

Para suprir essas necessidades iniciamos nossos testes do projeto montando um circuito em um simulador de Arduino (Tikercard ou wokwi), onde fizemos as devidas conexões dos componentes, elaboramos um código para que cada componente executasse sua devida função. Com o código em completo funcionamento passando para a montagem no Arduino onde usamos, um Arduino Uno, uma protoboard, LEDs, resistores, jumpers, um buzzer, um sensor LDR, um sensor DHT11, um display LCD. Por fim, operamos o Arduino IDE para executar nosso codigo na linguagem C e colocar o projeto em atividade.
