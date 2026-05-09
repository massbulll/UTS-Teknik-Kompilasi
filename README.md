# Tugas UTS Teknik Kompilasi

## Deskripsi
Implementasi Mini Compiler yang mendukung:
- Lexical Analysis (Tokenizer)
- Parsing dengan EBNF
- Abstract Syntax Tree (AST)
- Three Address Code (TAC) generation

## Fitur
- Operator aritmatika: `+`, `-`, `*`, `/`
- **Operator pangkat (`^`)** dengan prioritas tertinggi
- Right-associative untuk operator pangkat
- Semantic checking (variabel undefined)
- Nested parentheses

## Contoh Penggunaan

### Input
```python
source = "a ^ 2 + b * c"
symbol_table = {'a': 5, 'b': 10, 'c': 2}
