---
title: "PdfContentEditor.CreatePopup"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서에 팝업 주석을 생성합니다"
type: docs
weight: 250
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

PDF 문서에 팝업 주석을 생성합니다.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 주석 사각형은 페이지에서 주석의 위치를 정의합니다. |
| contents | String | 주석의 내용. |
| open | Boolean | 팝업 주석이 처음에 열려 있게 표시될지 여부를 지정하는 플래그. |
| 페이지 | Int32 | 주석이 생성될 원본 페이지 번호. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


