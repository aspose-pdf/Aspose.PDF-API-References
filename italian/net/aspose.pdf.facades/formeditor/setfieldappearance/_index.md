---
title: SetFieldAppearance
second_title: Aspose.PDF per .NET API Reference
description: Imposta flag di campo
type: docs
weight: 320
url: /it/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

Imposta flag di campo

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo i cui flag devono essere aggiornati. |
| flags | AnnotationFlags | Bandiera del campo. |

### Valore di ritorno

true se i flag sono stati aggiornati correttamente.

### Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Guarda anche

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags)
* class [FormEditor](../../formeditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../formeditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
