# An-lise-Turbina-E-lica
Contexto
Em turbinas eólicas, os sistemas Scada medem e salvam dados como velocidade do vento, direção do vento, energia gerada, etc., em intervalos de 10 minutos. Este arquivo foi retirado do sistema scada de uma turbina eólica que está funcionando e gerando energia na Turquia.

Contente
Os dados no arquivo são:

Data/Hora (para intervalos de 10 minutos)
LV ActivePower (kW): A potência gerada pela turbina naquele momento
Velocidade do vento (m/s): A velocidade do vento na altura do cubo da turbina (a velocidade do vento que a turbina usa para geração de eletricidade)
Curva_de_potência teórica (KWh): Os valores teóricos de potência que a turbina gera com a velocidade do vento fornecida pelo fabricante da turbina
Direção do Vento (°): A direção do vento na altura do cubo da turbina (as turbinas eólicas giram nesta direção automaticamente)

Logica
1 - Importando Bibliotecas
2 - Lendo o arquivo
3 - Plotando os dados em um gráfico - Real
    Plotando os dados em um gráfico - Teórica
4 - Criando "limites aceitáveis"
5 - Adicionando lista "dentro_limite" ao dataframe:
6 - Plotando novamente o gráfico:
