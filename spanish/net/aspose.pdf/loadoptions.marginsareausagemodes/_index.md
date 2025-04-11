---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Enum LoadOptionsMarginsAreaUsageModes de Aspose.Pdf. Representa el modo de uso del área de márgenes durante la conversión como HTML EPUB etc. define el tratamiento de las instrucciones del formato importado relacionadas con el uso de márgenes
type: docs
weight: 6130
url: /es/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## Enumeración LoadOptions.MarginsAreaUsageModes

Representa el modo de uso del área de márgenes durante la conversión (como HTML, EPUB, etc.), define el tratamiento de las instrucciones del formato importado relacionadas con el uso de márgenes.

```csharp
public enum MarginsAreaUsageModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | En este modo, el convertidor obedece el formato del documento importado (por ejemplo, CSS del HTML importado) en el uso del área de márgenes. Así que, si el formato del documento importado requiere el uso del área de márgenes para el renderizado, el convertidor lo permitirá. |
| NeverPutContentOnMarginArea | `1` | Este modo prohíbe estrictamente el uso del área de márgenes, por lo que el convertidor nunca utilizará el área de márgenes para el renderizado, incluso si el CSS o el formato del documento fuente lo permite o requiere. |

### Ver También

* clase [LoadOptions](../loadoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)