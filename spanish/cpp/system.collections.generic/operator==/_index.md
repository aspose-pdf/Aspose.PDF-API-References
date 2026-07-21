---
title: "System::Collections::Generic::operator== método"
linktitle: "operator=="
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Collections::Generic::operator== método. Compara dos pares clave-valor usando la semántica ''equals''. Utiliza el operador == o el método EqualsTo para ambas claves y valores, lo que sea definido en C++."
type: docs
weight: 5600
url: /es/cpp/system.collections.generic/operator==/
---
## System::Collections::Generic::operator== method


Compara dos pares clave-valor usando la semántica 'equals'. Utiliza el operador == o el método EqualsTo para ambas claves y valores, lo que sea definido.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```


| Parámetro | Descripción |
| --- | --- |
| TKey | Tipo de clave. |
| TValue | Tipo de valor. |

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| izquierda | const KeyValuePair\<TKey, TValue\>\& | Operando LHS. |
| derecha | const KeyValuePair\<TKey, TValue\>\& | Operando RHS. |

### ReturnValue

Verdadero si ambas claves y valores coinciden, falso de lo contrario.

## Ver también

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
