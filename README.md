# Grammar School - Python Implementation

Python implementation of Grammar School, a lightweight framework for building LLM-friendly DSLs.

## Installation

```bash
pip install grammar-school
```

## Usage

```python
from grammar_school import Grammar, Engine, method

class MyGrammar(Grammar):
    @method
    def my_method(self, arg: str):
        ...

engine = Engine(grammar_str, MyGrammar())
engine.execute(dsl_code)
```

## Documentation

For complete documentation, see the main [Grammar School](https://github.com/Conceptual-Machines/grammar-school) repository.

## License

AGPL v3 - See LICENSE file for details.
