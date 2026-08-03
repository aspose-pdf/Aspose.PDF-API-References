---
title: "FormEditor.SetFieldAlignment"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Ställer in justeringsstilen för ett textfält"
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

Ställ in justeringsstilen för ett textfält.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |
| alignment | Int32 | Definitionen av justeringsstil, inklusive FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter och FormFieldFacade.AlignRight. |

### Returvärde

true om fältet hittades och justeringen sattes.

## Exempel

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


