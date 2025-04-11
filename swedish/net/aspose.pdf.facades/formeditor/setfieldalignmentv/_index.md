---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Ställ in den vertikala justeringsstilen för ett textfält
type: docs
weight: 270
url: /sv/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV metod

Ställ in den vertikala justeringsstilen för ett textfält.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det kvalificerade fältnamnet. |
| alignment | Int32 | Definitionen av justeringsstilen, inklusive FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle och FormFieldFacade.AlignRight. |

### Returvärde

true om fältet hittades och justeringen framgångsrikt fylldes.

## Exempel

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)