---
title: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Diese Klasse beschreibt Regeln, die verwendet werden können, um den Adobe‑Preflight‑Fehler <br/>            \\\"Text cannot be mapped to Unicode\\\" zu lösen."
type: docs
weight: 20
url: /de/python-net/aspose.pdf.pdfaoptionclasses/tounicodeprocessingrules/
---

## ToUnicodeProcessingRules class

Diese Klasse beschreibt Regeln, die verwendet werden können, um den Adobe‑Preflight‑Fehler <br/>            \"Text cannot be mapped to Unicode\" zu lösen.

Der Typ ToUnicodeProcessingRules stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| ToUnicodeProcessingRules() | Konstruktor |
| ToUnicodeProcessingRules(remove_spaces) | Initialisiert eine neue Instanz der Klasse ToUnicodeProcessingRules |
| ToUnicodeProcessingRules(remove_spaces, map_non_linked_unicodes_on_space) | Initialisiert eine neue Instanz der Klasse ToUnicodeProcessingRules |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| remove_spaces_from_c_map_names | Einige Schriftarten haben ToUnicode-Zeichencodierungstabellen mit Leerzeichen in den Namen. Diese Leerzeichen können Fehler verursachen<br/>            bei der Unicode-Textzuordnung. Dieses Flag bewirkt, dass Leerzeichen aus den Namen von ToUnicode-Zeichencodierungstabellen entfernt werden.<br/>            Standardmäßig false. |
| map_non_linked_symbols_on_space | Einige Schriftarten liefern keine Informationen über Unicodes für bestimmte Textsymbole. <br/>            Dieser Informationsmangel führt zu einem Fehler "Text cannot be mapped to Unicode".<br/>            Verwenden Sie dieses Flag, um nicht verknüpfte Symbole auf das Unicode-"space" (Code 32) abzubilden. |

### Siehe auch

* namespace [aspose.pdf.pdfaoptionclasses](/pdf/python-net/aspose.pdf.pdfaoptionclasses/)
* assembly [Aspose.PDF](/pdf/python-net/)

