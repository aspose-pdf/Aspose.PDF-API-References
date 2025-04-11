---
title: Document.OpenAction
second_title: Aspose.PDF for .NET API Reference
description: Dokumenteneigenschaft. Ruft die beim Öffnen des Dokuments ausgeführte Aktion ab oder legt sie fest
type: docs
weight: 390
url: /de/net/aspose.pdf/document/openaction/
---
## Document.OpenAction-Eigenschaft

Ruft die beim Öffnen des Dokuments ausgeführte Aktion ab oder legt sie fest.

```csharp
public IAppointment OpenAction { get; set; }
```

## Beispiele

Das Beispiel zeigt, wie man das CenterWindow-Flag abruft:

```csharp
Document document = new Document("sample.pdf");
IAppointment value = document.OpenAction;
```

### Siehe auch

* Schnittstelle [IAppointment](../../../aspose.pdf.annotations/iappointment/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)