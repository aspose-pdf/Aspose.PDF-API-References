---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzt die Anzahl der Kämmchen für ein reguläres einzeiliges Textfeld, das automatisch in so viele gleichmäßig verteilte Positionen oder Kämmchen unterteilt wird, wie der Wert des Parameters combNumber.
type: docs
weight: 300
url: /de/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber-Methode

Setzt die Anzahl der Kämmchen für ein reguläres einzeiliges Textfeld (das Feld wird automatisch in so viele gleichmäßig verteilte Positionen oder Kämmchen unterteilt, wie der Wert des Parameters combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der qualifizierte Feldname. |
| combNumber | Int32 | Die Anzahl der Kämmchen, in die das Feld unterteilt werden soll. |

### Rückgabewert

Bei Erfolg true zurückgeben; andernfalls false.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)