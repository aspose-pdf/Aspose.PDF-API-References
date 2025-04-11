---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Свойство формы. Получает список имен полей на форме
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/form/fieldnames/
---
## Свойство Form.FieldNames

Получает список имен полей на форме.

```csharp
public string[] FieldNames { get; }
```

## Примеры

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### См. также

* класс [Form](../)
* пространство имен [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* сборка [Aspose.PDF](../../../)