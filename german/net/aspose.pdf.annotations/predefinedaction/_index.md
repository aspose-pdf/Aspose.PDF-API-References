---
title: PredefinedAction
second_title: Aspose.PDF für .NET-API-Referenz
description: Definiert verschiedene Aktionen die von einer PDF-Datei ausgelöst werden können.
type: docs
weight: 950
url: /de/net/aspose.pdf.annotations/predefinedaction/
---
## PredefinedAction enumeration

Definiert verschiedene Aktionen, die von einer PDF-Datei ausgelöst werden können.

```csharp
public enum PredefinedAction
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| FirstPage | `0` | Eine benannte Aktion, um zur ersten Seite zu gehen. |
| LastPage | `1` | Eine benannte Aktion, um zur letzten Seite zu gehen. |
| NextPage | `2` | Eine benannte Aktion, um zur nächsten Seite zu gehen. |
| PrevPage | `3` | Eine benannte Aktion, um zur vorherigen Seite zu gehen. |
| PrintDialog | `4` | Eine benannte Aktion zum Öffnen eines Druckdialogs (JavaScript). |
| Print | `5` | Eine benannte Aktion zum Öffnen eines Druckdialogs. |
| Bookmarks_ExpanCurrentBookmark | `6` | Eine benannte Aktion zum Suchen des aktuellen Lesezeichens. |
| Bookmarks_HightlightCurrentBookmark | `7` | Eine benannte Aktion zum Hervorheben des aktuellen Lesezeichens. |
| Document_AttachFile | `8` | Eine benannte Aktion zum Hinzufügen von Dateianhängen. |
| Document_CropPages | `9` | Eine benannte Aktion zum Zuschneiden von Dokumentseiten. |
| Document_DeletePages | `10` | Eine benannte Aktion zum Löschen von Dokumentseiten. |
| Document_ExtractPages | `11` | Eine benannte Aktion zum Extrahieren von Dokumentseiten. |
| Document_InsertPages | `12` | Eine benannte Aktion zum Einfügen von Seiten aus einem Dokument. |
| Document_ReplacePages | `13` | Eine benannte Aktion zum Ersetzen von Dokumentseiten. |
| Document_RotatePages | `14` | Eine benannte Aktion zum Drehen von Dokumentseiten. |
| Edit_CheckSpelling_InComFieldEdit | `15` | Eine benannte Aktion zur Rechtschreibprüfung in Kommentaren. |
| Edit_Find | `16` | Eine benannte Aktion, die gesucht werden soll. |
| Edit_Preferences | `17` | Eine benannte Aktion zum Bearbeiten von Einstellungen. |
| Edit_Search | `18` | Eine benannte Aktion zum Suchen. |
| File_AttachToEmail | `19` | Eine benannte Aktion zum Anhängen des aktuellen PDF-Dokuments an eine E-Mail-Nachricht. |
| File_Close | `20` | Eine benannte Aktion zum Schließen des Dokuments. |
| File_CreatePDF_FromScanner | `21` | Eine benannte Aktion zum Erstellen eines PDF-Dokuments vom Scanner. |
| File_CreatePDF_FromWebPage | `22` | Eine benannte Aktion zum Erstellen eines PDF-Dokuments von einer Webseite. |
| File_Exit | `23` | Eine benannte Aktion zum Beenden des PDF-Readers. |
| File_Organizer_OpenOrganizer | `24` | Eine benannte Aktion zum Öffnen des Organizers. |
| File_Print | `25` | Eine benannte Aktion zum Drucken des Dokuments. |
| File_Properties | `26` | Eine benannte Aktion zum Öffnen der Dokumenteigenschaften. |
| File_SaveAs | `27` | Eine benannte Aktion zum Speichern des Dokuments unter einem anderen Namen. |
| Miscellaneous_ZoomIn | `28` | Eine benannte Aktion zum Vergrößern des Dokuments. |
| Miscellaneous_ZoomOut | `29` | Eine benannte Aktion zum Verkleinern des Dokuments. |
| PageImages_PrintPages | `30` | Eine benannte Aktion zum Drucken der Dokumentseiten. |
| View_GoTo_NextView | `31` | Eine benannte Aktion, um zur nächsten Ansicht zu wechseln. |
| View_GoTo_Page | `32` | Eine benannte Aktion, um zu einer bestimmten Seite zu gehen. |
| View_GoTo_PreDocument | `33` | Eine benannte Aktion, um zum vorherigen Dokument zu gehen. |
| View_GoTo_PreView | `34` | Eine benannte Aktion, um zur vorherigen Ansicht zu wechseln. |
| View_NavigationPanels_Articles | `35` | Eine benannte Aktion zum Ein-/Ausblenden des Artikelbereichs. |
| View_NavigationPanels_Attachments | `36` | Eine benannte Aktion zum Ein-/Ausblenden des Anlagenbereichs. |
| View_NavigationPanels_Boomarks | `37` | Eine benannte Aktion zum Ein-/Ausblenden des Lesezeichenfelds. |
| View_NavigationPanels_Comments | `38` | Eine benannte Aktion zum Ein-/Ausblenden des Kommentarbereichs. |
| View_NavigationPanels_Fields | `39` | Eine benannte Aktion zum Ein-/Ausblenden von Feldern. |
| View_NavigationPanels_Layers | `40` | Eine benannte Aktion zum Ein-/Ausblenden des Ebenenbedienfelds. |
| View_NavigationPanels_ModelTree | `41` | Eine benannte Aktion zum Ein-/Ausblenden des Modellbaumfensters. |
| View_NavigationPanels_Pages | `42` | Eine benannte Aktion zum Ein-/Ausblenden des Seitenbereichs. |
| View_NavigationPanels_Signatures | `43` | Eine benannte Aktion zum Ein-/Ausblenden des Signaturbereichs. |
| View_PageDisplay_SinglePage | `44` | Eine benannte Aktion zum Anzeigen einer einzelnen Seite. |
| View_PageDisplay_SinglePageContinuous | `45` | Eine benannte Aktion zum Anzeigen einer einzelnen fortlaufenden Seite. |
| View_PageDisplay_TwoUp | `46` | Eine benannte Aktion zum Anzeigen von Seiten als Two-Up. |
| View_PageDisplay_TwoUpContinuous | `47` | Eine benannte Aktion zur fortlaufenden Anzeige von Seiten im Doppelnutzen. |
| View_Toolbars_AdvanceEditing | `48` | Eine benannte Aktion zum Ein-/Ausblenden der erweiterten Bearbeitungssymbolleiste. |
| View_Toolbars_CommentMarkup | `49` | Eine benannte Aktion zum Ein-/Ausblenden der Kommentarsymbolleiste. |
| View_Toolbars_Edit | `50` | Eine benannte Aktion zum Ein-/Ausblenden der Bearbeitungssymbolleiste. |
| View_Toolbars_File | `51` | Eine benannte Aktion zum Ein-/Ausblenden der Dateisymbolleiste. |
| View_Toolbars_Find | `52` | Eine benannte Aktion zum Ein-/Ausblenden der Suchsymbolleiste. |
| View_Toolbars_Forms | `53` | Eine benannte Aktion zum Ein-/Ausblenden der Formularsymbolleiste. |
| View_Toolbars_Measuring | `54` | Eine benannte Aktion zum Ein-/Ausblenden der Messsymbolleiste. |
| View_Toolbars_ObjectData | `55` | Eine benannte Aktion zum Ein-/Ausblenden der Symbolleiste für Objektdaten. |
| View_Toolbars_PageDisplay | `56` | Eine benannte Aktion zum Ein-/Ausblenden der Symbolleiste für die Seitenanzeige. |
| View_Toolbars_PageNavigation | `57` | Eine benannte Aktion zum Ein-/Ausblenden der Navigationssymbolleiste. |
| View_Toolbars_PrintProduction | `58` | Eine benannte Aktion zum Ein-/Ausblenden der Symbolleiste für die Druckproduktion. |
| View_Toolbars_PropertiesBar | `59` | Eine benannte Aktion zum Ein-/Ausblenden der Eigenschaftssymbolleiste. |
| View_Toolbars_Redaction | `60` | Eine benannte Aktion zum Ein-/Ausblenden der Schwärzungssymbolleiste. |
| View_Toolbars_SelectZoom | `61` | Eine benannte Aktion zum Ein-/Ausblenden der Auswahl- und Zoom-Symbolleiste. |
| View_Toolbars_Tasks | `62` | Eine benannte Aktion zum Ein-/Ausblenden der Aufgabensymbolleiste. |
| View_Toolbars_Typewriter | `63` | Eine benannte Aktion zum Ein-/Ausblenden der Schreibmaschinen-Symbolleiste. |
| View_Zoom_ActualSize | `64` | Eine benannte Aktion zum Anzeigen von Seiten in Originalgröße. |
| View_Zoom_FitHeight | `65` | Eine benannte Aktion, um die Seite an die Höhe anzupassen. |
| View_Zoom_FitPage | `66` | Eine benannte Aktion zum Einpassen in die Seite. |
| View_Zoom_FitVisible | `67` | Eine benannte Aktion zur Anpassung der Seitensichtbarkeit. |
| View_Zoom_FitWidth | `68` | Eine benannte Aktion, um die Seite an die Breite anzupassen. |
| View_Zoom_ZoomTo | `69` | Eine benannte Aktion zum Zoomen. |
| Window_FullScreenMode | `70` | Eine benannte Aktion, um das Dokument im Vollbildmodus anzuzeigen. |

### Siehe auch

* namensraum [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
