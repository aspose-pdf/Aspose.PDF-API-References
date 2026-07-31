---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Aspose.PDF für .NET API-Referenz"
description: "FreeTextAnnotation method. Legt die Formatierung fest, die durch den Parameter textStyle für gesamten Anmerkungstext bestimmt wird"
type: docs
weight: 150
url: /de/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

Legt die Formatierung fest, die durch den Parameter textStyle für gesamten Anmerkungstext bestimmt wird.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Stil(e) für Anmerkungstext angewendet. |
| fontName | String | Schriftname, der für Anmerkungstext verwendet wird. |
| fontSize | Double | Schriftgröße, die für Anmerkungstext verwendet wird. |
| fontColor | Color | Schriftfarbe, die für Anmerkungstext verwendet wird. |

### Siehe auch

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

Legt die Formatierung fest, die durch den Parameter textStyle für ein Textfragment vom Index fromInd bis zum Index toInd bestimmt wird.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fromInd | Int32 | Startindex des Textfragmentes (ab 0). |
| toInd | Int32 | Endindex des Textfragmentes (gezählt ab 0, dieser nicht enthalten). |
| textStyles | RichTextFontStyles | Stil(e), die auf das Textfragment angewendet werden. |

### Siehe auch

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


