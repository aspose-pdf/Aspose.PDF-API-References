---
title: "OptimizedMemoryStream.Read"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OptimizedMemoryStream-metod. När den åsidosätts i en avledd klass läser den en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte"
type: docs
weight: 100
url: /sv/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

När den åsidosätts i en avledd klass, läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffert | Byte[] | En array av byte. När denna metod återvänder innehåller bufferten den angivna bytearrayen med värdena |
| offset | Int32 | Det nollbaserade byteoffsetet i där lagringen av data som lästs från den aktuella strömmen ska börja. |
| antal | Int32 | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

### Returvärde

Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än det begärda antalet byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet på strömmen har nåtts.

### Se även

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


