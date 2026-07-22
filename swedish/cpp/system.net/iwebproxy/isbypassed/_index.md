---
title: "System::Net::IWebProxy::IsBypassed metod"
linktitle: "IsBypassed"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::IWebProxy::IsBypassed metod. Returnerar ett värde som indikerar om proxyn inte får användas för den angivna värden i C++."
type: docs
weight: 300
url: /sv/cpp/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed method


Returnerar ett värde som indikerar om proxy inte får användas för den angivna värden.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | System::SharedPtr\<Uri\> | Värdens URI att kontrollera. |

### ReturnValue

Sant när proxyservern inte får användas, annars falskt.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [IWebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
