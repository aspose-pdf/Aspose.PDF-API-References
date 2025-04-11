---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setzt die URL des Buttons
type: docs
weight: 340
url: /de/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl-Methode

Setzt die URL des Buttons.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Absende-Buttons. |
| url | String | Vollständig qualifizierte URL. |

### Rückgabewert

true, wenn die URL für den Button erfolgreich gesetzt wurde.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)