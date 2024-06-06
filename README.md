# feedback-system
Um sistema de feedback para correção da imagem de um padrão de interferencia.

O codigo funciona da seguinte forma:

1 - Obtém dados do shot atual

2 - Corta uma região específica da imagem definida pelas coordenadas 

3 - Calcula a média das intensidades das linhas da região cortada e exibe a curva média de intensidades.

4 - Encontra picos locais na curva média de intensidades

5 - Calcula o valor de Dvoltage com base na distância entre picos.Se a coordenada de referência for diferente da coordenada do máximo, calcula o deslocamento e ajusta voltagevalue de acordo e aplica condições adicionais para ajustar voltagevalue caso exceda certos limites.
