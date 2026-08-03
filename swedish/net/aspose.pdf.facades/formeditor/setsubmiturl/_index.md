---
title: "FormEditor.SetSubmitUrl"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Anger URL för knappen"
type: docs
weight: 340
url: /sv/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Ställer in URL för knappen.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på inskickningsknappen. |
| url | String | Fullständigt kvalificerad URL. |

### Returvärde

Sant om URL för knappen sattes framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


