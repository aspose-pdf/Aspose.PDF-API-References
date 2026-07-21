---
title: "Clase System::Collections::Generic::DictionaryIterator"
linktitle: "DictionaryIterator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::DictionaryIterator. Iterador de diccionario que proporciona notación KeyValuePair en C++."
type: docs
weight: 1200
url: /es/cpp/system.collections.generic/dictionaryiterator/
---
## DictionaryIterator class


[Dictionary](../dictionary/) iterator that provides [KeyValuePair](../keyvaluepair/) notation.

```cpp
template<typename Dict>class DictionaryIterator : public System::Details::NativeIteratorWrapperBase<Dict::KeyValuePairType, Dict::map_t::const_iterator>,
                                                  private System::Details::IteratorPointerUpdater<Dict::KeyValuePairType, false>
```


| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| [DecrementIterator](./decrementiterator/)() override | Mueve el iterador un paso atrás. |
| [DictionaryIterator](./dictionaryiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
| [DictionaryIterator](./dictionaryiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
| [DictionaryIterator](./dictionaryiterator/)(DictionaryIterator\&&) | Constructor de movimiento. |
| [IncrementIterator](./incrementiterator/)() override | Mueve el iterador un paso adelante. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Mueve el iterador la cantidad especificada de pasos. |
| virtual [~DictionaryIterator](./~dictionaryiterator/)() | Destructor. |

## Ver también

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
