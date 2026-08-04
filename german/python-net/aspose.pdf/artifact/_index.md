---
title: "Artefakt"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Klasse stellt ein PDF-Artifact-Objekt dar."
type: docs
weight: 30
url: /de/python-net/aspose.pdf/artifact/
---

## Artifact class

Klasse stellt ein PDF-Artifact-Objekt dar.

Der Artifact-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| Artifact(type, sub_type) | Initialisiert eine neue Instanz der Artifact-Klasse |
| Artifact(type, sub_type) | Initialisiert eine neue Instanz der Artifact-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| custom_type | Liefert den Namen des Artefakttyps. Kann verwendet werden, wenn der Artefakttyp nicht standardmäßig ist. |
| custom_subtype | Liefert den Namen des Artefaktuntertyps. Kann verwendet werden, wenn der Artefaktuntertyp kein Standarduntertyp ist. |
| type | Liefert den Artefakttyp. |
| subtype | Liefert den Artefaktuntertyp. Wenn das Artefakt einen nicht‑standardmäßigen Untertyp hat, kann der Name des Untertyps über CustomSubtype gelesen werden. |
| inhalt | Liefert die Sammlung interner Operatoren des Artefakts. |
| Formular | Liefert das XForm des Artefakts (falls XForm verwendet wird). |
| Rechteck | Liefert das Rechteck des Artefakts. |
| position | Liefert oder setzt die Position des Artefakts.<br/>            Wenn diese Eigenschaft angegeben ist, werden Rand- und Ausrichtungswerte ignoriert. |
| right_margin | Rechter Rand des Artefakts. <br/>            Wenn die Position explizit angegeben ist (in der Position‑Eigenschaft), wird dieser Wert ignoriert. |
| left_margin | Linker Rand des Artefakts. <br/>            Wenn die Position explizit angegeben ist (in der Position‑Eigenschaft), wird dieser Wert ignoriert. |
| top_margin | Oberer Rand des Artefakts. <br/>            Wenn die Position explizit angegeben ist (in der Position‑Eigenschaft), wird dieser Wert ignoriert. |
| bottom_margin | Unterer Rand des Artefakts. <br/>            Wenn die Position explizit angegeben ist (in der Position‑Eigenschaft), wird dieser Wert ignoriert. |
| artifact_horizontal_alignment | Horizontale Ausrichtung des Artefakts. <br/>            Wenn die Position explizit angegeben ist (in der Position‑Eigenschaft), wird dieser Wert ignoriert. |
| artifact_vertical_alignment | Vertikale Ausrichtung des Artefakts. <br/>            Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| rotation | Liest oder setzt den Rotationswinkel des Artefakts. |
| text | Liest den Text des Artefakts. |
| image | Liest das Bild des Artefakts (falls vorhanden). |
| opacity | Liest oder setzt die Deckkraft des Artefakts. Mögliche Werte liegen im Bereich 0..1. |
| lines | Zeilen des mehrzeiligen Text-Artefakts. |
| text_state | Textzustand für den Artefakt-Text. |
| is_background | Wenn true, wird das Artefakt hinter dem Seiteninhalt platziert. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| set_image(image_stream) | Setzt das Bild des Artefakts. |
| set_image(image_name) | Setzt das Bild des Artefakts. |
| set_text(formatted_text) | Setzt den Text des Artefakts. |
| set_text_and_state(text, text_state) | Setzt Text und Texteigenschaften des Artefakts. |
| set_lines_and_state(text, text_state) | Setzt Text und Texteigenschaften des Artefakts. Ermöglicht die Angabe mehrerer Zeilen. |
| set_pdf_page(page) | Setzt die PDF-Seite, die als Artefakt auf der Dokumentenseite platziert wird. |
| get_value(name) | Liest benutzerdefinierten Wert des Artefakts. |
| set_value(name, value) | Setzt benutzerdefinierten Wert des Artefakts. |
| remove_value(name) | Entferne benutzerdefinierten Wert aus dem Artefakt. |
| begin_updates() | Starten Sie verzögerte Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. <br/>            In der Regel werden Artefakt‑Operatoren jederzeit geändert, wenn eine Artefakt‑Eigenschaft geändert wurde. Dies führt dazu, dass der Seiteninhalt<br/>            jedes Mal geändert wird, wenn das Artefakt geändert wurde. Um diesen Effekt zu vermeiden, setzen Sie alle Artefakt‑Updates zwischen den Aufrufen StartUpdates/SaveUpdates.<br/>            Dadurch wird der Seiteninhalt nur einmal geändert. |
| save_updates() | Speichert alle Updates im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

