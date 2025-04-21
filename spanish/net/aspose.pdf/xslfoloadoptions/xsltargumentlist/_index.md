---
title: XslFoLoadOptions.XsltArgumentList
second_title: Aspose.PDF for .NET API Reference
description: Propiedad XslFoLoadOptions. XsltArgumentList para insertar valores en parámetros xls existentes.
type: docs
weight: 30
url: /es/net/aspose.pdf/xslfoloadoptions/xsltargumentlist/
---
## Propiedad XslFoLoadOptions.XsltArgumentList

XslArgumentList para insertar valores en parámetros xls existentes. El archivo XLS tiene un parámetro 'animal' sin valor: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); ahora el convertidor asume que hay un parámetro 'animal' con el valor 'cat' en el archivo XLS.

```csharp
public XsltArgumentList XsltArgumentList { get; set; }
```

### Ver También

* clase [XslFoLoadOptions](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)