---
title: "PdfContentEditor.CreateMarkup"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서에 마크업 주석을 생성합니다."
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

PDF 문서에 마크업 주석을 생성합니다.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석 위치를 정의하는 사각형입니다. |
| contents | String | 주석의 내용. |
| 유형 | Int32 | 마크업 주석의 유형입니다. 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly) 중 하나일 수 있습니다. |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |
| clr | Color | 마크업의 색상입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


