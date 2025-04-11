---
title: Document.Optimize
second_title: Aspose.PDF for .NET API Reference
description: Dokumentmethode. Linearisieren Sie das Dokument, um die erste Seite so schnell wie möglich zu öffnen, die nächste Seite anzuzeigen oder über einen Link zur nächsten Seite so schnell wie möglich zu folgen, die Seite inkrementell anzuzeigen, während sie ankommt, wenn Daten für eine Seite über einen langsamen Kanal geliefert werden, die nützlichsten Daten zuerst anzuzeigen, Benutzerinteraktionen wie das Folgen eines Links zuzulassen, selbst bevor die gesamte Seite empfangen und angezeigt wurde. Das Aufrufen dieser Methode speichert das Dokument tatsächlich nicht. Im Gegenteil, das Dokument ist nur vorbereitet, um eine optimierte Struktur zu haben, rufen Sie dann Speichern auf, um das optimierte Dokument zu erhalten.
type: docs
weight: 750
url: /de/net/aspose.pdf/document/optimize/
---
## Document.Optimize-Methode

Linearisieren Sie das Dokument, um - die erste Seite so schnell wie möglich zu öffnen; - die nächste Seite anzuzeigen oder über einen Link zur nächsten Seite so schnell wie möglich zu folgen; - die Seite inkrementell anzuzeigen, während sie ankommt, wenn Daten für eine Seite über einen langsamen Kanal geliefert werden (die nützlichsten Daten zuerst anzeigen); - Benutzerinteraktionen, wie das Folgen eines Links, zuzulassen, selbst bevor die gesamte Seite empfangen und angezeigt wurde. Das Aufrufen dieser Methode speichert das Dokument tatsächlich nicht. Im Gegenteil, das Dokument ist nur vorbereitet, um eine optimierte Struktur zu haben, rufen Sie dann Speichern auf, um das optimierte Dokument zu erhalten.

```csharp
public void Optimize()
```

### Beispiele

Das folgende Beispiel zeigt, wie man ein PDF-Dokument für das Web optimiert.

```csharp
[C#]
	// The path to your PDF File.
	string pdfFilePath = "YOUR_PDF_FILE_PATH";

	// Open document
	using (Document pdfDocument = new Document(pdfFilePath))
	{

	// Optimize for web
	pdfDocument.Optimize();

	// Save output document
	pdfDocument.Save(pdfFilePath);
	}
```

```csharp
[VB.NET]

    ' The path to your PDF File.
    Dim pdfFilePath As String = "YOUR_PDF_FILE_PATH"
	
    ' Open document
    Using pdfDocument As Document = New Document(pdfFilePath)

        ' Optimize for web
        pdfDocument.Optimize()

        ' Save output document
        pdfDocument.Save(pdfFilePath)
    End Using
```

### Siehe auch

* Klasse [Document](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)