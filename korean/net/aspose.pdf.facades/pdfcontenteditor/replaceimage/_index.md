---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. PDF 문서의 지정된 페이지에서 지정된 이미지를 다른 이미지로 교체합니다.
type: docs
weight: 440
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## PdfContentEditor.ReplaceImage 메서드

PDF 문서의 지정된 페이지에서 지정된 이미지를 다른 이미지로 교체합니다.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 이미지가 교체되는 페이지의 번호입니다. |
| index | Int32 | 교체해야 하는 이미지 객체의 인덱스입니다. |
| imageFile | String | 교체에 사용될 이미지 파일입니다. |

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)