---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa un objeto absorbente de elementos de tabla. Realiza búsquedas y proporciona acceso a los resultados de búsqueda a través de la colección {@code TableAbsorber.TableList}. </p> <hr> <pre> The."
type: docs
weight: 4800
url: /es/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Representa un objeto absorbente de elementos de tabla. Realiza búsquedas y proporciona acceso a los resultados de búsqueda a través de la colección {@code TableAbsorber.TableList}. </p> <hr> <pre> El ejemplo muestra cómo encontrar una tabla en la primera página del documento PDF y reemplazar el texto en una celda de tabla. // Open document -> // Abrir documento Document doc = new Document("D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables -> // Crear objeto TableAbsorber para encontrar tablas TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber -> // Visitar la primera página con el absorbente absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it -> // Obtener acceso a la primera tabla en la página, su primera celda y los fragmentos de texto en ella TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell -> // Cambiar el texto del primer fragmento de texto en la celda fragment.setText("hi world"); // Save document -> // Guardar documento doc.save("D:\\Tests\\output.pdf"); </pre>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Inicializa una nueva instancia de {@code TableAbsorber}. </p> <hr> Realiza búsquedas de tablas y proporciona acceso a las tablas a través del objeto {@code TableList}. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Inicializa una nueva instancia de {@code TableAbsorber}. </p> <hr> Realiza búsquedas de tablas y proporciona acceso a las tablas a través del objeto {@code TableList}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getTableList](#getTableList--) | <p> Devuelve IList de solo lectura que contiene las tablas encontradas </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Obtiene las opciones de búsqueda de texto. </p> <hr> Permite definir varias opciones que se usarán durante la búsqueda de texto contenido en tablas. |
| [isUseFlowEngine](#isUseFlowEngine--) | Habilita un motor de reconocimiento de tablas alternativo que es superior en numerosos escenarios y es capaz de reconocer tablas sin bordes. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Elimina un {@code AbsorbedTable} de la página. </p> <hr> <p> Tenga en cuenta que cambia la colección TableList. En caso de eliminar/reemplazar tablas en un bucle, por favor use una copia de la colección TableList. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Reemplaza un {@code AbsorbedTable} con {@code Table} en la página. </p> <hr> <p> Tenga en cuenta que cambia la colección TableList. En caso de eliminar/reemplazar tablas en un bucle, por favor use una copia de la colección TableList. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Obtiene o establece las opciones de búsqueda de texto. </p> <hr> Permite definir varias opciones que se usarán durante la búsqueda de texto contenido en tablas. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Habilita un motor de reconocimiento de tablas alternativo que es superior en numerosos escenarios y es capaz de reconocer tablas sin bordes. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrae tablas del documento especificado. </p> <hr> <pre> El ejemplo muestra cómo extraer una tabla en la primera página del documento PDF. // Open document -> // Abrir documento Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables -> // Crear objeto TableAbsorber para encontrar tablas TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber -> // Visitar la primera página con el absorbente absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it -> // Obtener acceso a la primera tabla en la página, su primera celda y los fragmentos de texto en ella TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList.get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell -> // Cambiar el texto del primer fragmento de texto en la celda fragment.setText ("hi world"); // Save document -> // Guardar documento doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrae tablas en la página especificada </p> <hr> <pre> El ejemplo muestra cómo extraer una tabla en la primera página del documento PDF. // Open document -> // Abrir documento Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables -> // Crear objeto TableAbsorber para encontrar tablas TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber -> // Visitar la primera página con el absorbente absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it -> // Obtener acceso a la primera tabla en la página, su primera celda y los fragmentos de texto en ella TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList.get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell -> // Cambiar el texto del primer fragmento de texto en la celda fragment.setText ("hi world"); // Save document -> // Guardar documento doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Inicializa una nueva instancia de {@code TableAbsorber}. </p> <hr> Realiza búsquedas de tablas y proporciona acceso a las tablas a través del objeto {@code TableList}.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Inicializa una nueva instancia de {@code TableAbsorber}. </p> <hr> Realiza búsquedas de tablas y proporciona acceso a las tablas a través del objeto {@code TableList}.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Devuelve IList de solo lectura que contiene las tablas encontradas </p>

**Returns:**
{@code IGenericList<AbsorbedTable> objeto}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Obtiene las opciones de búsqueda de texto. </p> <hr> Permite definir varias opciones que se usarán durante la búsqueda de texto contenido en tablas.

**Returns:**
objeto TextSearchOptions

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Habilita un motor de reconocimiento de tablas alternativo que es superior en numerosos escenarios y es capaz de reconocer tablas sin bordes.

**Returns:**
valor booleano

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Elimina un {@code AbsorbedTable} de la página. </p> <hr> <p> Tenga en cuenta que cambia la colección TableList. En caso de eliminar/reemplazar tablas en un bucle, por favor use una copia de la colección TableList. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Reemplaza un {@code AbsorbedTable} con {@code Table} en la página. </p> <hr> <p> Tenga en cuenta que cambia la colección TableList. En caso de eliminar/reemplazar tablas en un bucle, por favor use una copia de la colección TableList. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Obtiene o establece las opciones de búsqueda de texto. </p> <hr> Permite definir varias opciones que se usarán durante la búsqueda de texto contenido en tablas.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Habilita un motor de reconocimiento de tablas alternativo que es superior en numerosos escenarios y es capaz de reconocer tablas sin bordes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| useFlowEngine |  | valor booleano |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrae tablas en el documento especificado. </p> <hr> <pre> El ejemplo muestra cómo extraer una tabla en la primera página del documento PDF. // Abrir documento Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Crear objeto TableAbsorber para encontrar tablas TableAbsorber absorber = new TableAbsorber(); // Visitar la primera página con el absorber absorber.visit(pdfDocument); // Obtener acceso a la primera tabla en la página, su primera celda y fragmentos de texto en ella TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Cambiar el texto del primer fragmento de texto en la celda fragment.setText (\"hi world\"); // Guardar documento doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrae tablas en la página especificada </p> <hr> <pre> El ejemplo muestra cómo extraer una tabla en la primera página del documento PDF. // Abrir documento Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Crear objeto TableAbsorber para encontrar tablas TableAbsorber absorber = new TableAbsorber(); // Visitar la primera página con el absorber absorber.visit(doc.getPages.get_item(1)); // Obtener acceso a la primera tabla en la página, su primera celda y fragmentos de texto en ella TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Cambiar el texto del primer fragmento de texto en la celda fragment.setText (\"hi world\"); // Guardar documento doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
