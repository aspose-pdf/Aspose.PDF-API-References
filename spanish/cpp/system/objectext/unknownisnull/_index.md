---
title: "System::ObjectExt::UnknownIsNull método"
linktitle: "UnknownIsNull"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::ObjectExt::UnknownIsNull método. Verifica si un objeto de tipo desconocido es nullptr. Sobrecarga para tipos no escalares en C++."
type: docs
weight: 1800
url: /es/cpp/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) method


Comprueba si el objeto de tipo desconocido es nullptr. Sobrecarga para tipos no escalares.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../object/) tipo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | [Object](../../object/) para comprobar. |

### ReturnValue

Verdadero si 'obj == nullptr' es verdadero, falso en caso contrario.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## ObjectExt::UnknownIsNull(T) method


Comprueba si el objeto de tipo desconocido es nullptr. Sobrecarga para tipos escalares.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


| Parámetro | Descripción |
| --- | --- |
| T | [Object](../../object/) tipo. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | T | [Object](../../object/) para comprobar. |

### ReturnValue

Siempre devuelve false.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
