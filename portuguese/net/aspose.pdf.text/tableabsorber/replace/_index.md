---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: Método TableAbsorber. Substitui um AbsorbedTable por Table na página
type: docs
weight: 60
url: /pt/net/aspose.pdf.text/tableabsorber/replace/
---
## Método TableAbsorber.Replace

Substitui um [`AbsorbedTable`](../../absorbedtable/) por [`Table`](../../../aspose.pdf/table/) na página.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | Objeto de página do documento Pdf. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) a ser substituído. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) para substituir a tabela antiga. |

## Observações

Por favor, leve em conta que isso altera a coleção TableList. No caso de remover/substituir tabelas em um loop, por favor, use uma cópia da coleção TableList.

### Veja Também

* classe [Page](../../../aspose.pdf/page/)
* classe [AbsorbedTable](../../absorbedtable/)
* classe [Table](../../../aspose.pdf/table/)
* classe [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)