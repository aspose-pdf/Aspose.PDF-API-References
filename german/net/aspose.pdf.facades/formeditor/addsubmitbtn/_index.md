---
title: AddSubmitBtn
second_title: Aspose.PDF für .NET-API-Referenz
description: Senden-Schaltfläche zum Formular hinzufügen.
type: docs
weight: 170
url: /de/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

Senden-Schaltfläche zum Formular hinzufügen.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name der neuen Schaltfläche. |
| page | Int32 | Seite, auf der die Schaltfläche platziert wird. |
| label | String | Schaltflächenbeschriftung. |
| url | String | URL des Submit-Buttons. |
| llx | Single | Abszisse der unteren linken Ecke. |
| lly | Single | Ordinate der unteren linken Ecke. |
| urx | Single | Abszisse der oberen rechten Ecke. |
| ury | Single | Ordinate der oberen rechten Ecke. |

### Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Siehe auch

* class [FormEditor](../../formeditor)
* namensraum [Aspose.Pdf.Facades](../../formeditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
