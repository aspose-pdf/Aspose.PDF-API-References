---
title: "PdfAOptionsBase.PdfAVersion"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfAOptionsBase. Получает или задает версию стандарта PDF/A, используемую для проверки или конвертации"
type: docs
weight: 110
url: /ru/net/aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/
---
## PdfAOptionsBase.PdfAVersion property

Получает или задает версию стандарта PDF/A, которая будет использоваться для проверки или конвертации.

```csharp
public PdfAStandardVersion PdfAVersion { get; set; }
```

### Property Value

Версия стандарта PDF/A. Это может быть одно из значений перечисления [`PdfAStandardVersion`](../../pdfastandardversion/).

## Примечания

Версия стандарта PDF/A используется для определения уровня соответствия при проверке и конвертации PDF/A. Если версия установлена в Auto, система автоматически определит подходящую версию стандарта PDF/A для проверки на основе метаданных документа. Для процесса конвертации PDF/A значение Auto по умолчанию соответствует версии стандарта PDF/A-1b.

### См. также

* enum [PdfAStandardVersion](../../pdfastandardversion/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


