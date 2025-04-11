---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 커서 주석을 생성합니다.
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret 메서드

커서 주석을 생성합니다.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| annotRect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| caretRect | Rectangle | 기본 커서의 실제 경계입니다. |
| symbol | String | 커서와 연관될 기호입니다. 값은 "P" (단락), "None"이 될 수 있습니다. |
| annotContents | String | 주석의 내용입니다. |
| color | Color | 주석의 색상입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)