---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Form metodu. Alanın bayraklarını döndürür
type: docs
weight: 220
url: /tr/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag metodu

Alanın bayraklarını döndürür.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Alan adı |

### Dönüş Değeri

Özellik bayrağı (ReadOnly/ Required/NoExport

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Ayrıca Bakınız

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)