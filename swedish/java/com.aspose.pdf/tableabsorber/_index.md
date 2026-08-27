---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar ett absorberande objekt för tabell-element. Utför sökning och ger åtkomst till sökresultat via {@code TableAbsorber.TableList} samling. </p> <hr> <pre> The."
type: docs
weight: 4800
url: /sv/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Representerar ett absorberande objekt för tabell-element. Utför sökning och ger åtkomst till sökresultat via {@code TableAbsorber.TableList} samling. </p> <hr> <pre> Exemplet visar hur man hittar en tabell på den första PDF-dokumentets sida och ersätter texten i en tabellcell. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages().get_Item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Change text of the first text fragment in the cell fragment.setText("hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Initierar en ny instans av {@code TableAbsorber}. </p> <hr> Utför sökning efter tabeller och ger åtkomst till tabellerna via {@code TableList} objekt. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initierar en ny instans av {@code TableAbsorber}. </p> <hr> Utför sökning efter tabeller och ger åtkomst till tabellerna via {@code TableList} objekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTableList](#getTableList--) | <p> Returnerar en skrivskyddad IList som innehåller tabeller som hittades </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Hämtar alternativ för textsökning. </p> <hr> Tillåter att definiera flera alternativ som kommer att användas under sökning av text i tabeller. |
| [isUseFlowEngine](#isUseFlowEngine--) | Aktivera en alternativ tabelligenkänningsmotor som är överlägsen i många scenarier och kan känna igen tabeller utan kanter. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Tar bort en {@code AbsorbedTable} från sidan. </p> <hr> <p> Vänligen notera att detta ändrar TableList-samlingen. Vid borttagning/ersättning av tabeller i en loop, använd en kopia av TableList-samlingen. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Ersätter en {@code AbsorbedTable} med {@code Table} på sidan. </p> <hr> <p> Vänligen notera att detta ändrar TableList-samlingen. Vid borttagning/ersättning av tabeller i en loop, använd en kopia av TableList-samlingen. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Hämtar eller anger alternativ för textsökning. </p> <hr> Tillåter att definiera flera alternativ som kommer att användas under sökning av text i tabeller. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Aktivera en alternativ tabelligenkänningsmotor som är överlägsen i många scenarier och kan känna igen tabeller utan kanter. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extraherar tabeller i det angivna dokumentet. </p> <hr> <pre> Exemplet visar hur man extraherar en tabell på den första PDF-dokumentets sida. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extraherar tabeller på den angivna sidan </p> <hr> <pre> Exemplet visar hur man extraherar en tabell på den första PDF-dokumentets sida. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Initierar en ny instans av {@code TableAbsorber}. </p> <hr> Utför sökning efter tabeller och ger åtkomst till tabellerna via {@code TableList} objekt.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initierar en ny instans av {@code TableAbsorber}. </p> <hr> Utför sökning efter tabeller och ger åtkomst till tabellerna via {@code TableList} objekt.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Returnerar en skrivskyddad IList som innehåller tabeller som hittades </p>

**Returns:**
{@code IGenericList<AbsorbedTable> objekt}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Hämtar alternativ för textsökning. </p> <hr> Tillåter att definiera flera alternativ som kommer att användas under sökning av text i tabeller.

**Returns:**
TextSearchOptions objekt

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Aktivera en alternativ tabelligenkänningsmotor som är överlägsen i många scenarier och kan känna igen tabeller utan kanter.

**Returns:**
booleskt värde

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Tar bort en {@code AbsorbedTable} från sidan. </p> <hr> <p> Vänligen notera att detta ändrar TableList-samlingen. Vid borttagning/ersättning av tabeller i en loop, använd en kopia av TableList-samlingen. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Ersätter en {@code AbsorbedTable} med {@code Table} på sidan. </p> <hr> <p> Vänligen notera att detta ändrar TableList-samlingen. Vid borttagning/ersättning av tabeller i en loop, använd en kopia av TableList-samlingen. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Hämtar eller anger alternativ för textsökning. </p> <hr> Tillåter att definiera flera alternativ som kommer att användas under sökning av text i tabeller.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Aktivera en alternativ tabelligenkänningsmotor som är överlägsen i många scenarier och kan känna igen tabeller utan kanter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| useFlowEngine |  | booleskt värde |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extraherar tabeller i det angivna dokumentet. </p> <hr> <pre> Exemplet visar hur man extraherar en tabell på den första PDF-dokumentets sida. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extraherar tabeller på den angivna sidan </p> <hr> <pre> Exemplet visar hur man extraherar en tabell på den första PDF-dokumentets sida. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
