---
title: Table.ImportDataView
second_title: Aspose.PDF for .NET API Reference
description: Método de tabla. Importa los datos de un objeto DataView en la tabla
type: docs
weight: 270
url: /es/net/aspose.pdf/table/importdataview/
---
## Método Table.ImportDataView

Importa los datos de un objeto DataView en la tabla.

```csharp
public void ImportDataView(DataView sourceDataView, bool isColumnNamesImported, int firstFilledRow, 
    int firstFilledColumn, int maxRows, int maxColumns)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceDataView | DataView | El objeto DataView que se va a importar. |
| isColumnNamesImported | Boolean | Indica si los nombres de las columnas se importarán como la primera fila. |
| firstFilledRow | Int32 | El número de fila basado en cero de la primera celda en la tabla de destino desde la cual comenzará la importación. Si la tabla de destino no contiene esa fila, se creará (y todas las anteriores si es necesario). |
| firstFilledColumn | Int32 | El número de columna basado en cero de la primera celda en la tabla de destino desde la cual comenzará la importación. La tabla de destino debe contener esa columna antes de que comience la importación; de lo contrario, se lanzará una excepción. |
| maxRows | Int32 | Cantidad máxima de filas que se importarán desde el DataView de origen. |
| maxColumns | Int32 | Máximas columnas que se importarán desde el DataView de origen. |

### Ver También

* clase [Table](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)