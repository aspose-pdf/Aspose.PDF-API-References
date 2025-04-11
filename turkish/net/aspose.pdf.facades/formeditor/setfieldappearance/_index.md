---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metodu. Alan bayraklarını ayarla
type: docs
weight: 280
url: /tr/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance metodu

Alan bayraklarını ayarla

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fieldName | String | Bayrakları güncellenmesi gereken alanın adı. |
| flags | AnnotationFlags | Alanın bayrağı. |

### Dönüş Değeri

Bayraklar başarıyla güncellenmişse true döner.

## Örnekler

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Ayrıca Bakınız

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)