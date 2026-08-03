---
title: "Form.GetSubmitFlags"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Returnerar inskickningsflaggorna för submit‑knapparna"
type: docs
weight: 270
url: /sv/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

Returnerar submit‑knappens inskickningsflaggor.

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det kvalificerade fältnamnet. |

### Returvärde

Inskickningsflaggor för knappen.

## Exempel

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Se även

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


