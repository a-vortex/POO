# Exemplos em python

1) Crie uma classe bolo
2) Crie uma instância da classe bolo
3) Crie dois tipos de bolo com os seguintes atributos:
- nome
- recheio
- massa
- se tem cobertura - o primeiro tem, o segundo não
4) Crie um terceiro bolo, igual ao primeiro, mas sem cobertura:
- advindo da instância principal
- Advindo de um objeto já criado.

![diagrama uml](image.png)

```
class Bolo:
    pass

bolo1 = Bolo()
bolo1.nome = 'chessecake'
bolo1.recheio = 'morango'
bolo1.massa = 'pao_de_lo'
bolo1.cobertura = True

bolo2 = Bolo()
bolo2.nome = 'bento_cake'
bolo2.recheio = 'chocolate'
bolo2.massa = 'baunilha'
bolo2.cobertura = False

#bolo3 = Bolo()
#bolo3.cobertura = False

bolo3 = bolo1
bolo3.cobertura = False
```