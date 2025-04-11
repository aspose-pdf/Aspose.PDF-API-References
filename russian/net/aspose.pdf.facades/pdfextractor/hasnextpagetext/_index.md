---
title: PdfExtractor.HasNextPageText
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfExtractor. Указывает, можно ли получить больше текстов или нет
type: docs
weight: 210
url: /ru/net/aspose.pdf.facades/pdfextractor/hasnextpagetext/
---
## Метод PdfExtractor.HasNextPageText

Указывает, можно ли получить больше текстов или нет.

```csharp
public bool HasNextPageText()
```

### Возвращаемое значение

Можно получить больше текстов или нет, true - можно, или false.

## Примеры

Пример демонстрирует использование свойства `HasNextPageText` в сценарии извлечения текста.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### См. также

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)