---
title: "System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength metod"
linktitle: "GetTransferCodingLength"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength method. Konverterar en given sträng från det angivna indexet till en instans av klassen TransferCodingHeaderValue i C++."
type: docs
weight: 700
url: /sv/cpp/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength method


Konverterar en given sträng från det angivna indexet till en instans av klassen [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inmatning | String | En sträng att tolka. |
| startIndex | int32_t | En startposition för parsning. |
| parsedValue | const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\& | En instans där ett parsat objekt kommer att tilldelas. |
| transferCodingCreator | System::SharedPtr\<TransferCodingHeaderValue\>\& | Delegaten som används för att skapa instanser av klassen [TransferCodingHeaderValue](../). |

### ReturnValue

Returnerar längden på en analyserad delsträng, annars 0.

## Se även

* Class [String](../../../system/string/)
* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TransferCodingHeaderValue](../)
* Class [TransferCodingHeaderValue](../)
* Namespace [System::Net::Http::Headers](../../)
* Library [Aspose.PDF for C++](../../../)
