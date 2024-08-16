# Debug Report

## Introduction

This is a debug report that includes various types of texts and information to facilitate problem identification and resolution.

---

## Headers

### Level 3 Header

#### Level 4 Header

##### Level 5 Header

---

## Lists

### Unordered List

- Item 1
- Item 2
    - Subitem 1
    - Subitem 2
- Item 3

### Ordered List

1. First item
2. Second item
3. Third item

### Tasks

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

---

## Code

### Inline Code

To show inline code, use single backticks, like `print("Hello, World!")`.

### Code Block

```python
def greeting(name):
    """
    Function that returns a personalized greeting.
    """
    return f"Hello, {name}!"

print(greeting("World"))
```

---

## Tables

| Col 1   | Col 2                                              |
|-------- |----------------------------------------------------|
|**bold** | ![Valid XHTML] (http://w3.org/Icons/valid-xhtml10) |
| Plain   | Value                                              |
| Pipe    | \|                                                 |

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| **col 3 is**  | right-aligned | $1600 |
| col 2 is      | *centered*    |   $12 |
| zebra stripes | ~~are neat~~  |    $1 |

---

## Links

- [Official Documentation](https://www.example.com)
- [GitHub Repository](https://github.com/user/repo)

---

## Images

![Example Image](http://w3.org/Icons/valid-xhtml10)

Image base64:

![Image base64](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAQAAAADCAIAAAA7l
jmRAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAY
SURBVBhXYwCC/2AAZYEoOAMs8Z+BgQEAXdcR7/Q1gssAAAAASUVORK5CYII=)

---

## Quotes

> "Success is the sum of small efforts repeated day in and day out." - Robert Collier

---

## Notes

- **Important Note**: Make sure all dependencies are installed correctly.
- **Observation**: Ensure that the development environment is configured according to the documentation.

---

## References

1. [Markdown Guide](https://www.markdownguide.org/)
2. [Python Documentation](https://docs.python.org/3/)

```python
# Este é um comentário simples

# Definição de uma função
def exemplo_funcao(parametro1, parametro2):
    """
    Esta é uma função exemplo que realiza uma operação simples.
    """
    resultado = parametro1 + parametro2
    return resultado

# Definição de uma classe
class ExemploClasse:
    def __init__(self, valor):
        self.valor = valor
    
    def mostrar_valor(self):
        print(f"O valor é: {self.valor}")

    def incrementar_valor(self, incremento):
        self.valor += incremento

# Funções internas e chamadas de função
def exemplo_avancado():
    numero = 10
    incremento = 5

    # Funções incorporadas
    numero_str = str(numero)  # Conversão de número para string
    incremento_str = str(incremento)

    # Chamada de função definida pelo usuário
    novo_valor = exemplo_funcao(numero, incremento)

    print(f"Novo valor calculado: {novo_valor}")

    # Trabalhando com a classe
    objeto = ExemploClasse(novo_valor)
    objeto.mostrar_valor()
    objeto.incrementar_valor(3)
    objeto.mostrar_valor()

# Palavras-chave e operadores
if __name__ == "__main__":
    # Testando a função avançada
    exemplo_avancado()
    
    # Mais exemplos com operadores
    x = 10
    y = 20
    z = (x + y) * (x - y) / (x ** 2)
    print(f"Resultado final: {z}")

    # Usando valores booleanos
    condicao = True
    if condicao and not False:
        print("A condição é verdadeira")

    # Trabalhando com None
    nada = None
    if nada is None:
        print("Nada é igual a None")

# Utilizando funções incorporadas comuns
print("Valor absoluto de -5:", abs(-5))
print("Valor máximo entre 3, 7 e 2:", max(3, 7, 2))
```
