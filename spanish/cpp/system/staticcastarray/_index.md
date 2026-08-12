---
title: "Método System::StaticCastArray"
linktitle: "StaticCastArray"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::StaticCastArray. Realiza la conversión de los elementos de la matriz especificada a un tipo diferente. Sobrescribe para los casos en que From es un objeto SmartPtr en C++."
type: docs
weight: 44600
url: /es/cpp/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Realiza la conversión de los elementos de la matriz especificada a un tipo diferente. Sobrescribe para los casos en que From es un objeto [SmartPtr](../smartptr/).

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que convertir los elementos del array especificado |
| From | El tipo de los elementos del array cuyos elementos se van a convertir |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| desde | const System::SharedPtr\<System::Array\<From\>\>\& | Puntero compartido al array que contiene los elementos a convertir |

### ReturnValue

Un puntero a un nuevo array que contiene elementos del tipo **To** equivalentes a los elementos de **from**

## Deprecated
Añadido por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) method


Realiza la conversión de los elementos de la matriz especificada a un tipo diferente. Sobrescribe para los casos en que From es Boxable y To es [Object](../object/)[].

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


| Parámetro | Descripción |
| --- | --- |
| To | El tipo al que convertir los elementos del array especificado |
| From | El tipo de los elementos del array cuyos elementos se van a convertir |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| desde | const System::SharedPtr\<System::Array\<From\>\>\& | Puntero compartido al array que contiene los elementos a convertir |

### ReturnValue

Un puntero a un nuevo array que contiene elementos del tipo **To** equivalentes a los elementos de **from**

## Deprecated
Añadido por compatibilidad hacia atrás. Use ExplicitCast en su lugar.

## Ver también

* Typedef [SharedPtr](../sharedptr/)
* Class [Object](../object/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
