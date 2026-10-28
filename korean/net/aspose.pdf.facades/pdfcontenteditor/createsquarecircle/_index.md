---
title: "PdfContentEditor.CreateSquareCircle"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. squarecircle 주석을 생성합니다"
type: docs
weight: 280
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

사각형-원 주석을 생성합니다.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| contents | String | 주석의 내용. |
| clr | Color | 정사각형 또는 원의 색상. |
| 정사각형 | Boolean | True (square), false (sircle). |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |
| borderWidth | Int32 | 정사각형 또는 원의 테두리 두께. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


