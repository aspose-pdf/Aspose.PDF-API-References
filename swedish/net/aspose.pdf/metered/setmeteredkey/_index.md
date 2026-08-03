---
title: "Metered.SetMeteredKey"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Metered-metoden. Ställer in metered offentlig och privat nyckel. Om du köper en metered-licens när du startar applikationen bör detta API anropas normalt, det räcker. Men om uppladdning av konsumtionsdata alltid misslyckas och överstiger 24 timmar kommer licensen att sättas till utvärderingsstatus; för att undvika detta bör du regelbundet kontrollera licensstatusen och om den är i utvärderingsstatus anropa detta API igen."
type: docs
weight: 30
url: /sv/net/aspose.pdf/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Ställer in metered offentlig och privat nyckel. Om du köper en metered-licens, bör detta API anropas när applikationen startas; normalt är detta tillräckligt. Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | String | offentlig nyckel |
| privateKey | String | privat nyckel |

### Se även

* class [Metered](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


