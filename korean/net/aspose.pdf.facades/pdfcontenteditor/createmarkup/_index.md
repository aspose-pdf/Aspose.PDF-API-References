---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. PDF 문서에 마크업 주석을 생성합니다.
type: docs
weight: 200
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup 메서드

PDF 문서에 마크업 주석을 생성합니다.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 페이지에서 주석의 위치를 정의하는 사각형입니다. |
| contents | String | 주석의 내용입니다. |
| type | Int32 | 마크업 주석의 유형입니다. 0(하이라이트), 1(밑줄), 2(취소선), 3(물결선)일 수 있습니다. |
| page | Int32 | 주석이 생성될 원본 페이지의 번호입니다. |
| clr | Color | 마크업의 색상입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)