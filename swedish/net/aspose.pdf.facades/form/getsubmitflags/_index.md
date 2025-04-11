---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Returnerar submit-knapparnas inlämningsflaggor
type: docs
weight: 270
url: /sv/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags metod

Returnerar submit-knappens inlämningsflaggor

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Det kvalificerade fältnamnet. |

### Returvärde

Inlämningsflaggor för knappen.

## Exempel

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Se Även

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)