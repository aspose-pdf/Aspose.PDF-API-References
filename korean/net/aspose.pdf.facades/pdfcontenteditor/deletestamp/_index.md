---
title: "PdfContentEditor.DeleteStamp"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 지정된 페이지에서 스탬프 인덱스로 여러 스탬프를 삭제합니다."
type: docs
weight: 330
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

지정된 페이지에서 스탬프 인덱스로 여러 스탬프를 삭제합니다.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 스탬프가 삭제될 페이지 번호입니다. |
| index | Int32[] | 스탬프 인덱스. |

## 예제

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


