---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Dokumenteigenschaft. Ruft die Sammlung von Dokumentseiten ab oder legt sie fest. Beachten Sie, dass die Seiten in der Sammlung von 1 nummeriert sind.
type: docs
weight: 470
url: /de/net/aspose.pdf/document/pages/
---
## Document.Pages-Eigenschaft

Ruft die Sammlung von Dokumentseiten ab oder legt sie fest. Beachten Sie, dass die Seiten in der Sammlung von 1 nummeriert sind.

```csharp
public PageCollection Pages { get; }
```

## Beispiele

Das folgende Beispiel zeigt, wie man mit den Dokumentseiten arbeitet: Wie man die Anzahl der Seiten erhält und wie man das Rechteck der Startseite des Dokuments erhält.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Siehe auch

* Klasse [PageCollection](../../pagecollection/)
* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)