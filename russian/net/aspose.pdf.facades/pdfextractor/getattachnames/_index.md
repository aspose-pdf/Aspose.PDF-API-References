---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: Метод PdfExtractor. Возвращает список вложений в PDF файле. Примечание ExtractAttachments должен быть вызван перед использованием этого метода
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## Метод PdfExtractor.GetAttachNames

Возвращает список вложений в PDF файле. Примечание: ExtractAttachments должен быть вызван перед использованием этого метода.

```csharp
public IList<string> GetAttachNames()
```

### Возвращаемое значение

Список вложений

## Примеры

Пример демонстрирует, как извлечь имена вложений из PDF файла.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### См. также

* класс [PdfExtractor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)