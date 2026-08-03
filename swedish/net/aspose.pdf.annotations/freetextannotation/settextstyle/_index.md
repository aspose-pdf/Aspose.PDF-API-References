---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FreeTextAnnotation‑metod. Ställer in formatering som bestäms av parametern textStyle för all annotationstext."
type: docs
weight: 150
url: /sv/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

Ställer in formateringen som bestäms av parametern textStyle för all anteckningstext.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Stil(ar) som tillämpas på annotationstext. |
| fontName | String | Typsnittsnamn som tillämpas på annotationstext. |
| fontSize | Double | Typsnittsstorlek som tillämpas på annotationstext. |
| fontColor | Color | Typsnittsfärg som tillämpas på annotationstext. |

### Se även

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

Ställer in formateringen som bestäms av parametern textStyle för ett textfragment från index fromInd till index toInd.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fromInd | Int32 | Startindex för textfragmentet (från 0). |
| toInd | Int32 | Slutindex för textfragmentet (räknat från 0, detta inkluderas ej). |
| textStyles | RichTextFontStyles | Stil(ar) som tillämpas på textfragmentet. |

### Se även

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


