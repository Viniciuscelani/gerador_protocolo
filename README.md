# Gerador de Números de Protocolo

Este projeto é um código simples e de fácil implementação, desenvolvido para gerar números de protocolo únicos sem repetição. 
Simplificando: A geração é baseada na data atual e uma combinação de cálculos com números aleatórios.

## Funcionalidades

- **Geração de Números de Protocolo**: O código gera números de protocolo únicos com base na data atual (dia, mês e ano) e cálculos simples para garantir que não haja repetições.
- **Cálculo com Data**: Utiliza o dia e o mês atuais como base, realizando operações de subtração e adição para compor a primeira parte do protocolo.
- **Randomização Controlada**: A segunda parte do protocolo é formada pela soma de 1000 a um número aleatório que é multiplicado por 9000, garantindo uma variação significativa e evitando repetições.
- **Segurança contra Repetições**: A combinação entre a data e a randomização controlada dos números garante a exclusividade de cada protocolo gerado.

## Como Funciona

1. **Base de Data**: O código usa a data atual (dia e mês), realizando cálculos simples de subtração e adição para formar a primeira parte do número de protocolo.
2. **Randomização**: A segunda parte do protocolo é gerada ao somar 1000 a um número aleatório, que em seguida é multiplicado por 9000 para criar variação.
3. **Geração Única**: A combinação da data atual com o resultado do cálculo aleatório garante a unicidade do protocolo.

## Exemplo de Uso

- Um número de protocolo gerado pode ser algo como: `13062023-45000`, onde:
  - `13062023` refere-se à data processada.
  - `45000` é o resultado de `1000 + (número random * 9000)`.

## Finalidade

Este código é ideal para sistemas que necessitam de geração de números de protocolo únicos, utilizando cálculos simples baseados em data e números aleatórios para garantir a não repetição.
