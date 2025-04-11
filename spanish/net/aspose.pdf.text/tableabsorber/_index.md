---
title: Class TableAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Text.TableAbsorber. Representa un objeto absorbente de elementos de tabla. Realiza búsquedas y proporciona acceso a los resultados de búsqueda a través de la colección TableList.
type: docs
weight: 10790
url: /es/net/aspose.pdf.text/tableabsorber/
---
## Clase TableAbsorber

Representa un objeto absorbente de elementos de tabla. Realiza búsquedas y proporciona acceso a los resultados de búsqueda a través de la colección [`TableList`](./tablelist/).

```csharp
public class TableAbsorber
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TableAbsorber](tableabsorber/#constructor)() | Inicializa una nueva instancia de `TableAbsorber`. |
| [TableAbsorber](tableabsorber/#constructor_1)(TextSearchOptions) | Inicializa una nueva instancia de `TableAbsorber` con opciones de búsqueda de texto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [TableList](../../aspose.pdf.text/tableabsorber/tablelist/) { get; } | Devuelve una IList de solo lectura que contiene las tablas que se encontraron. |
| virtual [TextSearchOptions](../../aspose.pdf.text/tableabsorber/textsearchoptions/) { get; set; } | Obtiene o establece las opciones de búsqueda de texto. |
| [UseFlowEngine](../../aspose.pdf.text/tableabsorber/useflowengine/) { get; set; } | * Habilita un motor de reconocimiento de tablas alternativo que es superior en numerosos escenarios y es capaz de reconocer tablas sin bordes. Aún no admite la edición de tablas ni la obtención de estilos de texto. El valor predeterminado es falso; |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Remove](../../aspose.pdf.text/tableabsorber/remove/)(AbsorbedTable) | Elimina un [`AbsorbedTable`](../absorbedtable/) de la página. |
| [Replace](../../aspose.pdf.text/tableabsorber/replace/)(Page, AbsorbedTable, Table) | Reemplaza un [`AbsorbedTable`](../absorbedtable/) con [`Table`](../../aspose.pdf/table/) en la página. |
| [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit)(Document) | Extrae tablas en el documento especificado. |
| virtual [Visit](../../aspose.pdf.text/tableabsorber/visit/#visit_1)(Page) | Extrae tablas en la página especificada. |

## Ejemplos

El ejemplo demuestra cómo encontrar una tabla en la primera página del documento PDF y reemplazar el texto en una celda de la tabla.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TableAbsorber object to find tables
TableAbsorber absorber = new TableAbsorber();

// Visit first page with absorber
absorber.Visit(pdfDocument.Pages[1]);

// Get access to first table on page, their first cell and text fragments in it
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Change text of the first text fragment in the cell
fragment.Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### Ver También

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)