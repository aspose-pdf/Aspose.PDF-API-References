---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Справочник API Aspose.PDF для .NET"
description: "FreeTextAnnotation method. Устанавливает форматирование, определяемое параметром textStyle, для всего текста аннотации."
type: docs
weight: 150
url: /ru/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

Устанавливает форматирование, определяемое параметром textStyle, для всего текста annotation.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| textStyles | RichTextFontStyles | Стиль(и), применяемый(ые) к тексту аннотации. |
| fontName | String | Имя шрифта, применяемое к тексту аннотации. |
| fontSize | Double | Размер шрифта, применяемый к тексту аннотации. |
| fontColor | Color | Цвет шрифта, применяемый к тексту аннотации. |

### См. также

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

Устанавливает форматирование, определяемое параметром textStyle, для фрагмента текста от индекса fromInd до индекса toInd.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fromInd | Int32 | Начальный индекс текстового фрагмента (от 0). |
| toInd | Int32 | Конечный индекс текстового фрагмента (считается от 0, не включается). |
| textStyles | RichTextFontStyles | Стили, применённые к текстовому фрагменту. |

### См. также

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


