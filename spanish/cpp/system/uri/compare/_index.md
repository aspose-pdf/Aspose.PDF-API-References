---
title: "System::Uri::Compare método"
linktitle: "Compare"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "System::Uri::Compare método. Compara los objetos Uri especificados usando las reglas de comparación especificadas en C++."
type: docs
weight: 3500
url: /es/cpp/system/uri/compare/
---
## Uri::Compare method


Compara los objetos [Uri](../) especificados usando las reglas de comparación especificadas.

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| uri1 | const SharedPtr\<Uri\>\& | El primer comparando |
| uri2 | const SharedPtr\<Uri\>\& | El segundo comparando |
| partsToCompare | UriComponents | Especifica las partes de **uri1** y **uri2** a comparar |
| compareFormat | UriFormat | Especifica el escape de caracteres usado cuando se comparan los componentes de URIs |
| comparisonType | StringComparison | Uno de los valores de [StringComparison](../../stringcomparison/) |

### ReturnValue

Un valor negativo si **uri1** es menor que **uri2**; 0 si uri1 y uri2 son iguales; un valor positivo si **uri1** es mayor que **uri2**

## Ver también

* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
