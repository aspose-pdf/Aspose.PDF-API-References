---
title: "Page.IsBlank"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Page-metod. Hämtar flaggan som anger om sidan är tom eller inte"
type: docs
weight: 490
url: /sv/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

Hämtar flaggan som anger om sidan är tom eller inte.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillThresholdFactor | Double | Fylltröskelvärdet som styr känsligheten för detektering. Bör ligga i intervallet [0..1). |

### Returvärde

Sant - om sidan är tom; annars falskt.

## Anmärkningar

För att avgöra om en sida är tom eller inte beräknas förhållandet mellan det fyllda utrymmet och sidans totala utrymme. Detta förhållande jämförs med parametern fillThresholdFactor och om det är mindre anses sidan vara tom.

### Se även

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


