---
title: "Método System::ObjectExt::ObjectToUnknown"
linktitle: "ObjectToUnknown"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::ObjectToUnknown. Convierte Object a un tipo desconocido, manejando tanto situaciones de tipo puntero inteligente como de valor empaquetado en C++."
type: docs
weight: 1300
url: /es/cpp/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


Convierte [Object](../../object/) a un tipo desconocido, manejando tanto situaciones de tipo puntero inteligente como de valor empaquetado.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que convertir [Object](../../object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | [Object](../../object/) a convertir. |

### ReturnValue

Ya sea valor desempaquetado o puntero convertido.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) method


Convierte [Object](../../object/) a un tipo desconocido, manejando tanto situaciones de tipo puntero inteligente como de valor empaquetado.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo al que convertir [Object](../../object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | SmartPtr\<Object\> | [Object](../../object/) a convertir. |

### ReturnValue

Ya sea valor desempaquetado o puntero convertido.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
