---
title: "PdfContentEditor.CreateCaret"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 캐럿 주석을 생성합니다."
type: docs
weight: 130
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## PdfContentEditor.CreateCaret method

캐럿 주석을 생성합니다.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |
| annotRect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| caretRect | Rectangle | 기본 캐럿의 실제 경계입니다. |
| 기호 | String | 캐럿에 기호가 연결됩니다. 값은 "P"(단락) 또는 "None"일 수 있습니다. |
| annotContents | String | 주석의 내용. |
| color | Color | 주석의 색상. |

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

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


