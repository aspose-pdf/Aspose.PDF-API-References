---
title: ImportArray
second_title: Aspose.PDF für .NET-API-Referenz
description: Importiert eindimensionales Array von Daten in die Tabelle. Der Import geht eine Zelle pro Element jedes Arrays und beginnt mit Zeile und Spalte die in Parametern definiert sind. Wenn während des Imports festgestellt wird dass erforderliche Zeilen noch fehlen dh die Zieltabelle ist zu klein um alle Daten aufzunehmen werden erforderliche Zeilen erstellt
type: docs
weight: 250
url: /de/net/aspose.pdf/table/importarray/
---
## Table.ImportArray method

Importiert eindimensionales Array von Daten in die Tabelle. Der Import geht eine Zelle pro Element jedes Arrays und beginnt mit Zeile und Spalte, die in Parametern definiert sind. Wenn während des Imports festgestellt wird, dass erforderliche Zeilen noch fehlen (dh die Zieltabelle ist zu klein, um alle Daten aufzunehmen), werden erforderliche Zeilen erstellt

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| importedArray | Object[] | importierten Daten werden Nullen als leere Zeichenfolgen importiert |
| firstFilledRow | Int32 | Definieren Sie die Nummer der ersten Zielzeile in der Zieltabelle, ab der der Import beginnen soll. Wenn die Anzahl der Zeilen in der Zieltabelle geringer als erforderlich ist, werden zuerst die fehlenden Zeilen erstellt. |
| firstFilledColumn | Int32 | gibt die Nummer der ersten Zielspalte in der Zieltabelle an, die Spalte muss vor dem Start des Imports in der Zieltabelle vorhanden sein |
| isLeftColumnsFilled | Boolean | Wenn 'isLeftColumnsFilled'=false, dann werden in der zweiten und allen folgenden gefüllten Zeilen Zellen, die sich auf der linken Seite von firstFilledColumn befinden, übersprungen |

### Siehe auch

* class [Table](../../table)
* namensraum [Aspose.Pdf](../../table)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
