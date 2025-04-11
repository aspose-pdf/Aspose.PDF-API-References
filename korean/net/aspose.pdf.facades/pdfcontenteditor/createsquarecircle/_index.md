---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 사각형 원 주석을 생성합니다.
type: docs
weight: 280
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle 메서드

사각형-원 주석을 생성합니다.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| clr | Color | 사각형 또는 원의 색상입니다. |
| square | Boolean | True (사각형), false (원). |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| borderWidth | Int32 | 사각형 또는 원의 테두리 너비입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)