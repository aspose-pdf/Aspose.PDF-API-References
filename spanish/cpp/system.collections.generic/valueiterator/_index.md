---
title: "Clase System::Collections::Generic::ValueIterator"
linktitle: "ValueIterator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase System::Collections::Generic::ValueIterator. Iterador de Dictionary que proporciona acceso a valores en C++."
type: docs
weight: 4800
url: /es/cpp/system.collections.generic/valueiterator/
---
## ValueIterator class


[Dictionary](../dictionary/) iterator that provides value access.

```cpp
template<typename Dict>class ValueIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::mapped_type, Dict::map_t::const_iterator>,
                                             private System::Details::IteratorPointerUpdater<Dict::map_t::mapped_type, false>
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
| [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Mueve el iterador la cantidad especificada de pasos. |
| [ValueIterator](./valueiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Constructor. |
| [ValueIterator](./valueiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Constructor. |
| [ValueIterator](./valueiterator/)(ValueIterator\&&) | Constructor de movimiento. |
| virtual [~ValueIterator](./~valueiterator/)() | Destructor. |

## Ver también

* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
