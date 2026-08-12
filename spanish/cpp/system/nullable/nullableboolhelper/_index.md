---
title: "Método System::Nullable::NullableBoolHelper."
linktitle: "NullableBoolHelper"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::Nullable::NullableBoolHelper. Función auxiliar para comprobar si this y other no son nulos y llamar a una lambda si es así. Utilizada en implementaciones en C++."
type: docs
weight: 800
url: /es/cpp/system/nullable/nullableboolhelper/
---
## Nullable::NullableBoolHelper method


Función auxiliar para comprobar si este y **other** no son nulos y llamar a una lambda en ese caso. Usada en implementation.s.

```cpp
template<typename T1> bool System::Nullable<T>::NullableBoolHelper(const T1 &other, const std::function<bool()> &f, bool default_if_both_are_null=false) const
```


| Parámetro | Descripción |
| --- | --- |
| T1 | Otro tipo nullable. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| otro | const T1\& | Otro valor nullable para comparar. |
| f | const std::function\<bool()>\& | Lambda a llamar si tanto **this** como **other** no son nulos. |
| default_if_both_are_null | bool | Valor de retorno si ambos valores son nulos. |

### ReturnValue

false si **this** o **other** es nulo; **default_if_both_are_null** si ambos son nulos; resultado de la llamada a **f** si ambos no son nulos.

## Ver también

* Class [Nullable](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
