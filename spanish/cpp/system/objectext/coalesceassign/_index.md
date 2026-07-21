---
title: "Método System::ObjectExt::CoalesceAssign"
linktitle: "CoalesceAssign"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::CoalesceAssign. Implementación de la traducción del operador ''??='' en C++."
type: docs
weight: 600
url: /es/cpp/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign method


Implementación de la traducción del operador '??='.

```cpp
template<typename T0,typename T1> static T0 & System::ObjectExt::CoalesceAssign(T0 &value, T1 func)
```


| Parámetro | Descripción |
| --- | --- |
| T0 | Tipo de valor LHS. |
| T1 | Tipo de lambda que encapsula la expresión RHS. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | T0\& | Valor LHS. |
| func | T1 | Expresión RHS. |

### ReturnValue

Si el valor LHS no es nulo, devuelve LHS; de lo contrario calcula la expresión RHS y devuelve el resultado.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
