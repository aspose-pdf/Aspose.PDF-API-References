---
title: "System::Net::Cookie::VerifySetDefaults method"
linktitle: "VerifySetDefaults"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::Cookie::VerifySetDefaults method. Verifierar och sätter standardattributets värden i C++."
type: docs
weight: 4200
url: /sv/cpp/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults method


Verifierar och sätter standardattributens värden.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| variant | CookieVariant | Cookie''s specifikation. |
| uri | System::SharedPtr\<Uri\> | Uri-klassens instans som används för att initiera de interna fälten. |
| isLocalDomain | bool | Ett värde som indikerar om cookien skjuts in i den lokala domänen. |
| localDomain | String | Ett lokalt domännamn. |
| setDefault | bool | Ett värde som indikerar om cookiens attribut måste initieras med sina standardvärden. |
| shouldThrow | bool | Ett värde som indikerar om ett undantag ska kastas när de angivna värdena är ogiltiga. |

### ReturnValue

Sant när alla värden är giltiga, annars falskt.

## Se även

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [Cookie](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
