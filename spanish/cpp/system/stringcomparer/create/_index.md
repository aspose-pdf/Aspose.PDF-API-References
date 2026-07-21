---
title: "Método System::StringComparer::Create"
linktitle: "Crear"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método System::StringComparer::Create. Crea un comparador específico de cultura en C++."
type: docs
weight: 100
url: /es/cpp/system/stringcomparer/create/
---
## StringComparer::Create method


Crea un comparador específico de cultura.

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cultura | const System::SharedPtr\<System::Globalization::CultureInfo\>\& | Cultura para la cual crear el comparador. |
| ignoreCase | bool | Si el comparador debe ignorar mayúsculas y minúsculas. |

### ReturnValue

Puntero al objeto comparador recién creado.

## Ver también

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [StringComparer](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
