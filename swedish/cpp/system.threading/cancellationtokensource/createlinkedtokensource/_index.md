---
title: "System::Threading::CancellationTokenSource::CreateLinkedTokenSource-metod"
linktitle: "CreateLinkedTokenSource"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::CancellationTokenSource::CreateLinkedTokenSource-metod. Skapar en länkad tokenkälla som avbryts när någon av de angivna tokenarna avbryts i C++."
type: docs
weight: 600
url: /sv/cpp/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource method


Skapar en länkad tokenkälla som avbryts när någon av de angivna tokenarna avbryts.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| token1 | const CancellationToken\& | Första avbokningstoken att övervaka. |
| token2 | const CancellationToken\& | Andra avbokningstoken att övervaka. |

### ReturnValue

Ny tokenkälla som avbryts när någon av ingångstokenarna avbryts.
## Anmärkningar



Den returnerade källan avbryts omedelbart om någon av ingångstokenarna redan är avbruten.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [CancellationTokenSource](../)
* Class [CancellationToken](../../cancellationtoken/)
* Class [CancellationTokenSource](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
