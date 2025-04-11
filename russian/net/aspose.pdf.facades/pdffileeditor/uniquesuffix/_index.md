---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: Свойство PdfFileEditor. Формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. Эта строка должна содержать подстроку NUM, которая будет заменена на числа. Например, если UniqueSuffix = ABCNUM, то для поля fieldName имена будут: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д.
type: docs
weight: 200
url: /ru/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## Свойство PdfFileEditor.UniqueSuffix

Формат суффикса, который добавляется к имени поля, чтобы сделать его уникальным при объединении форм. Эта строка должна содержать подстроку %NUM%, которая будет заменена на числа. Например, если UniqueSuffix = "ABC%NUM%", то для поля "fieldName" имена будут: fieldNameABC1, fieldNameABC2, fieldNameABC3 и т.д.

```csharp
public string UniqueSuffix { get; set; }
```

## Примеры

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### См. также

* класс [PdfFileEditor](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)