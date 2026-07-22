---
title: "Aspose::Pdf::Metered class"
linktitle: "Måttbaserad"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Metered-klass. Tillhandahåller metoder för att ställa in måttbaserad nyckel i C++."
type: docs
weight: 11300
url: /sv/cpp/aspose.pdf/metered/
---
## Metered class


Tillhandahåller metoder för att ställa in mätt nyckel.

```cpp
class Metered : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [GetConsumptionCredit](./getconsumptioncredit/)() | Hämtar konsumtionskredit. |
| static [GetConsumptionQuantity](./getconsumptionquantity/)() | Hämtar konsumtionsfilens storlek. |
| [GetProductName](./getproductname/)() | Hämta produktnamnet. |
| static [IsMeteredLicensed](./ismeteredlicensed/)() | Kontrollera om måttbaserad är licensierad. |
| [Metered](./metered/)() | Initierar en ny instans av denna klass. |
| [SetMeteredKey](./setmeteredkey/)(const System::String\&, const System::String\&) | Ställer in den måttbaserade offentliga och privata nyckeln. Om du köper en måttbaserad licens, bör detta API anropas när applikationen startas; normalt är detta tillräckligt. Men om uppladdning av konsumtionsdata alltid misslyckas och överskrider 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen; om den är i utvärderingsstatus, anropa detta API igen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
