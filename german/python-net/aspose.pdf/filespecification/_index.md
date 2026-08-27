---
title: "FileSpecification"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse, die eine eingebettete Datei darstellt."
type: docs
weight: 360
url: /de/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Klasse, die eine eingebettete Datei darstellt.

Der Typ FileSpecification stellt die folgenden Member bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| FileSpecification(file) | Initialisiert eine neue Instanz der Klasse FileSpecification. |
| FileSpecification(stream, name) | Initialisiert eine neue Instanz der Klasse FileSpecification. |
| FileSpecification(file, description) | Initialisiert eine neue Instanz der Klasse FileSpecification. |
| FileSpecification(stream, name, description) | Initialisiert eine neue Instanz der Klasse FileSpecification. |
| FileSpecification(file_name, annot) | Initialisiert eine neue Instanz der Klasse FileSpecification. |
| FileSpecification() | Erstelle neue leere Dateispezifikation. |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| encoding | Liest oder setzt das Kodierungsformat.<br/>            Mögliche Werte: Zip - Datei ist mit ZIP komprimiert, <br/>            None - Datei ist nicht komprimiert. |
| include_contents | Wenn true, werden die Inhalte der Datei in die Dateispezifikation aufgenommen. |
| encrypted_payload | Liest verschlüsselte Nutzdaten. |
| description | Liest oder setzt den Text, der mit der Dateispezifikation verknüpft ist. |
| af_relationship | Zugehörige Dateibeziehung. |
| stream_contents | Liest den Inhalt der Datei als Stream. <br/>            Der Inhalt wird nicht in den Speicher geladen, was eine Verringerung des Speicherverbrauchs ermöglicht.<br/>            Dieser Stream unterstützt jedoch keine Positionsänderung und die Length‑Eigenschaft. Wenn Sie diese Funktionen benötigen, verwenden Sie stattdessen die Contents‑Eigenschaft. |
| inhalt | Liest oder setzt die Inhaltsdatei. <br/>            Diese Eigenschaft gibt Daten zurück, die im Speicher geladen sind, was bei großen Daten zu einer Out‑of‑Memory‑Ausnahme führen kann.<br/>            Um den Speicherverbrauch zu reduzieren, verwenden Sie bitte StreamContents. |
| params | Liest Dateiparameter. |
| mime_type | Liest den Subtyp der eingebetteten Datei |
| Name | Liest oder setzt den Namen der Dateispezifikation. |
| unicode_name | Liest oder setzt den Unicode‑Namen der Dateispezifikation. |
| file_system | Liest oder setzt den Namen des Dateisystems. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| get_value(key) | Liest anwendungsspezifischen Parameter. |
| set_value(key, value) | Setzt anwendungsspezifischen Parameter. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

