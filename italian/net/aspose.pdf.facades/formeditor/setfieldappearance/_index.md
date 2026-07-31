---
title: "FormEditor.SetFieldAppearance"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Imposta i flag del campo"
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

Imposta i flag del campo

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo i cui flag devono essere aggiornati. |
| flags | AnnotationFlags | Flag del campo. |

### Valore di ritorno

vero se le flag sono state aggiornate correttamente.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Vedi anche

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


