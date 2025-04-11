---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Ställer in antalet kamrar för ett vanligt enradigt textfält som fältet automatiskt delas in i så många lika avståndspositioner eller kamrar som värdet av parametern combNumber
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber metod

Ställer in antalet kamrar för ett vanligt enradigt textfält (fältet delas automatiskt in i så många lika avståndspositioner, eller kamrar, som värdet av parametern combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det kvalificerade fältnamnet. |
| combNumber | Int32 | Antalet kamrar att dela fältet i. |

### Returvärde

Om framgång, returnera true; annars false.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)