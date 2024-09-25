
# Atividade 2: Função Hash

João Pedro Nagib Jorge Barbieri – 22.120.049-6 

Gabriel Brito Schanz – 22.119.010-1 

Lucas Podmanicki Fernandes - 22.121.007-3 

Leonardo Barrionuevo Candido – 22.121.034-7



Esta atividade tem o intuito de verificar a autenticidade de diversas frases fornecidas através do cálculo dos hashes **SHA256** e **MD5**. Para cada frase, os hashes foram calculados utilizando a biblioteca `hashlib` do Python e, em seguida, comparados com os valores esperados fornecidos.

## O processo consiste em:

1. **Entrada das Frases**: As frases foram processadas sem as aspas, conforme solicitado, para o cálculo dos hashes.
   
2. **Cálculo dos Hashes**: Cada frase foi convertida em um hash **SHA256** e um hash **MD5**, utilizando a codificação `utf-8` para garantir a consistência do resultado.

3. **Comparação dos Resultados**: Os hashes calculados foram comparados com os hashes fornecidos. Se ambos os hashes (**SHA256** e **MD5**) corresponderam aos valores esperados, o resultado foi marcado como "correto". Caso contrário, foi marcado como "incorreto".

As frases que obtiveram a combinação correta de hashes são consideradas verdadeiras, de acordo com os valores de referência. Já as frases com hashes incorretos não correspondem aos valores fornecidos e, portanto, não são consideradas verdadeiras.

## Finalidade

Este relatório serve como um instrumento de validação para garantir a integridade das informações fornecidas.

## Código-Fonte

O código-fonte utilizado para este processo está disponível no repositório GitHub, no seguinte link:

[Link para o código-fonte no GitHub](https://github.com/barbieriraketti/Hash/blob/main/main.py)
