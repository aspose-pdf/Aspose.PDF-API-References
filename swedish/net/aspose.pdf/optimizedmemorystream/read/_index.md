---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: OptimizedMemoryStream-metod. När den åsidosätts i en härledd klass läser den en sekvens av byte från den aktuella strömmen och avancerar positionen inom strömmen med antalet lästa byte
type: docs
weight: 100
url: /sv/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read metod

När den åsidosätts i en härledd klass, läser den en sekvens av byte från den aktuella strömmen och avancerar positionen inom strömmen med antalet lästa byte.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | Byte[] | En array av byte. När denna metod returnerar, innehåller bufferten den angivna byte-arrayen med värdena |
| offset | Int32 | Den nollbaserade byte-offset där lagring av data som lästs från den aktuella strömmen ska börja. |
| count | Int32 | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

### Returvärde

Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än antalet begärda byte om så många byte inte för närvarande är tillgängliga, eller noll (0) om slutet av strömmen har nåtts.

### Se Även

* klass [OptimizedMemoryStream](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)