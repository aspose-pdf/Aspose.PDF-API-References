---
title: "FontRepository"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Führt die Schriftartensuche durch. Durchsucht systeminstallierte Schriftarten und Standard-PDF-Schriftarten.<br/>             Bietet außerdem die Möglichkeit, benutzerdefinierte Schriftarten zu öffnen."
type: docs
weight: 130
url: /de/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

Führt die Schriftartensuche durch. Durchsucht systeminstallierte Schriftarten und Standard-PDF-Schriftarten.<br/>             Bietet außerdem die Möglichkeit, benutzerdefinierte Schriftarten zu öffnen.

Der Typ FontRepository stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| FontRepository() | Initialisiert eine neue Instanz der Klasse FontRepository |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| substitutions | Ruft die Sammlung von Schriftart-Substitutionsstrategien ab. |
| sources | Ruft die Sammlung von Schriftquellen ab. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| find_font(font_name) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück. |
| find_font(font_name, ignore_case) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen zurück, wobei die Groß-/Kleinschreibung ignoriert oder berücksichtigt wird. |
| find_font(font_family_name, stl) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil zurück. |
| find_font(font_family_name, stl, ignore_case) | Sucht und gibt die Schriftart mit dem angegebenen Schriftartnamen und Schriftstil <br/>             zurück, wobei die Groß-/Kleinschreibung ignoriert oder berücksichtigt wird. |
| open_font(font_stream, font_type) | Öffnet die Schriftart mit dem angegebenen Schriftstrom. |
| open_font(font_file_path) | Öffnet die Schriftart mit dem angegebenen Pfad zur Schriftdatei. |
| open_font(font_file_path, metrics_file_path) | Öffnet die Schriftart mit dem angegebenen Pfad zur Schriftdatei. |
| load_fonts() | Lädt systeminstallierte Schriftarten und Standard‑Pdf‑Schriftarten. Diese Methode wurde entwickelt, um den Schriftarten‑Ladevorgang zu beschleunigen.<br/>Standardmäßig werden Schriftarten bei der ersten Anforderung einer Schriftart geladen. Die Verwendung dieser Methode lädt System‑ und Standard‑Pdf‑Schriftarten<br/>sofort, bevor ein Pdf‑Dokument geöffnet wird. |
| reload_fonts() | Lädt alle Schriftarten neu, die durch die Eigenschaft [sources](/pdf/python-net/aspose.pdf.text/fontrepository/) angegeben sind. |

### Siehe auch

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

