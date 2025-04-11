---
title: Delegate HtmlSaveOptions.CssUrlMakingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implementa la creación de la URL del CSS referenciado en el documento HTML generado. Por ejemplo, si desea hacer que el CSS referenciado en HTML, por ejemplo, como otherPage.ASPXCssIDzjjkklj, entonces tal estrategia personalizada debe devolver otherPage.ASPXCssIDzjjkklj
type: docs
weight: 5600
url: /es/net/aspose.pdf/htmlsaveoptions.cssurlmakingstrategy/
---
## Delegado HtmlSaveOptions.CssUrlMakingStrategy

Puede asignar a esta propiedad un delegado creado a partir de un método personalizado que implementa la creación de la URL del CSS referenciado en el documento HTML generado. Por ejemplo, si desea hacer que el CSS referenciado en HTML, por ejemplo, como "otherPage.ASPX?CssID=zjjkklj", entonces tal estrategia personalizada debe devolver "otherPage.ASPX?CssID=zjjkklj"

```csharp
public delegate string CssUrlMakingStrategy(CssUrlRequestInfo cssUrlRequestInfo);
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cssUrlRequestInfo | CssUrlRequestInfo | representa un conjunto de datos que se puede utilizar para la generación de la URL del CSS |

### Valor de Retorno

debe devolver una cadena que representa la URL del CSS o la plantilla de la URL

### Véase También

* clase [CssUrlRequestInfo](../htmlsaveoptions.cssurlrequestinfo/)
* clase [HtmlSaveOptions](../htmlsaveoptions/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)