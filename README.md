# Desafio: Roman to Integer 🏛️ ➡️ 🔢

Este repositório contém a solução para o desafio **"Roman to Integer"** disponível no [LeetCode](https://leetcode.com/problems/roman-to-integer/description/).  

O objetivo do desafio é converter um número representado em algarismos romanos para seu equivalente em números inteiros.

---

## 💡 Descrição do Desafio

Os algarismos romanos são representados por sete símbolos principais:

| Símbolo | Valor |
|---------|-------|
| I       | 1     |
| V       | 5     |
| X       | 10    |
| L       | 50    |
| C       | 100   |
| D       | 500   |
| M       | 1000  |

Por exemplo:
- O número **2** é representado como **II** (1 + 1).
- O número **12** é representado como **XII** (10 + 1 + 1).
- O número **27** é representado como **XXVII** (10 + 10 + 5 + 1 + 1).

No entanto, nem sempre os símbolos seguem do maior para o menor. Em alguns casos específicos, os números são representados por subtração:
- O número **4** é escrito como **IV** (5 - 1), e não como **IIII**.
- O número **9** é escrito como **IX** (10 - 1).
- O número **40** é escrito como **XL** (50 - 10).
- O número **90** é escrito como **XC** (100 - 10).
- O número **400** é escrito como **CD** (500 - 100).
- O número **900** é escrito como **CM** (1000 - 100).

### **Objetivo**
Dado um numeral romano válido, converter o mesmo em um número inteiro.

---

## 🛠️ Exemplos

### Exemplo 1:
- **Input**: `s = "III"`  
- **Output**: `3`  
- **Explicação**: `III = 3`.

### Exemplo 2:
- **Input**: `s = "LVIII"`  
- **Output**: `58`  
- **Explicação**: `L = 50, V = 5, III = 3`.

### Exemplo 3:
- **Input**: `s = "MCMXCIV"`  
- **Output**: `1994`  
- **Explicação**:  
  `M = 1000`,  
  `CM = 900`,  
  `XC = 90`,  
  `IV = 4`.  
  Total: `1000 + 900 + 90 + 4 = 1994`.

---

## 🔒 Restrições

- `1 <= s.length <= 15`
- `s` contém apenas os caracteres: `'I', 'V', 'X', 'L', 'C', 'D', 'M'`.
- É garantido que `s` é um numeral romano válido no intervalo `[1, 3999]`.

---
