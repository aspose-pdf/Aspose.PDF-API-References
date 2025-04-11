---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Imposta il numero di combs per un campo di testo regolare a una sola riga; il campo è automaticamente diviso in tante posizioni o combs equidistanti quante sono il valore del parametro combNumber
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## Metodo FormEditor.SetFieldCombNumber

Imposta il numero di combs per un campo di testo regolare a una sola riga (il campo è automaticamente diviso in tante posizioni, o combs, equidistanti quante sono il valore del parametro combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome del campo qualificato. |
| combNumber | Int32 | Il numero di combs in cui dividere il campo. |

### Valore di ritorno

Se ha successo, restituisce true; altrimenti false.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Vedi Anche

* classe [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)