---
title: Enum ComparisonMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ComparisonMode de Aspose.Pdf.Comparison. La enumeración del modo de comparación
type: docs
weight: 3140
url: /es/net/aspose.pdf.comparison/comparisonmode/
---
## Enumeración ComparisonMode

La enumeración del modo de comparación.

```csharp
public enum ComparisonMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Normal | `0` | Modo normal. Solo se tienen en cuenta los espacios dentro de los fragmentos de texto (dependiendo de la forma en que se genera el documento). |
| IgnoreSpaces | `1` | Se ignoran todos los espacios. Los cambios se buscan solo en palabras. |
| ParseSpaces | `2` | El modo es similar al normal, pero intenta tener en cuenta el espaciado visual entre los fragmentos de texto basado en la distancia. Reconocer el número de espacios entre fragmentos puede no ser preciso porque esto depende en gran medida de cómo se generan los documentos. Si los documentos son creados por diferentes generadores, puede haber inexactitudes en la comparación de espacios entre fragmentos de texto. |

### Ver También

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)