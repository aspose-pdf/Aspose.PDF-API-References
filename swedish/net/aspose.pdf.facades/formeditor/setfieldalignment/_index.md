---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-metod. Ställ in justeringsstilen för ett textfält
type: docs
weight: 260
url: /sv/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment metod

Ställ in justeringsstilen för ett textfält.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |
| alignment | Int32 | Definitionen av justeringsstilen, inklusive FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter och FormFieldFacade.AlignRight. |

### Returvärde

true om fältet hittades och justeringen ställdes in.

## Exempel

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Se Även

* klass [FormEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)