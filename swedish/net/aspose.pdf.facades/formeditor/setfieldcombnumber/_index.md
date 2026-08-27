---
title: "FormEditor.SetFieldCombNumber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Ställer in antalet combs för ett vanligt enkelradigt textfält; fältet delas automatiskt upp i lika många jämnt fördelade positioner eller combs som värdet på parametern combNumber."
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Ställer in antalet fack för ett vanligt enkellinjigt textfält (fältet delas automatiskt upp i lika många jämnt fördelade positioner, eller fack, som värdet på parametern combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |
| combNumber | Int32 | Antalet combs att dela fältet i. |

### Returvärde

Om lyckat, returnera true; annars false.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


