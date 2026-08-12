---
title: "Clase System::Collections::Generic::KeyIterator"
linktitle: "KeyIterator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::KeyIterator. Iterador de Dictionary que proporciona acceso a claves en C++."
type: docs
weight: 2800
url: /es/cpp/system.collections.generic/keyiterator/
---
## KeyIterator class


[Dictionary](../dictionary/) iterator that provides key access.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


| Parámetro | Descripción |
| --- | --- |
| Dict | [Dictionary](../dictionary/) clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [CloneIterator](./cloneiterator/)() const override | Clona el iterador actual. |
| [DecrementIterator](./decrementiterator/)() override | Mueve el iterador un paso atrás. |
| [IncrementIterator](./incrementiterator/)() override | Mueve el iterador un paso adelante. |
| [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
| [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
| [KeyIterator](./keyiterator/)(KeyIterator\&&) | Constructor de movimiento. |
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Mueve el iterador la cantidad especificada de pasos. |
| virtual [~KeyIterator](./~keyiterator/)() | Destructor. |

## Ver también

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
