---
title: "PdfContentEditor.CreateJavaScriptLink"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서에서 JavaScript에 대한 링크를 생성합니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## PdfContentEditor.CreateJavaScriptLink method

PDF 문서에서 JavaScript에 대한 링크를 생성합니다.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| code | String | JavaScript 코드. |
| rect | Rectangle | 활성 클릭을 위한 사각형입니다. |
| originalPage | Int32 | 링크가 바인딩된 사각형이 생성될 원본 페이지 번호. |
| color | Color | 활성 클릭을 위한 사각형의 색상입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


