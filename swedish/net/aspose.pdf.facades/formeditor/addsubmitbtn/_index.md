---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Lägg till en skicka-knapp på formuläret
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn metod

Lägg till en skicka-knapp på formuläret.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Namn på den nya knappen. |
| page | Int32 | Sida där knappen kommer att placeras. |
| label | Sträng | Knappens text. |
| url | Sträng | URL för skicka-knappen. |
| llx | Enkel | Abscissa för det nedre vänstra hörnet. |
| lly | Enkel | Ordinate för det nedre vänstra hörnet. |
| urx | Enkel | Abscissa för det övre högra hörnet. |
| ury | Enkel | Ordinate för det övre högra hörnet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)