---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Imposta i flag del campo
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## Metodo FormEditor.SetFieldAppearance

Imposta i flag del campo

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo i cui flag devono essere aggiornati. |
| flags | AnnotationFlags | Flag del campo. |

### Valore di Ritorno

true se i flag sono stati aggiornati con successo.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Vedi Anche

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)