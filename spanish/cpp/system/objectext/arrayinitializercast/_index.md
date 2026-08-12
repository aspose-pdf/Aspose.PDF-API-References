---
title: "Método System::ObjectExt::ArrayInitializerCast"
linktitle: "ArrayInitializerCast"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::ArrayInitializerCast. Convierte valores fundamentales de matrices (que C# hace implícitamente pero C++ aparentemente no) en C++."
type: docs
weight: 100
url: /es/cpp/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast method


Convierte valores fundamentales de matrices (que C# hace implícitamente pero C++ aparentemente no lo hace).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


| Parámetro | Descripción |
| --- | --- |
| To | Tipo objetivo. |
| From | Tipos de origen. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | De ... | Valores a convertir y empujar al array de destino. |

### ReturnValue

[Array](../../array/) containing converted copies of all arguments in the same order.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
