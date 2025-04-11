---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Método de tabla. Importa un array unidimensional de datos en la tabla. La importación se realiza una celda por cada elemento del array y comienza desde la fila y columna definidas en los parámetros. Durante la importación, si se detecta que las filas necesarias aún están ausentes, es decir, la tabla de destino es demasiado pequeña para absorber todos los datos, se crearán las filas necesarias.
type: docs
weight: 250
url: /es/net/aspose.pdf/table/importarray/
---
## Método Table.ImportArray

Importa un array unidimensional de datos en la tabla. La importación se realiza una celda por cada elemento del array y comienza desde la fila y columna definidas en los parámetros. Durante la importación, si se detecta que las filas necesarias aún están ausentes (es decir, la tabla de destino es demasiado pequeña para absorber todos los datos), se crearán las filas necesarias.

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| importedArray | Object[] | datos importados, los nulos se importarán como cadenas vacías |
| firstFilledRow | Int32 | define el número de la primera fila objetivo en la tabla de destino desde la cual comenzará la importación. Si la cantidad de filas en la tabla de destino es menor que la requerida, se crearán primero las filas faltantes. |
| firstFilledColumn | Int32 | especifica el número de la primera columna objetivo en la tabla de destino, la columna debe estar presente en la tabla de destino antes del inicio de la importación |
| isLeftColumnsFilled | Boolean | Si 'isLeftColumnsFilled'=false, entonces en la segunda y todas las filas llenas subsiguientes, las celdas que están a la izquierda de firstFilledColumn serán omitidas |

### Ver También

* clase [Table](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)