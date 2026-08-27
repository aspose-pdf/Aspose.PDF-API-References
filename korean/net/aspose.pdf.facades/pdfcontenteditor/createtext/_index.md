---
title: "PdfContentEditor.CreateText"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서에 텍스트 주석을 생성합니다."
type: docs
weight: 290
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

PDF 문서에 텍스트 주석을 생성합니다.

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| 제목 | String | 주석의 제목. |
| contents | String | 주석의 내용. |
| open | Boolean | 주석이 처음에 열려 있는 상태로 표시될지 여부를 지정하는 플래그입니다. |
| icon | String | 주석을 표시할 때 사용할 아이콘 이름입니다. 이 값은 다음 중 하나일 수 있습니다: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| 페이지 | Int32 | 텍스트 주석이 생성될 원본 페이지 번호입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


