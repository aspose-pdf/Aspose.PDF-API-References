---
title: SetFieldCombNumber
second_title: Aspose.PDF för .NET API Referens
description: Ställer in antalet kammar för ett vanligt enrads textfält fältet är automatiskt uppdelat i lika många positioner med lika mellanrum eller kammar som värdet på parametern combNumber.
type: docs
weight: 340
url: /sv/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Ställer in antalet kammar för ett vanligt enrads textfält (fältet är automatiskt uppdelat i lika många positioner med lika mellanrum, eller kammar, som värdet på parametern combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |
| combNumber | Int32 | Antalet kammar att dela fältet i. |

### Returvärde

Om det lyckas, returnera sant; annars falskt.

### Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Se även

* class [FormEditor](../../formeditor)
* namnutrymme [Aspose.Pdf.Facades](../../formeditor)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
