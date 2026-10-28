---
title: "PdfContentEditor.ExtractLink"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. PDF 문서에 포함된 Link 인스턴스 컬렉션을 추출합니다."
type: docs
weight: 370
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink method

PDF 문서에 포함된 Link 인스턴스 컬렉션을 추출합니다.

```csharp
public IList<Annotation> ExtractLink()
```

### 반환 값

Link 객체의 컬렉션

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
IList links = editor.ExtractLink();
foreach (object obj in links)
{
    Link link = (Link)obj;
    // Link 인스턴스를 사용합니다.
}
```

### 또 보기

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


