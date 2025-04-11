---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: TableAbsorber-metod. Ersätter en AbsorbedTable med Table på sidan
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace metod

Ersätter en [`AbsorbedTable`](../../absorbedtable/) med [`Table`](../../../aspose.pdf/table/) på sidan.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| page | Page | Pdf-dokument sidobjekt. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) som ska ersättas. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) för att ersätta gammal tabell. |

## Kommentarer

Vänligen ta hänsyn till att det ändrar TableList-samlingen. Vid borttagning/ersättning av tabeller i loop, vänligen använd en kopia av TableList-samlingen.

### Se Även

* klass [Page](../../../aspose.pdf/page/)
* klass [AbsorbedTable](../../absorbedtable/)
* klass [Table](../../../aspose.pdf/table/)
* klass [TableAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)