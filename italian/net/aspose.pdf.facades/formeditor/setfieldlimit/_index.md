---
title: "FormEditor.SetFieldLimit"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Imposta il conteggio massimo di caratteri del campo di testo"
type: docs
weight: 310
url: /it/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

Imposta il numero massimo di caratteri del campo di testo.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Nome del campo di testo. |
| fieldLimit | Int32 | Nuovo valore del limite per il campo. |

### Valore di ritorno

true se il limite del campo è stato impostato correttamente.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


