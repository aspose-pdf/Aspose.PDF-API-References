---
title: "PdfContentEditor.CreateFreeText"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서에 자유 텍스트 주석을 생성합니다."
type: docs
weight: 160
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## PdfContentEditor.CreateFreeText method

PDF 문서에 자유 텍스트 주석을 생성합니다.

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| contents | String | 주석의 내용. |
| 페이지 | Int32 | 텍스트 주석이 생성될 원본 페이지 번호입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


