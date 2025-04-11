---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Tabellenmethode. Importiert eindimensionales Array von Daten in die Tabelle. Der Import erfolgt zelle für zelle für jedes Element des Arrays und beginnt in der Zeile und Spalte, die in den Parametern definiert sind. Während des Imports, wenn festgestellt wird, dass notwendige Zeilen noch fehlen (d.h. die Zieltabelle zu klein ist, um alle Daten aufzunehmen), werden die notwendigen Zeilen erstellt
type: docs
weight: 250
url: /de/net/aspose.pdf/table/importarray/
---
## Table.ImportArray-Methode

Importiert ein eindimensionales Array von Daten in die Tabelle. Der Import erfolgt zelle für zelle für jedes Element des Arrays und beginnt in der Zeile und Spalte, die in den Parametern definiert sind. Während des Imports, wenn festgestellt wird, dass notwendige Zeilen noch fehlen (d.h. die Zieltabelle zu klein ist, um alle Daten aufzunehmen), werden die notwendigen Zeilen erstellt

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| importedArray | Object[] | importierte Daten, Nullwerte werden als leere Strings importiert |
| firstFilledRow | Int32 | definiert die Nummer der ersten Zielzeile in der Zieltabelle, von der der Import beginnen wird. Wenn die Anzahl der Zeilen in der Zieltabelle geringer ist als erforderlich, werden zuerst die fehlenden Zeilen erstellt. |
| firstFilledColumn | Int32 | gibt die Nummer der ersten Zielspalte in der Zieltabelle an, die Spalte muss vor Beginn des Imports in der Zieltabelle vorhanden sein |
| isLeftColumnsFilled | Boolean | Wenn 'isLeftColumnsFilled'=false, dann werden in der zweiten und allen nachfolgenden gefüllten Zeilen die Zellen, die sich links von firstFilledColumn befinden, übersprungen |

### Siehe auch

* Klasse [Table](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)