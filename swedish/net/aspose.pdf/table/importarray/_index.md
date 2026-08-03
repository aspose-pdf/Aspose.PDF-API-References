---
title: "Table.ImportArray"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Tabell‑metod. Importerar endimensionell array av data till tabellen. Importen går en cell per varje array‑element och startar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäcks att nödvändiga rader fortfarande saknas, t.ex. att måltabellen är för liten för att rymma all data, kommer nödvändiga rader att skapas"
type: docs
weight: 250
url: /sv/net/aspose.pdf/table/importarray/
---
## Table.ImportArray method

Importerar endimensionell array av data till tabellen. Importen går en cell per varje array‑element och startar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäcks att nödvändiga rader fortfarande saknas (dvs. mål‑tabellen är för liten för att rymma all data), kommer nödvändiga rader att skapas

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| importedArray | Object[] | Importerade data, nullvärden importeras som tomma strängar |
| firstFilledRow | Int32 | definiera antalet första målrad i måltabellen där importen ska börja. Om antalet rader i måltabellen är färre än krävs, kommer saknade rader att skapas först. |
| firstFilledColumn | Int32 | anger nummer för den första målkolumnen i måltabellen, kolumnen måste finnas i måltabellen innan importen startar |
| isLeftColumnsFilled | Boolean | Om 'isLeftColumnsFilled'=false, så kommer celler till vänster om firstFilledColumn i den andra och alla efterföljande fyllda rader att hoppas över. |

### Se även

* class [Table](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


