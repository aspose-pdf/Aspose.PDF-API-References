---
title: SetFieldAttribute
second_title: Aspose.PDF for .NET API Referansı
description: Alanın özniteliklerini ayarlayın.
type: docs
weight: 330
url: /tr/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

Alanın özniteliklerini ayarlayın.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Niteliklerin ayarlanması gereken alanın adı. |
| flag | PropertyFlag | Bayrak (Dışa Aktarma Yok/Salt Okunur/Gerekli) |

### Geri dönüş değeri

öznitelik başarıyla ayarlanmışsa true .

### Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Ayrıca bakınız

* enum [PropertyFlag](../../propertyflag)
* class [FormEditor](../../formeditor)
* ad alanı [Aspose.Pdf.Facades](../../formeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
