---
title: "Berechtigungen"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Dieses Enum repräsentiert die Berechtigungen des Benutzers für ein PDF."
type: docs
weight: 6560
url: /de/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Dieses Enum repräsentiert die Berechtigungen des Benutzers für ein PDF.

## Members
| Member-Name | Beschreibung |
| :- | :- |
| PRINT_DOCUMENT | (Security handlers of revision 2) Drucken Sie das Dokument.<br/>            (Security handlers of revision 3 or greater) Drucken Sie das Dokument <br/>            (möglicherweise nicht in höchster Qualitätsstufe, <br/>            abhängig davon, ob [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) ebenfalls gesetzt ist). |
| MODIFY_CONTENT | Ändern Sie den Inhalt des Dokuments durch andere Vorgänge <br/>            als die, die von [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) kontrolliert werden, <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/) und 11. |
| EXTRACT_CONTENT | (Security handlers of revision 2) Kopieren oder anderweitig extrahieren Sie <br/>            Text und Grafiken aus dem Dokument, einschließlich des Extrahierens <br/>            von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Nutzer <br/>            mit Behinderungen oder zu anderen Zwecken).<br/>            (Security handlers of revision 3 or greater) Kopieren oder anderweitig <br/>            extrahieren Sie Text und Grafiken aus dem Dokument durch Vorgänge <br/>            , die nicht von [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/) kontrolliert werden. |
| MODIFY_TEXT_ANNOTATIONS | Fügen Sie Textanmerkungen hinzu oder ändern Sie sie, füllen Sie interaktive Formularfelder aus, <br/>            und, wenn [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) ebenfalls gesetzt ist, erstellen oder ändern Sie interaktive Formular-<br/>            felder (einschließlich Signaturfelder). |
| FILL_FORM | (Security handlers of revision 3 or greater) Füllen Sie vorhandene <br/>            interaktive Formularfelder aus (einschließlich Signaturfelder), selbst wenn <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) deaktiviert ist. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Security handlers of revision 3 or greater) Extrahieren Sie Text und <br/>            Grafiken (zur Unterstützung der Barrierefreiheit für Nutzer mit Behinderungen <br/>            oder zu anderen Zwecken). |
| ASSEMBLE_DOCUMENT | (Security handlers of revision 3 or greater) Setzen Sie das Dokument zusammen <br/>            (einfügen, drehen oder löschen von Seiten und Erstellen von Lesezeichen oder Miniatur‑<br/>            Bildern), selbst wenn [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) deaktiviert ist. |
| PRINTING_QUALITY | (Security handlers of revision 3 or greater) Drucken Sie das Dokument zu <br/>            einer Darstellung, aus der eine getreue digitale Kopie des PDF‑Inhalts <br/>            erzeugt werden kann. Wenn dieses Bit deaktiviert ist (und Bit 3 gesetzt ist), <br/>            ist der Druck auf eine niedrigstufige Darstellung des Erscheinungsbildes beschränkt, <br/>            möglicherweise in verminderter Qualität. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

