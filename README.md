# Calculadora de Imposto em Python

![Badge Python](https://img.shields.io/badge/Python-3.x-blue)

## Introdução

Este projeto apresenta uma **calculadora de imposto** desenvolvida em Python.

O programa calcula *15% sobre um valor base* e adiciona uma **taxa fixa**, retornando o valor total a pagar.

---

## Pré-requisitos

Para executar o programa é necessário:

- Python 3.x instalado; ou
- Google Colab.

Para mais informações sobre Python:

https://docs.python.org/3/

---

## Funcionalidades

- Calcular imposto de 15%.
- Somar uma taxa fixa.
- Exibir o valor final.

---

## Passo a Passo

1. Abra o arquivo Python.
2. Execute o código.
3. Informe os valores desejados.
4. Visualize o resultado.

### Exemplo de código

```python
resultado = calcular_imposto(100.00, 10.00)
print(f"Total a pagar: R$ {resultado:.2f}")
```

### Resultado esperado

```
Total a pagar: R$ 25.00
```

---

## Código Principal

```python
def calcular_imposto(valor_base, taxa_fixa):
    """
    Calcula o imposto total aplicando 15%
    sobre o valor base e somando uma taxa fixa.
    """

    porcentagem_imposto = 0.15
    valor_imposto = valor_base * porcentagem_imposto
    total_a_pagar = valor_imposto + taxa_fixa

    return total_a_pagar


resultado = calcular_imposto(100.00, 10.00)

print(f"Total a pagar: R$ {resultado:.2f}")
```

---

## Fórmula

```
Imposto = Valor Base × 15%

Total = Imposto + Taxa Fixa
```

---

## Troubleshooting

Caso o programa apresente erro:

- Verifique se está utilizando Python 3.
- Confira se os valores são numéricos.
- Execute todo o código antes de chamar a função.

---

## Conclusão

Este projeto demonstra o uso de funções em Python para realizar cálculos matemáticos de forma simples e organizada. A documentação em Markdown facilita a compreensão do código e sua reutilização por outros desenvolvedores.
