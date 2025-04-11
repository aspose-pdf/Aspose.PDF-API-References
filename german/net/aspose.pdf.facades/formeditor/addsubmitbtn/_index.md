---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Fügen Sie einen Absenden-Button zum Formular hinzu
type: docs
weight: 130
url: /de/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn-Methode

Fügen Sie einen Absenden-Button zum Formular hinzu.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des neuen Buttons. |
| page | Int32 | Seite, auf der der Button platziert wird. |
| label | String | Beschriftung des Buttons. |
| url | String | URL des Absenden-Buttons. |
| llx | Single | Abszisse der unteren linken Ecke. |
| lly | Single | Ordinate der unteren linken Ecke. |
| urx | Single | Abszisse der oberen rechten Ecke. |
| ury | Single | Ordinate der oberen rechten Ecke. |

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Siehe auch

* Klasse [FormEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)