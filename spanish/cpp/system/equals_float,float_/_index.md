---
title: "System::Equals< float, float > método"
linktitle: "Igual< float, float >"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Equals< float, float > método. Especialización para valores de punto flotante de precisión simple. Aunque dos NaN de punto flotante están definidos por IEC 60559:1989 para compararse siempre como desiguales, el contrato para System.Object.Equals, requiere que las sobrescrituras cumplan con los requisitos de un operador de equivalencia. Por lo tanto, System.Double.Equals y System.Single.Equals devuelven True al comparar dos NaN, mientras que el operador de igualdad devuelve False en ese caso, como lo exige el estándar en C++."
type: docs
weight: 18900
url: /es/cpp/system/equals_float,float_/
---
## System::Equals< float, float > method


Especialización para valores de punto flotante de precisión simple. Aunque dos NaN de punto flotante están definidos por IEC 60559:1989 para compararse siempre como desiguales, el contrato para [System.Object.Equals](../object/equals/), requiere que las sobrescrituras cumplan con los requisitos de un operador de equivalencia. Por lo tanto, System.Double.Equals y System.Single.Equals devuelven True al comparar dos NaN, mientras que el operador de igualdad devuelve False en ese caso, como lo exige el estándar.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | const float\& | El primer comparando |
| b | const float\& | El segundo comparando |

### ReturnValue

True si ambos valores son NaN o son iguales, de lo contrario - false

## Ver también

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
