---
title: "Aspose::Pdf::Comparison::ComparisonMode enumeración"
linktitle: "ComparisonMode"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::ComparisonMode enumeración. La enumeración de modo de comparación en C++."
type: docs
weight: 2100
url: /es/cpp/aspose.pdf.comparison/comparisonmode/
---
## ComparisonMode enum


La enumeración de modo de comparación.

```cpp
enum class ComparisonMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Normal | 0 | Modo normal. Solo se tienen en cuenta los espacios dentro de fragmentos de texto (dependiendo de la forma en que se genera el documento). |
| IgnoreSpaces | 1 | Todos los espacios se ignoran. Los cambios se buscan solo en palabras. |
| ParseSpaces | 2 | El modo es similar al normal, pero intenta tener en cuenta el espaciado visual entre fragmentos de texto basado en la distancia. Reconocer la cantidad de espacios entre fragmentos puede no ser preciso porque depende en gran medida de cómo se generan los documentos. Si los documentos son creados por diferentes generadores, pueden existir inexactitudes al comparar los espacios entre fragmentos de texto. |

## Ver también

* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
