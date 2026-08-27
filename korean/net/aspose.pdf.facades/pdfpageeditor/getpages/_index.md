---
title: "PdfPageEditor.GetPages"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfPageEditor 메서드. 페이지 총 수를 반환합니다"
type: docs
weight: 150
url: /ko/net/aspose.pdf.facades/pdfpageeditor/getpages/
---
## PdfPageEditor.GetPages method

페이지의 총 수를 반환합니다.

```csharp
public int GetPages()
```

### 반환 값

페이지 수.

## 예제

다음 예제는 GetPages() 메서드 사용을 보여줍니다:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
Console.WriteLine("Document has: " + editor.GetPages());
```

### 또 보기

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


