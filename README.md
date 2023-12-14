# Get_Current_INA


Para implementar a leitura de voltagem e corrente de uma bateria utilizando o Arduino Nano, INA219 (sensor de corrente e tensão) e um display OLED I2C, você pode seguir os seguintes passos. Primeiramente, conecte o INA219 e o display OLED ao Arduino Nano. Em seguida, instale a biblioteca INA219 e a biblioteca Adafruit_SSD1306 para o display OLED no Arduino IDE. No código, inicialize o INA219 e o display OLED, configurando os parâmetros necessários, como a faixa de corrente e o ganho. Dentro do loop principal, leia os valores de corrente e tensão utilizando as funções disponíveis na biblioteca do INA219 e exiba esses valores no display OLED. Isso permitirá que você monitore em tempo real a voltagem e a corrente da bateria. Certifique-se de ajustar os valores de calibração conforme necessário para obter medições precisas. Essa implementação proporcionará uma solução eficiente para monitorar a condição da bateria usando um Arduino Nano, INA219 e um display OLED I2C.


<img src="/Users/viniciusrosa/Desktop/Vinicius/Facul/2023.2/Ubiquos/sistema.jpg">
