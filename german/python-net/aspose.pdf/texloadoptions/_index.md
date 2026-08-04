---
title: "TeXLoadOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt Optionen für das Laden/Importieren einer TeX-Datei in ein PDF-Dokument dar."
type: docs
weight: 1520
url: /de/python-net/aspose.pdf/texloadoptions/
---

## TeXLoadOptions class

Stellt Optionen für das Laden/Importieren einer TeX-Datei in ein PDF-Dokument dar.

Der TeXLoadOptions-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| TeXLoadOptions() | Initialisiert eine neue Instanz der TeXLoadOptions-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf, um alle erzeugten Warnungen zu behandeln. <br/>            Der WarningHandler gibt ein ReturnAction-Enum-Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und der Ladevorgang wird fortgesetzt, jedoch kann der Benutzer auch Abort zurückgeben, in welchem Fall der Ladevorgang beendet werden sollte. |
| load_format | Stellt das Dateiformat dar, das von [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/) beschrieben wird. |
| job_name | Liest/Setzt den Namen des Auftrags. |
| input_directory | Liest/Setzt das TeX-Eingabeverzeichnis. |
| output_directory | Liest/Setzt das TeX-Ausgabeverzeichnis. |
| repeat | Liest/Setzt das Flag, das angibt, ob es notwendig ist, den TeX‑Auftrag zweimal auszuführen, falls,<br/>            zum Beispiel Referenzen in Eingabe‑TeX‑Datei(en) vorhanden sind. Im Allgemeinen ist dieses Verhalten nützlich, wenn<br/>            die Engine während des Satzvorgangs Daten sammelt und in einer Hilfsdatei speichert,<br/>            und zwar beim ersten Durchlauf. Und beim zweiten Durchlauf verwendet die Engine diese Daten irgendwie. |
| subset_fonts | Liest/Setzt das Flag, das angibt, ob Schriftarten im Ausgabedatei subsettiert werden sollen oder nicht. |
| show_terminal_output | Liest/Setzt das Flag, das angibt, ob die Terminalausgabe in der Konsole angezeigt werden soll. |
| date_time | Liest/Setzt einen bestimmten Wert für Datums-/Zeit‑Primitiven wie \\year, \\month, \\day und \\time. |
| no_ligatures | Liest/Setzt ein Flag, das Ligaturen in allen Schriftarten deaktiviert. |
| rasterize_formulas | Liest/Setzt ein Flag, das das Rasterisieren mathematischer Formeln ermöglicht. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

