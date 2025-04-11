---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. PDF 문서에서 JavaScript에 대한 링크를 생성합니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink 메서드

PDF 문서에서 JavaScript에 대한 링크를 생성합니다.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| code | 문자열 | JavaScript 코드. |
| rect | 사각형 | 활성 클릭을 위한 사각형. |
| originalPage | Int32 | 링크와 함께 생성될 사각형의 원본 페이지 번호. |
| color | 색상 | 활성 클릭을 위한 사각형의 색상. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)