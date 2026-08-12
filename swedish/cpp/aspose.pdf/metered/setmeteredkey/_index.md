---
title: "Aspose::Pdf::Metered::SetMeteredKey‑metoden"
linktitle: "SetMeteredKey"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Metered::SetMeteredKey‑metoden. Ställer in metered offentliga och privata nycklar. Om du köper en metered‑licens, bör detta API anropas när applikationen startas; normalt räcker det. Men om uppladdning av förbrukningsdata alltid misslyckas och överskrider 24 timmar, sätts licensen till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen i C++."
type: docs
weight: 300
url: /sv/cpp/aspose.pdf/metered/setmeteredkey/
---
## Metered::SetMeteredKey method


Ställer in den måttbaserade offentliga och privata nyckeln. Om du köper en måttbaserad licens, bör detta API anropas när applikationen startas; normalt är detta tillräckligt. Men om uppladdning av konsumtionsdata alltid misslyckas och överskrider 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen; om den är i utvärderingsstatus, anropa detta API igen.

```cpp
void Aspose::Pdf::Metered::SetMeteredKey(const System::String &publicKey, const System::String &privateKey)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | const System::String\& | offentlig nyckel |
| privateKey | const System::String\& | privat nyckel |

## Se även

* Class [String](../../../system/string/)
* Class [Metered](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
