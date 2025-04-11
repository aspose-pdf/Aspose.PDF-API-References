---
title: PdfContentEditor.CreateBookmarksAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt ein Lesezeichen mit der angegebenen Aktion
type: docs
weight: 120
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/
---
## PdfContentEditor.CreateBookmarksAction-Methode

Erstellt ein Lesezeichen mit der angegebenen Aktion.

```csharp
public void CreateBookmarksAction(string title, Color color, bool boldFlag, bool italicFlag, 
    string file, string actionType, string destination)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| title | String | Der Titel des Lesezeichens. |
| color | Color | Die Farbe des Titels des Lesezeichens. |
| boldFlag | Boolean | Das Flag für fette Schrift. |
| italicFlag | Boolean | Das Flag für kursive Schrift. |
| file | String | Eine andere Datei oder Anwendung, die erforderlich ist, wenn der Aktionstyp "GoToR" oder "Launch" ist. |
| actionType | String | Der Aktionstyp. Der Wert kann sein: "GoToR", "Launch", "GoTo", "URI". |
| destination | String | Das lokale Ziel oder entfernte Ziel oder URL. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarksAction("bookmark title",
    System.Drawing.Color.Red, true, true, null, "GoTo", 1/*page number*/);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)