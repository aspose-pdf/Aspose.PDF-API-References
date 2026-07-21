---
title: "Aspose::Pdf::LoadOptions::MarginsAreaUsageModes enum"
linktitle: "MarginsAreaUsageModes"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LoadOptions::MarginsAreaUsageModes enum. Representa el modo de uso del área de márgenes durante la conversión (como HTML, EPUB, etc.), define el tratamiento de las instrucciones del formato importado relacionadas con el uso de márgenes en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf/loadoptions/marginsareausagemodes/
---
## MarginsAreaUsageModes enum


Representa el modo de uso del área de márgenes durante la conversión (como HTML, EPUB, etc.), define el tratamiento de las instrucciones del formato importado relacionadas con el uso de los márgenes.

```cpp
enum class MarginsAreaUsageModes
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | 0 | En este modo, el convertidor obedece el formato del documento importado (p. ej. CSS del HTML importado) en el uso del área de márgenes. Por lo tanto, si el formato del documento importado requiere el uso del área de márgenes para renderizar, el convertidor lo permitirá. |
| NeverPutContentOnMarginArea | 1 | Este modo prohíbe estrictamente el uso del área de márgenes, por lo que el convertidor nunca utilizará el área de márgenes para renderizar, incluso si el CSS o el formato del documento fuente lo permite o lo requiere. |

## Ver también

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
