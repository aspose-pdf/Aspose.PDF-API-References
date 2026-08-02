---
title: "PdfAOptionsBase.AlignText"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfAOptionsBase. Получает или задает значение, указывающее, необходимы ли дополнительные меры для сохранения выравнивания текста во время процесса преобразования PDF/A."
type: docs
weight: 10
url: /ru/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

Получает или задает значение, указывающее, необходимы ли дополнительные средства для сохранения выравнивания текста во время процесса конвертации PDF/A.

```csharp
public bool AlignText { get; set; }
```

### Property Value

`true`, если выравнивание текста изменяется и требуются дополнительные действия для его восстановления; иначе `false`.

## Примечания

Когда установлено значение `true`, процесс преобразования попытается восстановить исходные границы текстовых сегментов. Для большинства документов нет необходимости менять это свойство от значения по умолчанию `false`, так как выравнивание текста не меняется в процессе стандартного преобразования.

### См. также

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


