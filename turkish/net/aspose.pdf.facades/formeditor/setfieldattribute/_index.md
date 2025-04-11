---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Alanın özelliklerini ayarlayın
type: docs
weight: 290
url: /tr/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute metodu

Alan özelliklerini ayarlayın.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Özellikleri ayarlanacak alanın adı. |
| flag | PropertyFlag | Bayrak (NoExport/ReadOnly/Required) |

### Dönüş Değeri

Özellik başarıyla ayarlandıysa true döner.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Ayrıca Bakınız

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)