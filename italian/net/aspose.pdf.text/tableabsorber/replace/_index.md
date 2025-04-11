---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: Metodo TableAbsorber. Sostituisce un AbsorbedTable con Table nella pagina
type: docs
weight: 60
url: /it/net/aspose.pdf.text/tableabsorber/replace/
---
## Metodo TableAbsorber.Replace

Sostituisce un [`AbsorbedTable`](../../absorbedtable/) con [`Table`](../../../aspose.pdf/table/) nella pagina.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | Oggetto pagina del documento Pdf. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) da sostituire. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) per sostituire la vecchia tabella. |

## Osservazioni

Si prega di tenere in considerazione che modifica la collezione TableList. In caso di rimozione/sostituzione di tabelle in un ciclo, si prega di utilizzare una copia della collezione TableList.

### Vedi Anche

* classe [Page](../../../aspose.pdf/page/)
* classe [AbsorbedTable](../../absorbedtable/)
* classe [Table](../../../aspose.pdf/table/)
* classe [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)