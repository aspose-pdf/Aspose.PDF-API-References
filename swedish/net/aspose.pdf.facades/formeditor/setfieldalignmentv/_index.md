---
title: "FormEditor.SetFieldAlignmentV"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor metod. Ställ in den vertikala justeringsstilen för ett textfält"
type: docs
weight: 270
url: /sv/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

Ställ in den vertikala justeringsstilen för ett textfält.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |
| alignment | Int32 | Justeringstilsdefinitionen, inklusive FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle och FormFieldFacade.AlignRight. |

### Returvärde

Sant om fältet hittades och justeringen fylldes framgångsrikt.

## Exempel

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Se även

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


