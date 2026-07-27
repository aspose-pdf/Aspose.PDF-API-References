---
title: "LoadOptions.MarginsAreaUsageModes"
linktitle: "LoadOptions.MarginsAreaUsageModes"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa o modo de uso da área de margens durante a conversão (como HTML, EPUB etc.), define o tratamento das instruções do formato importado relacionadas ao uso das margens."
type: docs
weight: 2800
url: /pt/java/com.aspose.pdf/loadoptions.marginsareausagemodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.MarginsAreaUsageModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.MarginsAreaUsageModes

```
public static final class LoadOptions.MarginsAreaUsageModes extends com.aspose.ms.System.Enum
```

Representa o modo de uso da área de margens durante a conversão (como HTML, EPUB etc.), define o tratamento das instruções do formato importado relacionadas ao uso das margens.

## Campos

| Campo | Descrição |
| --- | --- |
| [NeverPutContentOnMarginArea](#NeverPutContentOnMarginArea) | Este modo proíbe estritamente o uso da área de margens, portanto, o conversor nunca usará a área de margens para renderização, mesmo que o CSS ou o formato do documento de origem permita ou exija isso. |
| [PutContentOnMarginAreaIfNecessary](#PutContentOnMarginAreaIfNecessary) | Neste modo, o conversor obedece ao formato do documento importado (por exemplo, CSS do HTML importado) no uso da área de margens. Assim, se o formato do documento importado exigir o uso da área de margens para renderização, o conversor permitirá isso. |

### NeverPutContentOnMarginArea {#NeverPutContentOnMarginArea}
```
public static final int NeverPutContentOnMarginArea
```

Este modo proíbe estritamente o uso da área de margens, portanto, o conversor nunca usará a área de margens para renderização, mesmo que o CSS ou o formato do documento de origem permita ou exija isso.

### PutContentOnMarginAreaIfNecessary {#PutContentOnMarginAreaIfNecessary}
```
public static final int PutContentOnMarginAreaIfNecessary
```

Neste modo, o conversor obedece ao formato do documento importado (por exemplo, CSS do HTML importado) no uso da área de margens. Assim, se o formato do documento importado exigir o uso da área de margens para renderização, o conversor permitirá isso.
