---
title: "Método System::ObjectExt::CoalesceInternal"
linktitle: "CoalesceInternal"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::ObjectExt::CoalesceInternal. Implementación de la traducción del operador ''??'' para tipos no anulables. Sobrecarga para el caso en que RT2 sea convertible a RT1 en C++."
type: docs
weight: 700
url: /es/cpp/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal method


Implementación de la traducción del operador '??' para tipos no anulables. Sobrecarga para el caso en que RT2 sea convertible a RT1.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


| Parámetro | Descripción |
| --- | --- |
| T0 | Tipo de valor LHS. |
| T1 | Tipo de lambda que encapsula la expresión RHS. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | RT1 | Valor LHS. |
| func | F | Expresión RHS. |

### ReturnValue

Si el valor LHS no es nulo, devuelve LHS; de lo contrario calcula la expresión RHS y devuelve el resultado.

## Ver también

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
