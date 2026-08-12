---
title: "Método System::ObjectExt::UnboxToNullable"
linktitle: "UnboxToNullable"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::UnboxToNullable. Desempaqueta el objeto a un tipo anulable en C++."
type: docs
weight: 1700
url: /es/cpp/system/objectext/unboxtonullable/
---
## ObjectExt::UnboxToNullable method


Desempaqueta objeto a tipo nullable.

```cpp
template<class T> static Nullable<T> System::ObjectExt::UnboxToNullable(const SmartPtr<Object> &obj, bool safe=true)
```


| Parámetro | Descripción |
| --- | --- |
| T | Tipo de destino. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const SmartPtr\<Object\>\& | [Object](../../object/) para desempaquetar. |
| seguro | bool | Si es true, devuelve nullptr en caso de fallo, de lo contrario lanza InvalidCastException. |

### ReturnValue

Valor anulable desempaquetado (puede ser null).

## Ver también

* Class [Nullable](../../nullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
