---
title: RemoveField
second_title: Aspose.PDF for .NET API Referansı
description: Alanı formdan kaldırın.
type: docs
weight: 250
url: /tr/net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Alanı formdan kaldırın.

```csharp
public void RemoveField(string fieldName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| fieldName | String | Kaldırılması gereken alanın adı. |

### Örnekler

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### Ayrıca bakınız

* class [FormEditor](../../formeditor)
* ad alanı [Aspose.Pdf.Facades](../../formeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
