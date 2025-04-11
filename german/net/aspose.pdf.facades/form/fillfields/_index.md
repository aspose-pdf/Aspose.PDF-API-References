---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Füllt die Textfeldfelder mit Textwerten und speichert das Dokument. Relevant für signierte Dokumente. Hinweis: Nur auf Textfelder anwendbar. Sowohl die Feldnamen als auch die Werte sind groß- und kleinschreibungsempfindlich.
type: docs
weight: 140
url: /de/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields-Methode

Füllt die Textfeldfelder mit Textwerten und speichert das Dokument. Relevant für signierte Dokumente. Hinweis: Nur auf Textfelder anwendbar. Sowohl die Feldnamen als auch die Werte sind groß- und kleinschreibungsempfindlich.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldNames | String[] | Namen der Felder. |
| fieldValues | String[] | Neue Werte der Felder. |
| output | Stream& | Stream, in dem das Dokument gespeichert wird. |

### Rückgabewert

true, wenn Felder gefunden und erfolgreich ausgefüllt wurden.

## Beispiele

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)