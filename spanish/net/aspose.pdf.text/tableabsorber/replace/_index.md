---
title: TableAbsorber.Replace
second_title: Aspose.PDF for .NET API Reference
description: Método TableAbsorber. Reemplaza un AbsorbedTable con Table en la página
type: docs
weight: 60
url: /es/net/aspose.pdf.text/tableabsorber/replace/
---
## Método TableAbsorber.Replace

Reemplaza un [`AbsorbedTable`](../../absorbedtable/) con [`Table`](../../../aspose.pdf/table/) en la página.

```csharp
public void Replace(Page page, AbsorbedTable oldTable, Table newTable)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | Objeto de página del documento Pdf. |
| oldTable | AbsorbedTable | [`AbsorbedTable`](../../absorbedtable/) que se va a reemplazar. |
| newTable | Table | [`Table`](../../../aspose.pdf/table/) para reemplazar la tabla antigua. |

## Observaciones

Tenga en cuenta que cambia la colección TableList. En caso de eliminar/reemplazar tablas en un bucle, utilice una copia de la colección TableList.

### Véase también

* clase [Page](../../../aspose.pdf/page/)
* clase [AbsorbedTable](../../absorbedtable/)
* clase [Table](../../../aspose.pdf/table/)
* clase [TableAbsorber](../)
* espacio de nombres [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* ensamblaje [Aspose.PDF](../../../)