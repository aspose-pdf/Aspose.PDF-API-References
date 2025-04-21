---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Puede asignar a esta propiedad una estrategia personalizada que implemente el procesamiento y/o guardado de una parte de CSS que se creó durante la conversión de PDF a HTML. En tal caso, el procesamiento debe realizarse en ese código personalizado.
type: docs
weight: 5590
url: /es/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## Delegado HtmlSaveOptions.CssSavingStrategy

Puede asignar a esta propiedad una estrategia personalizada que implemente el procesamiento y/o guardado de una parte de CSS que se creó durante la conversión de PDF a HTML. En tal caso, el procesamiento (como guardar en un flujo o disco) debe realizarse en ese código personalizado.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | representa un conjunto de datos que se puede utilizar para guardar la parte de CSS suministrada |

### Ver También

* clase [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)