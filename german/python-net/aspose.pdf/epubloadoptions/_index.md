---
title: "EpubLoadOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Enthält Optionen zum Laden/Importieren einer EPUB-Datei in ein PDF-Dokument."
type: docs
weight: 310
url: /de/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

Enthält Optionen zum Laden/Importieren einer EPUB-Datei in ein PDF-Dokument.

Der Typ EpubLoadOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| EpubLoadOptions() | Erstellt Standard-Ladeoptionen für die Konvertierung einer EPUB-Datei in ein PDF-Dokument. <br/>            Standard-PDF-Seitengröße - A4 300dpi 2480 × 3508. |
| EpubLoadOptions(page_size) | Initialisiert eine neue Instanz der Klasse EpubLoadOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf, um alle erzeugten Warnungen zu behandeln. <br/>            Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, jedoch kann der Benutzer auch Abort zurückgeben, in welchem Fall der Ladevorgang beendet werden sollte. |
| load_format | Stellt das Dateiformat dar, das von [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) beschrieben wird. |
| page_size | Liest oder setzt die Ausgabeseitengröße für den Import. |
| Rand | Liest die Referenz auf das Objekt, das Randinformationen darstellt. |
| margins_area_usage_mode | Stellt den Verwendungsmodus des Randbereichs dar – definiert die Behandlung <br/>              von Anweisungen (falls vorhanden) des CSS des importierten Dokuments<br/>              in Bezug auf die Nutzung der Ränder. |
| page_size_adjustment_mode | ACHTUNG! Die Funktion wurde implementiert, ist aber noch nicht in die öffentliche API aufgenommen, da ein Blocker-Problem in <br/>              der OSHARED-Schicht für das Beispieldokument aufgetreten ist.<br/>              <br/>             <br/>              Stellt den Verwendungsmodus der Seitengröße während der Konvertierung dar.<br/>             Formate (wie HTML, EPUB usw.) haben normalerweise ein fließendes Layout, sodass sie die erforderliche<br/>             Seitengröße anpassen können. Aber manchmal hat der Inhalt festgelegte horizontale Positionen oder Größen, die<br/>             es nicht erlauben, den Inhalt in die erforderliche Seitengröße zu passen.<br/>               In einem solchen Fall können wir festlegen, was in diesem Fall geschehen soll (z. B. wenn die Größe des Inhalts nicht in die<br/>             erforderliche Anfangsseitengröße des resultierenden PDF-Dokuments passt). |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

