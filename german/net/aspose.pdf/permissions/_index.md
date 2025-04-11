---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Permissions Enum. Dieses Enum repräsentiert die Berechtigungen der Benutzer für ein PDF
type: docs
weight: 8480
url: /de/net/aspose.pdf/permissions/
---
## Berechtigungen Enumeration

Dieses Enum repräsentiert die Berechtigungen des Benutzers für ein PDF.

```csharp
[Flags]
public enum Permissions
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| PrintDocument | `4` | (Sicherheits-Handler der Revision 2) Dokument drucken. (Sicherheits-Handler der Revision 3 oder höher) Dokument drucken (möglicherweise nicht in der höchsten Qualitätsstufe, abhängig davon, ob PrintingQuality ebenfalls gesetzt ist). |
| ModifyContent | `8` | Den Inhalt des Dokuments durch andere Operationen als die, die durch ModifyTextAnnotations, FillForm und 11 kontrolliert werden, ändern. |
| ExtractContent | `10` | (Sicherheits-Handler der Revision 2) Text und Grafiken aus dem Dokument kopieren oder anderweitig extrahieren, einschließlich des Extrahierens von Text und Grafiken (zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder für andere Zwecke). (Sicherheits-Handler der Revision 3 oder höher) Text und Grafiken aus dem Dokument durch andere Operationen als die, die durch ExtractContentWithDisabilities kontrolliert werden, kopieren oder anderweitig extrahieren. |
| ModifyTextAnnotations | `20` | Textannotationen hinzufügen oder ändern, interaktive Formularfelder ausfüllen und, falls ModifyContent ebenfalls gesetzt ist, interaktive Formularfelder (einschließlich Unterschriftsfelder) erstellen oder ändern. |
| FillForm | `100` | (Sicherheits-Handler der Revision 3 oder höher) Vorhandene interaktive Formularfelder (einschließlich Unterschriftsfelder) ausfüllen, selbst wenn ModifyTextAnnotations nicht gesetzt ist. |
| ExtractContentWithDisabilities | `200` | (Sicherheits-Handler der Revision 3 oder höher) Text und Grafiken extrahieren (zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder für andere Zwecke). |
| AssembleDocument | `400` | (Sicherheits-Handler der Revision 3 oder höher) Dokument zusammenstellen (Seiten einfügen, drehen oder löschen und Lesezeichen oder Miniaturansichten erstellen), selbst wenn ModifyContent nicht gesetzt ist. |
| PrintingQuality | `800` | (Sicherheits-Handler der Revision 3 oder höher) Dokument drucken in eine Darstellung, aus der eine treue digitale Kopie des PDF-Inhalts erzeugt werden könnte. Wenn dieses Bit nicht gesetzt ist (und Bit 3 gesetzt ist), ist das Drucken auf eine niedrigere Darstellung des Erscheinungsbildes beschränkt, möglicherweise von minderer Qualität. |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)