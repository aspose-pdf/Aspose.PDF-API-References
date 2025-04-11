---
title: Table.ImportDataTable
second_title: Aspose.PDF for .NET API Reference
description: Método de tabla. Importa datos de System.Data.DataTable a Aspose.Pdf.Table
type: docs
weight: 260
url: /es/net/aspose.pdf/table/importdatatable/
---
## ImportDataTable(DataTable, bool, int, int) {#importdatatable_1}

Importa datos de System.Data.DataTable a Aspose.Pdf.Table

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesImported, 
    int firstFilledRow, int firstFilledColumn)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| importedDataTable | DataTable | instancia fuente de System.Data.DataTable |
| isColumnNamesImported | Boolean | especifica si los nombres de las columnas se importarán como la primera fila |
| firstFilledRow | Int32 | especifica el número basado en cero de la primera fila en la tabla de destino desde la cual comenzará la importación; si la fila con dicho número (y algunas filas anteriores) están ausentes en la tabla de destino, se crearán primero |
| firstFilledColumn | Int32 | especifica el número de la primera columna de destino en la tabla de destino; la columna debe estar presente en la tabla de destino antes de comenzar la importación |

### Ver También

* clase [Table](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, bool, int, byte, int, int, bool) {#importdatatable}

Importa un objeto DataTable en la tabla.

```csharp
public void ImportDataTable(DataTable importedDataTable, bool isColumnNamesShown, 
    int firstFilledRow, byte firstFilledColumn, int maxRows, int maxColumns, 
    bool isHtmlSupported = false)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| importedDataTable | DataTable | El objeto DataTable que se va a importar. |
| isColumnNamesShown | Boolean | Especifica si los nombres de las columnas de la tabla de datos fuente se importarán como la primera fila. |
| firstFilledRow | Int32 | especifica el número basado en cero de la primera fila en la tabla de destino desde la cual comenzará la importación; si la fila con dicho número (y algunas filas anteriores) están ausentes en la tabla de destino, se crearán primero |
| firstFilledColumn | Byte | especifica el número de la primera columna de destino en la tabla de destino; la columna debe estar presente en la tabla de destino antes de comenzar la importación |
| maxRows | Int32 | Cantidad máxima de filas que se importarán de la tabla fuente. |
| maxColumns | Int32 | Cantidad máxima de columnas que se importarán de la tabla fuente. |
| isHtmlSupported | Boolean | Especifica si el texto es una cadena HTML. |

### Ver También

* clase [Table](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)

---

## ImportDataTable(DataTable, int[], int[], int, int, bool, bool) {#importdatatable_2}

Importa un objeto DataTable, pero no como una entidad completa. Solo se importan las filas y columnas especificadas.

```csharp
public void ImportDataTable(DataTable importedDataTable, int[] sourceRowList, 
    int[] sourceColumnList, int firstFilledRow, int firstFilledColumn, 
    bool showColumnNamesAsFirstRow, bool isHtmlSupported = false)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| importedDataTable | DataTable | El objeto DataTable que se va a importar. |
| sourceRowList | Int32[] | El arreglo de números de filas en el objeto DataTable fuente que deben ser importadas. La lista no debe ser nula y debe contener solo números de filas existentes, de lo contrario se lanzará una excepción. |
| sourceColumnList | Int32[] | El arreglo de números de columnas en el objeto DataTable fuente que deben ser importadas. La lista no debe ser nula y debe contener solo números de columnas existentes, de lo contrario se lanzará una excepción. |
| firstFilledRow | Int32 | El número de fila basado en cero de la primera celda en la tabla de destino desde la cual comenzará la importación. Si la tabla de destino no contiene esa fila, se creará (y todas las anteriores si es necesario) |
| firstFilledColumn | Int32 | El número de columna basado en cero de la primera celda en la tabla de destino desde la cual comenzará la importación. La tabla de destino debe contener esa columna antes de que comience la importación, de lo contrario se lanzará una excepción. |
| showColumnNamesAsFirstRow | Boolean | Especifica si los nombres de las columnas de la tabla de datos fuente se importarán como la primera fila. |
| isHtmlSupported | Boolean | Especifica si el texto es una cadena HTML. |

### Ver También

* clase [Table](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../../)