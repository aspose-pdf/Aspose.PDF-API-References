---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. PDF 문서에 팝업 주석을 생성합니다.
type: docs
weight: 250
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup 메서드

PDF 문서에 팝업 주석을 생성합니다.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 주석 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| open | Boolean | 팝업 주석이 처음에 열려 있어야 하는지를 지정하는 플래그입니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)