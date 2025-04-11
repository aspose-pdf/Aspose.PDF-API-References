---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 스탬프 인덱스를 통해 지정된 페이지에서 여러 스탬프를 삭제합니다.
type: docs
weight: 330
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp 메서드

스탬프 인덱스를 통해 지정된 페이지에서 여러 스탬프를 삭제합니다.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 스탬프가 삭제될 페이지 번호입니다. |
| index | Int32[] | 스탬프 인덱스입니다. |

## 예제

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)