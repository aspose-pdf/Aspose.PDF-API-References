---
title: "TableAbsorber.Replace"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TableAbsorber‑metod. Ersätter en AbsorbedTable med Table på sidan."
type: docs
weight: 60
url: /sv/net/aspose.pdf.text/tableabsorber/replace/
---
## TableAbsorber.Replace method

Ersätter en [`AbsorbedTable`](../../absorbedtable/) med [`Table`](../../../aspose.pdf/table/) på sidan.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | Pdf‑dokument sidobjekt. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) att ersättas. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) för att ersätta den gamla tabellen. |

## Anmärkningar

Observera att det ändrar TableList‑samlingen. Vid borttagning/ersättning av tabeller i en loop, använd en kopia av TableList‑samlingen.

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [AbsorbedTable](../../absorbedtable/)
* class [Table](../../../aspose.pdf/table/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


