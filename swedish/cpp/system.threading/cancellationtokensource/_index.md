---
title: "System::Threading::CancellationTokenSource-klass"
linktitle: "CancellationTokenSource"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::CancellationTokenSource-klass. En avboknings-tokenkälla som kan användas för att utlösa avbokningsnotiser i C++."
type: docs
weight: 400
url: /sv/cpp/system.threading/cancellationtokensource/
---
## CancellationTokenSource class


En avbokningstokenkälla som kan användas för att utlösa avbokningsnotifikationer.

```cpp
class CancellationTokenSource : public System::IDisposable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Cancel](./cancel/)() | Kommunicerar en begäran om avbrytning. |
| [CancellationTokenSource](./cancellationtokensource/)() | Skapar en ny [CancellationTokenSource](./). |
| static [CreateLinkedTokenSource](./createlinkedtokensource/)(const CancellationToken\&, const CancellationToken\&) | Skapar en länkad tokenkälla som avbryts när någon av de angivna tokenarna avbryts. |
| [Dispose](./dispose/)() override | Frigör alla resurser som används av [CancellationTokenSource](./). |
| [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Hämtar om avbrytning har begärts. |
| [get_Token](./get_token/)() const | Hämtar avbrytningstoken som är associerad med denna källa. |
## Anmärkningar


Tillhandahåller mekanismer för att skapa och styra avbrytningstoken för samarbetsbaserad avbrytning av operationer.
## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
