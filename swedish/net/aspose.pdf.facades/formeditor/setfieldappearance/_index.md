---
title: "FormEditor.SetFieldAppearance"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Ställ in fältflaggor"
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

Ställ in fältflaggor

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på fältet vars flaggor ska uppdateras. |
| flaggor | AnnotationFlags | Flagga för fältet. |

### Returvärde

true om flaggorna uppdaterades framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Se även

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


