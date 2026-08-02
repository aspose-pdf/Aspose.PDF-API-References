---
title: "PdfExtractor.GetAttachNames"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод PdfExtractor. Возвращает список вложений в PDF‑файле. Примечание: ExtractAttachments должен быть вызван до использования этого метода."
type: docs
weight: 160
url: /ru/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames method

Возвращает список вложений в PDF-файле. Примечание: перед использованием этого метода необходимо вызвать ExtractAttachments.

```csharp
public IList<string> GetAttachNames()
```

### Возвращаемое значение

Список вложений

## Примеры

Пример демонстрирует, как извлечь имена вложений из PDF‑файла.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### См. также

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


