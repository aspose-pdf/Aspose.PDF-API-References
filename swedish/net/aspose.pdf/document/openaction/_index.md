---
title: Document.OpenAction
second_title: Aspose.PDF for .NET API Reference
description: Dokumentegenskap. Hämtar eller ställer in åtgärd som utförs vid dokumentöppning
type: docs
weight: 390
url: /sv/net/aspose.pdf/document/openaction/
---
## Document.OpenAction-egenskap

Hämtar eller ställer in åtgärd som utförs vid dokumentöppning.

```csharp
public IAppointment OpenAction { get; set; }
```

## Exempel

Exemplet visar hur man får CenterWindow-flaggan:

```csharp
Document document = new Document("sample.pdf");
IAppointment value = document.OpenAction;
```

### Se Även

* interface [IAppointment](../../../aspose.pdf.annotations/iappointment/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)