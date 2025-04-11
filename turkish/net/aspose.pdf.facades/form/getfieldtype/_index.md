---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Alan türünü döndürür
type: docs
weight: 240
url: /tr/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType metodu

Alan türünü döndürür.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alan adı. |

### Dönüş Değeri

Alan türüne karşılık gelen FileType enumerasyonunun elemanı.

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Ayrıca Bakınız

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)