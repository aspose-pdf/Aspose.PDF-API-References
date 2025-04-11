---
title: Table.ImportArray
second_title: Aspose.PDF for .NET API Reference
description: Tabellmetod. Importerar en-dimensionell array av data till tabellen. Importen går en cell per varje arrays objekt och börjar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäckts att nödvändiga rader fortfarande är frånvarande, dvs. måltabellen är för liten för att absorbera all data, kommer nödvändiga rader att skapas
type: docs
weight: 250
url: /sv/net/aspose.pdf/table/importarray/
---
## Table.ImportArray metod

Importerar en-dimensionell array av data till tabellen. Importen går en cell per varje objekts i arrayen och börjar från rad och kolumn som definieras i parametrarna. Under importen, om det upptäckts att nödvändiga rader fortfarande är frånvarande (dvs. måltabellen är för liten för att absorbera all data), kommer nödvändiga rader att skapas

```csharp
public void ImportArray(object[] importedArray, int firstFilledRow, int firstFilledColumn, 
    bool isLeftColumnsFilled)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| importedArray | Object[] | importerad data, null-värden kommer att importeras som tomma strängar |
| firstFilledRow | Int32 | definiera nummer på första målraden i måltabellen från vilken importen kommer att börja. Om antalet rader i måltabellen är mindre än vad som krävs, kommer de saknade raderna att skapas först. |
| firstFilledColumn | Int32 | specificerar nummer på första målkolumnen i måltabellen, kolumnen måste finnas i måltabellen innan importen påbörjas |
| isLeftColumnsFilled | Boolean | Om 'isLeftColumnsFilled'=false, då i andra och alla efterföljande fyllda rader kommer celler som ligger till vänster om firstFilledColumn att hoppas över |

### Se Även

* klass [Table](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../../)