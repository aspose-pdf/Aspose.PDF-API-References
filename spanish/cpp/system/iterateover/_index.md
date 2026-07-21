---
title: "System::IterateOver método"
linktitle: "IterarSobre"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::IterateOver. Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable con tipo de destino predeterminado en C++."
type: docs
weight: 23900
url: /es/cpp/system/iterateover/
---
## System::IterateOver(const Enumerable *) method


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable con tipo de destino predeterminado.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo de un objeto envuelto |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(const Enumerable *) method


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable sin métodos begin(), end() con argumento de tipo de destino para (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de destino, debe ser devuelto por el iterador |
| Enumerable | El tipo de un objeto envuelto |

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable sin métodos begin(), end() con argumento de tipo de destino para (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| T | El tipo de destino, debe ser devuelto por el iterador |
| Enumerable | El tipo de un objeto envuelto |

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable sin métodos begin(), end() con argumento de tipo de destino predeterminado para (auto& value : IterateOver(enumerable)) análoga al siguiente código C# foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo de un objeto envuelto |

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable con métodos begin(), end() con argumento de tipo de destino predeterminado para (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo de un objeto envuelto |

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable con métodos begin(), end() con tipo de destino igual al value_type original del iterador.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo de un objeto envuelto |
| T | El tipo de destino que debe ser devuelto por el iterador |

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::IterateOver(System::SmartPtr\<Enumerable\>) method


Esta propiedad de función envuelve un objeto enumerable (o iterable) para que pueda usarse con un bucle for basado en rangos. Esta sobrecarga para Enumerable con métodos begin(), end() con tipo de destino diferente y value_type original del iterador.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```


| Parámetro | Descripción |
| --- | --- |
| Enumerable | El tipo de un objeto envuelto |
| T | El tipo de destino que debe ser devuelto por el iterador |

## Ver también

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
