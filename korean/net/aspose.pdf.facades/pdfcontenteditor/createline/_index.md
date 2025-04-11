---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 선 주석을 생성합니다.
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine 메서드

선 주석을 생성합니다.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| x1 | Single | 선의 시작 수평 좌표입니다. |
| y1 | Single | 선의 시작 수직 좌표입니다. |
| x2 | Single | 선의 끝 수평 좌표입니다. |
| y2 | Single | 선의 끝 수직 좌표입니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| border | Int32 | 포인트 단위의 테두리 너비입니다. 이 값이 0이면 테두리가 그려지지 않습니다. 기본값은 1입니다. |
| clr | Color | 선의 색상입니다. |
| borderStyle | String | 선을 그릴 때 사용할 너비와 대시 패턴을 지정하는 테두리 스타일입니다. 이 값은 "S" (Solid), "D" (Dashed), "B" (Beveled), "I" (Inset), "U" (Underline) 중 하나일 수 있습니다. |
| dashArray | Int32[] | 대시 테두리를 그릴 때 사용할 대시와 간격의 패턴을 정의하는 대시 배열입니다. 사용되는 경우 borderStyle은 "D"로 설정해야 합니다. |
| LEArray | String[] | 그리는 선의 시작 및 끝 스타일을 각각 지정하는 두 값의 배열입니다. 값은 "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash" 중 하나일 수 있습니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### 참조

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)