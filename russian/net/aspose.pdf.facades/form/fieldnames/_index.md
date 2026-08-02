---
title: "Form.FieldNames"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Form. Получает список имён полей в форме."
type: docs
weight: 30
url: /ru/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

Получает список имён полей в форме.

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


