---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzen von Feldflags
type: docs
weight: 280
url: /de/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance-Methode

Setzen von Feldflags

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes, dessen Flags aktualisiert werden sollen. |
| flags | AnnotationFlags | Flag des Feldes. |

### Rückgabewert

true, wenn die Flags erfolgreich aktualisiert wurden.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Siehe auch

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)