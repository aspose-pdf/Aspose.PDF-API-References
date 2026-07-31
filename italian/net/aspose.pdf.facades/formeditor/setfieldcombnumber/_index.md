---
title: "FormEditor.SetFieldCombNumber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo FormEditor. Imposta il numero di comb per un campo di testo a riga singola regolare; il campo viene automaticamente diviso in tante posizioni o comb equidistanti quanto il valore del parametro combNumber"
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Imposta il numero di combs per un campo di testo a riga singola regolare (il campo viene suddiviso automaticamente in tante posizioni equidistanti, o combs, quanto il valore del parametro combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fieldName | String | Il nome qualificato del campo. |
| combNumber | Int32 | Il numero di comb con cui dividere il campo. |

### Valore di ritorno

Se ha successo, restituisce true; altrimenti false.

## Esempi

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Vedi anche

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


