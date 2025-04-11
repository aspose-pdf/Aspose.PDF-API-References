---
title: PdfAOptionsBase.PdfAVersion
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfAOptionsBase. Получает или задает версию стандарта PDF/A, которая будет использоваться для валидации или конвертации
type: docs
weight: 110
url: /ru/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## Свойство PdfAOptionsBase.PdfAVersion

Получает или задает версию стандарта PDF/A, которая будет использоваться для валидации или конвертации.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Значение свойства

Версия стандарта PDF/A. Это может быть одно из значений перечисления [`PdfAStandardVersion`](../../pdfastandardversion/).

## Замечания

Версия стандарта PDF/A используется для определения уровня соответствия для валидации и конвертации PDF/A. Если версия установлена в Auto, система автоматически определит соответствующую версию стандарта PDF/A для валидации на основе метаданных документа. Для процесса конвертации PDF/A Auto по умолчанию соответствует версии стандарта PDF/A-1b.

### См. также

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)