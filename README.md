# Hash
Atividade 2: Função Hash

Esta atividade tem o intuito de verificar a autenticidade de diversas frases fornecidas através do cálculo dos hashes SHA256 e MD5. Para cada frase, os hashes foram calculados utilizando a biblioteca hashlib do Python e, em seguida, comparados com os valores esperados fornecidos.

O processo consiste em:

Entrada das Frases: As frases foram processadas sem as aspas, conforme solicitado, para o cálculo dos hashes.
Cálculo dos Hashes: Cada frase foi convertida em um hash SHA256 e um hash MD5, utilizando a codificação utf-8 para garantir a consistência do resultado.
Comparação dos Resultados: Os hashes calculados foram comparados com os hashes fornecidos. Se ambos os hashes (SHA256 e MD5) corresponderam aos valores esperados, o resultado foi marcado como "correto". Caso contrário, foi marcado como "incorreto".
As frases que obtiveram a combinação correta de hashes são consideradas verdadeiras, de acordo com os valores de referência. Já as frases com hashes incorretos não correspondem aos valores fornecidos e, portanto, não são consideradas verdadeiras.

Esse relatório serve como um instrumento de validação para garantir a integridade das informações fornecidas. O código-fonte utilizado para este processo está disponível no repositório GitHub, cujo link pode ser encontrado abaixo.
