---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt ein Absorber-Objekt für Tabellenelemente dar. Führt eine Suche durch und bietet Zugriff auf Suchergebnisse über die {@code TableAbsorber.TableList}-Sammlung. </p> <hr> <pre> Der."
type: docs
weight: 4800
url: /de/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Stellt ein Absorber-Objekt für Tabellenelemente dar. Führt eine Suche durch und bietet Zugriff auf Suchergebnisse über die {@code TableAbsorber.TableList}-Sammlung. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Tabelle auf der ersten Seite des PDF-Dokuments findet und den Text in einer Tabellenzelle ersetzt. // Dokument öffnen Document doc = new Document("D:\\Tests\\input.pdf"); // TableAbsorber-Objekt erstellen, um Tabellen zu finden TableAbsorber absorber = new TableAbsorber(); // Erste Seite mit Absorber besuchen absorber.visit(doc.getPages().get_Item(1)); // Zugriff auf die erste Tabelle auf der Seite, deren erste Zelle und Textfragmente erhalten TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Text des ersten Textfragments in der Zelle ändern fragment.setText("hi world"); // Dokument speichern doc.save("D:\\Tests\\output.pdf"); </pre>

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Initialisiert eine neue Instanz von {@code TableAbsorber}. </p> <hr> Führt die Suche nach Tabellen durch und bietet Zugriff auf die Tabellen über das {@code TableList}-Objekt. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Initialisiert eine neue Instanz von {@code TableAbsorber}. </p> <hr> Führt die Suche nach Tabellen durch und bietet Zugriff auf die Tabellen über das {@code TableList}-Objekt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTableList](#getTableList--) | <p> Gibt eine schreibgeschützte IList zurück, die gefundene Tabellen enthält </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Ruft Textsuchoptionen ab. </p> <hr> Ermöglicht das Definieren mehrerer Optionen, die bei der Suche nach Text in Tabellen verwendet werden. |
| [isUseFlowEngine](#isUseFlowEngine--) | Aktivieren Sie eine alternative Tabellenerkennungs-Engine, die in zahlreichen Szenarien überlegen ist und Tabellen ohne Rahmen erkennen kann. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Entfernt ein {@code AbsorbedTable} von der Seite. </p> <hr> <p> Bitte beachten Sie, dass dies die TableList‑Sammlung ändert. Beim Entfernen/Ersetzen von Tabellen in einer Schleife verwenden Sie bitte eine Kopie der TableList‑Sammlung. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Ersetzt ein {@code AbsorbedTable} durch {@code Table} auf der Seite. </p> <hr> <p> Bitte beachten Sie, dass dies die TableList‑Sammlung ändert. Beim Entfernen/Ersetzen von Tabellen in einer Schleife verwenden Sie bitte eine Kopie der TableList‑Sammlung. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Ruft Textsuchoptionen ab oder legt sie fest. </p> <hr> Ermöglicht das Definieren mehrerer Optionen, die bei der Suche nach Text in Tabellen verwendet werden. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Aktivieren Sie eine alternative Tabellenerkennungs-Engine, die in zahlreichen Szenarien überlegen ist und Tabellen ohne Rahmen erkennen kann. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Extrahiert Tabellen im angegebenen Dokument. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Tabelle auf der ersten Seite des PDF-Dokuments extrahiert. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Extrahiert Tabellen auf der angegebenen Seite </p> <hr> <pre> Das Beispiel zeigt, wie man eine Tabelle auf der ersten Seite des PDF-Dokuments extrahiert. // Open document Document doc = new Document(@"D:\\Tests\\input.pdf"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText ("hi world"); // Save document doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Initialisiert eine neue Instanz von {@code TableAbsorber}. </p> <hr> Führt die Suche nach Tabellen durch und bietet Zugriff auf die Tabellen über das {@code TableList}-Objekt.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Initialisiert eine neue Instanz von {@code TableAbsorber}. </p> <hr> Führt die Suche nach Tabellen durch und bietet Zugriff auf die Tabellen über das {@code TableList}-Objekt.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Gibt eine schreibgeschützte IList zurück, die gefundene Tabellen enthält </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Ruft Textsuchoptionen ab. </p> <hr> Ermöglicht das Definieren mehrerer Optionen, die bei der Suche nach Text in Tabellen verwendet werden.

**Returns:**
TextSearchOptions-Objekt

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Aktivieren Sie eine alternative Tabellenerkennungs-Engine, die in zahlreichen Szenarien überlegen ist und Tabellen ohne Rahmen erkennen kann.

**Returns:**
boolescher Wert

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Entfernt ein {@code AbsorbedTable} von der Seite. </p> <hr> <p> Bitte beachten Sie, dass dies die TableList‑Sammlung ändert. Beim Entfernen/Ersetzen von Tabellen in einer Schleife verwenden Sie bitte eine Kopie der TableList‑Sammlung. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Ersetzt ein {@code AbsorbedTable} durch {@code Table} auf der Seite. </p> <hr> <p> Bitte beachten Sie, dass dies die TableList‑Sammlung ändert. Beim Entfernen/Ersetzen von Tabellen in einer Schleife verwenden Sie bitte eine Kopie der TableList‑Sammlung. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Ruft Textsuchoptionen ab oder legt sie fest. </p> <hr> Ermöglicht das Definieren mehrerer Optionen, die bei der Suche nach Text in Tabellen verwendet werden.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Aktivieren Sie eine alternative Tabellenerkennungs-Engine, die in zahlreichen Szenarien überlegen ist und Tabellen ohne Rahmen erkennen kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| useFlowEngine |  | boolescher Wert |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Extrahiert Tabellen im angegebenen Dokument. </p> <hr> <pre> Das Beispiel zeigt, wie man eine Tabelle auf der ersten PDF-Dokumentseite extrahiert. // Dokument öffnen Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // TableAbsorber-Objekt erstellen, um Tabellen zu finden TableAbsorber absorber = new TableAbsorber(); // Erste Seite mit Absorber besuchen absorber.visit(pdfDocument); // Zugriff auf die erste Tabelle auf der Seite, deren erste Zelle und Textfragmente erhalten TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Text des ersten Textfragments in der Zelle ändern fragment.setText (\"hi world\"); // Dokument speichern doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Extrahiert Tabellen auf der angegebenen Seite </p> <hr> <pre> Das Beispiel zeigt, wie man eine Tabelle auf der ersten PDF-Dokumentseite extrahiert. // Dokument öffnen Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // TableAbsorber-Objekt erstellen, um Tabellen zu finden TableAbsorber absorber = new TableAbsorber(); // Erste Seite mit Absorber besuchen absorber.visit(doc.getPages.get_item(1)); // Zugriff auf die erste Tabelle auf der Seite, deren erste Zelle und Textfragmente erhalten TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Text des ersten Textfragments in der Zelle ändern fragment.setText (\"hi world\"); // Dokument speichern doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
