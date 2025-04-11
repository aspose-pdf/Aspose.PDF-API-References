---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Ändern Sie ein einzeiliges Textfeld in ein mehrzeiliges.
type: docs
weight: 350
url: /de/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple-Methode

Ändern Sie ein einzeiliges Textfeld in ein mehrzeiliges.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der qualifizierte Feldname. |

### Rückgabewert

Bei Erfolg true zurückgeben; andernfalls false.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)