---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Imposta la nuova posizione del campo
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/formeditor/movefield/
---
## Metodo FormEditor.MoveField

Imposta la nuova posizione del campo.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo che deve essere spostato. |
| llx | Single | Ascissa dell'angolo in basso a sinistra del campo. |
| lly | Single | Ordinata dell'angolo in basso a sinistra del campo. |
| urx | Single | Ascissa dell'angolo in alto a destra del campo. |
| ury | Single | Ordinata dell'angolo in alto a destra del campo. |

### Valore di Ritorno

true se la posizione del campo è stata cambiata con successo.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)