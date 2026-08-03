---
title: "FormEditor.AddSubmitBtn"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Lägg till en skickaknapp på formuläret"
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

Lägg till en skicka‑knapp på formuläret.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på ny knapp. |
| sida | Int32 | Sida där knappen kommer att placeras. |
| label | String | Knapptext. |
| url | String | URL för skickaknappen. |
| llx | Single | Abskissa för det nedre vänstra hörnet. |
| lly | Single | Ordinat för det nedre vänstra hörnet. |
| urx | Single | Abskissa för det övre högra hörnet. |
| ury | Single | Ordinat för det övre högra hörnet. |

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


