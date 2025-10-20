# Python Experimenty

Tento adresář obsahuje experimenty a projekty v Pythonu.

## 📚 Jupyter Notebooky

Interaktivní notebooky pro učení a experimentování s Pythonem.

### 01_hello_world.ipynb
**Základní Hello World a escape sekvence**

- Základní `print()` funkce
- Práce s uvozovkami (jednoduché vs. dvojité)
- Escape sekvence (`\n`, `\t`, `\a`)
- Zvukový signál (BELL) - různé způsoby zápisu
- Unicode znaky a jejich notace

### 02_string_formatting.ipynb
**Kompletní průvodce formátováním řetězců**

- **f-strings** - moderní formátování (Python 3.6+)
- **r-strings** - raw stringy pro cesty a regex
- **b-strings** - bajtové řetězce
- **u-strings** - unicode (Python 3)
- **Triple quotes** - víceřádkové texty
- Kombinace prefixů (fr, rb)
- Starší způsoby: `.format()` a `%` operátor
- Praktické příklady: tabulky, debug výpisy, datum a čas

### 03_data_types.ipynb
**Základní datové typy v Pythonu**

- **Primitivní typy**: int, float, str, bool, None
  - Různé číselné soustavy (binární, oktální, hexadecimální)
  - Vědecká notace
  - Operace s čísly a stringy
- **Kolekce**: list, tuple, dict, set
  - Operace a metody pro každý typ
  - Množinové operace
  - Indexování a slicing
- **Type checking a konverze**
  - Funkce `type()` a `isinstance()`
  - Převody mezi typy
  - Konverze kolekcí
- **Mutable vs Immutable**
  - Rozdíl mezi měnitelnými a neměnitelnými typy
  - Reference a kopie objektů
  - ID objektů
- **Praktické příklady**
  - List/dict/set comprehensions
  - Unpacking a `*args`
  - Užitečné funkce: `min()`, `max()`, `sum()`, `sorted()`

## 🚀 Jak používat notebooky

### Prerekvizity
```bash
pip install jupyter notebook
# nebo
pip install jupyterlab
```

### Spuštění
```bash
# Přejít do adresáře Python
cd Python

# Spustit Jupyter Notebook
jupyter notebook

# nebo JupyterLab
jupyter lab
```

### Doporučené pořadí
1. `01_hello_world.ipynb` - Začni zde pro úplné základy
2. `02_string_formatting.ipynb` - Nauč se práci s textem
3. `03_data_types.ipynb` - Pochop datové typy a struktury

## 📝 Další projekty

Zde budou přibývat další Python skripty, moduly a projekty pro experimentování.
