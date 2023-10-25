---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: Font property. Sometimes PDF fontsusually Chinese/Japanese/Korean fonts could have specificical font name. This name is value of PDF font property BaseFont and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in nonreadable form. To get readable form its necessary to decode fonts name by rules specifical for this font. This property returns decoded font name so use it for cases when you meet with a nonreadable FontName. If property FontName has readable form this property will be the same as FontName so you can use this property for any cases when you need to get font name in a readable form
type: docs
weight: 20
url: /net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName property

Sometimes PDF fonts(usually Chinese/Japanese/Korean fonts) could have specificical font name. This name is value of PDF font property "BaseFont" and sometimes this property could be represented in hexademical form. If read this name directly it could be represented in non-readable form. To get readable form it's necessary to decode font's name by rules specifical for this font. This property returns decoded font name, so use it for cases when you meet with a non-readable [`FontName`](../fontname/). If property [`FontName`](../fontname/) has readable form this property will be the same as [`FontName`](../fontname/), so you can use this property for any cases when you need to get font name in a readable form.

```csharp
public string DecodedFontName { get; }
```

### See Also

* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


