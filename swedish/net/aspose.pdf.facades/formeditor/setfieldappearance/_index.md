---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Ställ in fältflaggor
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance metod

Ställ in fältflaggor

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på fältet vars flaggor ska uppdateras. |
| flags | AnnotationFlags | Flagga för fältet. |

### Returvärde

true om flaggorna uppdaterades framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Se Även

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)