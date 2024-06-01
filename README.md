# RETIRAR-DIGITOS.

O código usa o operador módulo (%) para isolar o último dígito e a divisão por 10 para removê-lo.

**Exemplo:**

1. `numero = 350`
2. `digito_retirado = 350 % 10 = 0` (resto da divisão por 10)
3. `cout << 0` (imprime o dígito 0)

Para obter os demais dígitos, você pode repetir o processo após dividir `numero` por 10 dentro de um loop. 
