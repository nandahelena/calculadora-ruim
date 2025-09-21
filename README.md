# Calculadora

Uma calculadora para usar terminal que executa operações matemáticas básicas.

## Instalação

Instale com pip:
```
pip install calculadora
```

Ou clone:
```
git clone https://github.com/seuusuario/calculadora.git
cd calculadora
pip install -e .
```

## Funcionalidades
- Faz contas como +, -, *, /
- Tem funções de matemática: sin, cos, tan, log, sqrt
- Avalia expressões
- Faz contas com números com vírgula
- Dá pra por mais coisas
- Tem cores

## Exemplo de uso
Aqui tem um código:
```
from calculadora import Calc
calc = Calc()
print(calc.avaliar("2 + 2 * 3"))
print(calc.sqrt(16))
print(calc.seno(90))
```

## Licença
MIT.
