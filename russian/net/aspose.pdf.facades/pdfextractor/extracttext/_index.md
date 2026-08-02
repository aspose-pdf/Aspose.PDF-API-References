---
title: "PdfExtractor.ExtractText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfExtractor. Извлекает текст из PDF‑документа, используя Unicode‑кодировку."
type: docs
weight: 130
url: /ru/net/aspose.pdf.facades/pdfextractor/extracttext/
---
## ExtractText() {#extracttext}

Извлекает текст из документа Pdf, используя кодировку Unicode.

```csharp
public void ExtractText()
```

## Примеры

Первый пример демонстрирует, как извлечь весь текст из PDF‑файла.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText()
extractor.GetText("D:\Text\text.txt")
```

Второй пример демонстрирует, как извлечь текст каждой страницы в один txt‑файл.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText();
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
extractor.ExtractText()
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExtractText(Encoding) {#extracttext_1}

Извлекает текст из документа Pdf, используя указанную кодировку.

```csharp
public void ExtractText(Encoding encoding)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoding | Кодировка | Кодировка извлечённого текста. |

## Примеры

Первый пример демонстрирует, как извлечь весь текст из PDF‑файла.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText(Encoding.Unicode);
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText(Encoding.Unicode)
extractor.GetText("D:\Text\text.txt")
```

Второй пример демонстрирует, как извлечь текст каждой страницы в один txt‑файл.

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

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


