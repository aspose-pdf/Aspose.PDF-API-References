---
title: "FreeTextAnnotation.SetTextStyle"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FreeTextAnnotation method. 모든 주석 텍스트에 대해 매개변수 textStyle에 의해 결정된 서식을 설정합니다"
type: docs
weight: 150
url: /ko/net/aspose.pdf.annotations/freetextannotation/settextstyle/
---
## SetTextStyle(RichTextFontStyles, string, double, Color) {#settextstyle}

textStyle 매개변수에 의해 결정된 서식을 모든 Annotation 텍스트에 적용합니다.

```csharp
public void SetTextStyle(RichTextFontStyles textStyles, string fontName, double fontSize, 
    Color fontColor)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| textStyles | RichTextFontStyles | 주석 텍스트에 적용된 스타일. |
| fontName | String | 주석 텍스트에 적용된 글꼴 이름. |
| fontSize | Double | 주석 텍스트에 적용된 글꼴 크기. |
| fontColor | Color | 주석 텍스트에 적용된 글꼴 색상. |

### 또 보기

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## SetTextStyle(int, int, RichTextFontStyles) {#settextstyle_1}

textStyle 매개변수에 의해 결정된 서식을 fromInd 인덱스부터 toInd 인덱스까지의 텍스트 조각에 적용합니다.

```csharp
public void SetTextStyle(int fromInd, int toInd, RichTextFontStyles textStyles)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fromInd | Int32 | 텍스트 조각의 시작 인덱스(0부터). |
| toInd | Int32 | 텍스트 조각의 끝 인덱스(0부터 계산, 포함되지 않음). |
| textStyles | RichTextFontStyles | 텍스트 조각에 적용된 스타일. |

### 또 보기

* enum [RichTextFontStyles](../../richtextfontstyles/)
* class [FreeTextAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


