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
def px_to_em(px, base_font_size=16):
    """Converte pixels para em."""
    return px / base_font_size

def em_to_px(em, base_font_size=16):
    """Converte em para pixels."""
    return em * base_font_size

def font_weight_to_numeric(font_weight):
    """Converte font-weight (normal, bold, etc.) para seu valor numérico equivalente."""
    font_weights = {
        'normal': 400,
        'bold': 700,
        'bolder': 900,
        'lighter': 100,
    }
    return font_weights.get(font_weight.lower(), font_weight)

def numeric_to_font_weight(weight):
    """Converte valores numéricos de font-weight para seus equivalentes nominais."""
    if weight <= 300:
        return 'lighter'
    elif 301 <= weight <= 400:
        return 'normal'
    elif 401 <= weight <= 700:
        return 'bold'
    else:
        return 'bolder'

def convert_values():
    print("Escolha o tipo de conversão:")
    print("1. px para em")
    print("2. em para px")
    print("3. font-weight para valor numérico")
    print("4. valor numérico para font-weight")
    choice = int(input("Digite o número da opção desejada: "))

    if choice == 1:
        px_value = float(input("Digite o valor em px: "))
        base_font_size = float(input("Digite o tamanho base da fonte em px (padrão 16px): ") or 16)
        print(f"{px_value}px = {px_to_em(px_value, base_font_size)}em")
    elif choice == 2:
        em_value = float(input("Digite o valor em em: "))
        base_font_size = float(input("Digite o tamanho base da fonte em px (padrão 16px): ") or 16)
        print(f"{em_value}em = {em_to_px(em_value, base_font_size)}px")
    elif choice == 3:
        font_weight = input("Digite o valor de font-weight (normal, bold, etc.): ")
        print(f"{font_weight} = {font_weight_to_numeric(font_weight)}")
    elif choice == 4:
        numeric_weight = int(input("Digite o valor numérico de font-weight: "))
        print(f"{numeric_weight} = {numeric_to_font_weight(numeric_weight)}")
    else:
        print("Opção inválida. Por favor, escolha um número entre 1 e 4.")

if __name__ == "__main__":
    convert_values()
```
