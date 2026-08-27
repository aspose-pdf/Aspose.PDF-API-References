---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Referência da API Aspose.PDF para .NET"
description: "Método FreeTextAnnotation. Define a formatação determinada pelo parâmetro textStyle para todo o texto da anotação"
type: docs
weight: 150
url: /pt/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

Define a formatação determinada pelo parâmetro textStyle para todo o texto da anotação.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Estilo(s) aplicado(s) ao texto da anotação. |
| fontName | String | Nome da fonte aplicado ao texto da anotação. |
| fontSize | Double | Tamanho da fonte aplicado ao texto da anotação. |
| fontColor | Color | Cor da fonte aplicada ao texto da anotação. |

### Veja Também

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

Define a formatação determinada pelo parâmetro textStyle para um fragmento de texto do índice fromInd ao índice toInd.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fromInd | Int32 | Índice inicial do fragmento de texto (a partir de 0). |
| toInd | Int32 | Índice final do fragmento de texto (contando a partir de 0, este não incluído). |
| textStyles | RichTextFontStyles | Estilo(s) aplicados ao fragmento de texto. |

### Veja Também

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


