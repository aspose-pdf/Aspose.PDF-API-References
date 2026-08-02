---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство PdfFileEditor. Формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при конкатенации форм. Эта строка должна содержать подстроку NUM, которая будет заменена числами. Например, если UniqueSuffix = ABCNUM, то имена полей fieldName будут выглядеть как fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д."
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

Формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при конкатенации форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена числами. Например, если UniqueSuffix = "ABC%NUM%", то для поля "fieldName" имена будут: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д.

```csharp
public string UniqueSuffix { get; set; }
```

## Примеры

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### См. также

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


