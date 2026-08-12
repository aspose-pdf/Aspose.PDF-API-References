---
title: "System::Collections::Generic::Dictionary::Dictionary constructor"
linktitle: "Diccionario"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::Dictionary::Dictionary constructor. Crea un diccionario vacío en C++."
type: docs
weight: 100
url: /es/cpp/system.collections.generic/dictionary/dictionary/
---
## Dictionary::Dictionary() constructor


Crea un diccionario vacío.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary()
```

## Ver también

* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## Dictionary::Dictionary(const map_t\&) constructor


Copia datos del mapa.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const map_t &map)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| map | const map_t\& | Mapa del cual copiar datos. |

## Ver también

* Typedef [map_t](../map_t/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) constructor


Constructor de copia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const SharedPtr\<IDictionary\<TKey, TValue\>\>\& | [Dictionary](../) para copiar datos de. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../idictionary/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## Dictionary::Dictionary(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Constructor de copia.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IDictionary<TKey, TValue>> &src, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| src | const SharedPtr\<IDictionary\<TKey, TValue\>\>\& | Diccionario de origen. |
| comparer | const SharedPtr\<IEqualityComparer\<TKey\>\>\& | [Comparer](../../comparer/) objeto a usar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../idictionary/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## Dictionary::Dictionary(const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Crea un diccionario vacío.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comparer | const SharedPtr\<IEqualityComparer\<TKey\>\>\& | [Comparer](../../comparer/) para usar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## Dictionary::Dictionary(int) constructor


Sobrecarga que corresponde a crear un diccionario preasignado; en realidad no realiza asignación.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capacidad | int | Capacidad a asignar; ignorada. |

## Ver también

* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## Dictionary::Dictionary(int, const SharedPtr\<IEqualityComparer\<TKey\>\>\&) constructor


Crea un diccionario vacío.

```cpp
System::Collections::Generic::Dictionary<TKey, TValue>::Dictionary(int capacity, const SharedPtr<IEqualityComparer<TKey>> &comparer)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| capacity | int | [Dictionary](../) capacidad después de la creación; ignorada. |
| comparer | const SharedPtr\<IEqualityComparer\<TKey\>\>\& | [Comparer](../../comparer/) para usar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [Dictionary](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
