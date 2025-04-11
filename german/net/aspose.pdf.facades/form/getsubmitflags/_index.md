---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Gibt die Übermittlungsflags der Schaltflächen zurück
type: docs
weight: 270
url: /de/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags-Methode

Gibt die Übermittlungsflags der Schaltfläche zurück

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Der qualifizierte Feldname. |

### Rückgabewert

Übermittlungsflags der Schaltfläche.

## Beispiele

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Siehe auch

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)