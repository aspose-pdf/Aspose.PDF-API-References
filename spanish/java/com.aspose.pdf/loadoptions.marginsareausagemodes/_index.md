---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el modo de uso del área de márgenes durante la conversión (como HTML, EPUB, etc.), define el tratamiento de las instrucciones del formato importado relacionadas con el uso de los márgenes."
type: docs
weight: 2800
url: /es/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Representa el modo de uso del área de márgenes durante la conversión (como HTML, EPUB, etc.), define el tratamiento de las instrucciones del formato importado relacionadas con el uso de los márgenes.

## Campos

| Campo | Descripción |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Este modo prohíbe estrictamente el uso del área de márgenes, por lo que el conversor nunca usará el área de márgenes para renderizar, incluso si CSS o el formato del documento fuente lo permite o lo requiere. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | En este modo el conversor obedece el formato del documento importado (p.ej. CSS del HTML importado) en el uso del área de márgenes. Por lo tanto, si el formato del documento importado requiere el uso del área de márgenes para renderizar, el conversor lo permitirá. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Este modo prohíbe estrictamente el uso del área de márgenes, por lo que el conversor nunca usará el área de márgenes para renderizar, incluso si CSS o el formato del documento fuente lo permite o lo requiere.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

En este modo el conversor obedece el formato del documento importado (p.ej. CSS del HTML importado) en el uso del área de márgenes. Por lo tanto, si el formato del documento importado requiere el uso del área de márgenes para renderizar, el conversor lo permitirá.
