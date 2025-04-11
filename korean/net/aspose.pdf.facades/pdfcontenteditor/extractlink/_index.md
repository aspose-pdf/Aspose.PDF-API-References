---
title: PdfContentEditor.ExtractLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. PDF 문서에 포함된 Link 인스턴스의 컬렉션을 추출합니다.
type: docs
weight: 370
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/extractlink/
---
## PdfContentEditor.ExtractLink 메서드

PDF 문서에 포함된 Link 인스턴스의 컬렉션을 추출합니다.

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
    // work with Link instance
}
```

### 참조

* 클래스 [Annotation](../../../aspose.pdf.annotations/annotation/)
* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)