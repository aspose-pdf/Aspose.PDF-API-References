---
title: GetNextPageText
second_title: Aspose.PDF для справочника API .NET
description: Сохраняет текст одной страницы в файл.
type: docs
weight: 180
url: /ru/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

Сохраняет текст одной страницы в файл.

```csharp
public void GetNextPageText(string outputFile)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputFile | String | Путь и имя файла для сохранения текста. |

### Примеры

Пример демонстрирует использование метода GetNextPageText в сценарии извлечения текста.

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

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

---

## GetNextPageText(Stream) {#getnextpagetext}

Сохраняет текст одной страницы в поток.

```csharp
public void GetNextPageText(Stream outputStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Поток для сохранения текста. |

### Примеры

Пример демонстрирует[`GetNextPageText`](../getnextpagetext) использование метода в сценарии извлечения текста.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    FileStream fs = new FileStream(prefix + pageCount + suffix, FileMode.Create);
    extractor.GetNextPageText(prefix + pageCount + suffix);
    fs.Close();
    pageCount++;
}
```

### Смотрите также

* class [PdfExtractor](../../pdfextractor)
* пространство имен [Aspose.Pdf.Facades](../../pdfextractor)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->