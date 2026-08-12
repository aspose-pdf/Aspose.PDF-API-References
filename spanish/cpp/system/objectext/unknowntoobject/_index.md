---
title: "System::ObjectExt::UnknownToObject método"
linktitle: "UnknownToObject"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ObjectExt::UnknownToObject método. Convierte un tipo desconocido a Object, manejando tanto situaciones de tipo smart pointer como de tipo valor en C++."
type: docs
weight: 1900
url: /es/cpp/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(const T\&) method


Convierte un tipo desconocido a [Object](../../object/), manejando tanto situaciones de tipo smart pointer como de tipo valor.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo a convertir a [Object](../../object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) a convertir. |

### ReturnValue

Smart pointer a [Object](../../object/) que es ya sea un puntero convertido o un valor empaquetado.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownToObject(T) method


Convierte un tipo desconocido a [Object](../../object/), manejando tanto situaciones de tipo smart pointer como de tipo valor.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo a convertir a [Object](../../object/). |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | [Object](../../object/) a convertir. |

### ReturnValue

Smart pointer a [Object](../../object/) que es ya sea un puntero convertido o un valor empaquetado.

## Ver también

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
