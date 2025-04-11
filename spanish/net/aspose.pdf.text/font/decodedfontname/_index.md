---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Propiedad de fuente. A veces, las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad de fuente PDF BaseFont y a veces esta propiedad puede estar representada en forma hexadecimal. Si se lee este nombre directamente, puede estar representado en una forma no legible. Para obtener una forma legible, es necesario decodificar el nombre de la fuente según las reglas específicas para esta fuente. Esta propiedad devuelve el nombre de fuente decodificado, así que úsala para los casos en que te encuentres con un [`FontName`](../fontname/) no legible. Si la propiedad [`FontName`](../fontname/) tiene una forma legible, esta propiedad será la misma que [`FontName`](../fontname/), por lo que puedes usar esta propiedad para cualquier caso en que necesites obtener el nombre de la fuente en una forma legible.
type: docs
weight: 20
url: /es/net/aspose.pdf.text/font/decodedfontname/
---
## Propiedad Font.DecodedFontName

A veces, las fuentes PDF (generalmente fuentes chinas/japonesas/coreanas) pueden tener un nombre de fuente específico. Este nombre es el valor de la propiedad de fuente PDF "BaseFont" y a veces esta propiedad puede estar representada en forma hexadecimal. Si se lee este nombre directamente, puede estar representado en una forma no legible. Para obtener una forma legible, es necesario decodificar el nombre de la fuente según las reglas específicas para esta fuente. Esta propiedad devuelve el nombre de fuente decodificado, así que úsala para los casos en que te encuentres con un [`FontName`](../fontname/) no legible. Si la propiedad [`FontName`](../fontname/) tiene una forma legible, esta propiedad será la misma que [`FontName`](../fontname/), por lo que puedes usar esta propiedad para cualquier caso en que necesites obtener el nombre de la fuente en una forma legible.

```csharp
public string DecodedFontName { get; }
```

### Ver También

* clase [Font](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../../)