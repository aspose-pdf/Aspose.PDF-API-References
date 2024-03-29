---
title: SetSubmitUrl
second_title: Aspose.PDF für .NET-API-Referenz
description: Legt die URL der Schaltfläche fest.
type: docs
weight: 380
url: /de/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Legt die URL der Schaltfläche fest.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Schaltflächenname senden. |
| url | String | Vollqualifizierte URL. |

### Rückgabewert

true, wenn die URL für die Schaltfläche erfolgreich festgelegt wurde.

### Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Siehe auch

* class [FormEditor](../../formeditor)
* namensraum [Aspose.Pdf.Facades](../../formeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
