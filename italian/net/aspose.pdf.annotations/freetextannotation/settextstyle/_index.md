---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "FreeTextAnnotation method. Imposta la formattazione determinata dal parametro textStyle per tutto il testo dell'annotazione"
type: docs
weight: 150
url: /it/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

Imposta la formattazione determinata dal parametro textStyle per tutto il testo dell'annotazione.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Stile(i) applicato(i) al testo dell'annotazione. |
| fontName | String | Nome del carattere applicato al testo dell'annotazione. |
| fontSize | Double | Dimensione del carattere applicata al testo dell'annotazione. |
| fontColor | Color | Colore del carattere applicato al testo dell'annotazione. |

### Vedi anche

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

Imposta la formattazione determinata dal parametro textStyle per un frammento di testo dall'indice fromInd all'indice toInd.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fromInd | Int32 | Indice iniziale del frammento di testo (da 0). |
| toInd | Int32 | Indice finale del frammento di testo (contando da 0, non incluso). |
| textStyles | RichTextFontStyles | Stili applicati al frammento di testo. |

### Vedi anche

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


