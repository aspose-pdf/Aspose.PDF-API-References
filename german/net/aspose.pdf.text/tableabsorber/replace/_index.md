---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber-Methode. Ersetzt eine AbsorbedTable durch Table auf der Seite
type: docs
weight: 60
url: /de/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace-Methode

Ersetzt eine [`AbsorbedTable`](../../absorbedtable/) durch [`Table`](../../../aspose.pdf/table/) auf der Seite.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Seite | Pdf-Dokumentseitenobjekt. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) die ersetzt werden soll. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) um die alte Tabelle zu ersetzen. |

## Bemerkungen

Bitte beachten Sie, dass es die TableList-Sammlung ändert. Falls Tabellen in einer Schleife entfernt/ersetzt werden, verwenden Sie bitte eine Kopie der TableList-Sammlung.

### Siehe auch

* Klasse [Page](../../../aspose.pdf/page/)
* Klasse [AbsorbedTable](../../absorbedtable/)
* Klasse [Table](../../../aspose.pdf/table/)
* Klasse [TableAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)