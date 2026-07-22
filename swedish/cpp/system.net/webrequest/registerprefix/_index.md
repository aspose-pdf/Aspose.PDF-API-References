---
title: "System::Net::WebRequest::RegisterPrefix metod"
linktitle: "RegisterPrefix"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebRequest::RegisterPrefix metod. Registrerar WebRequest-efterföljaren för den angivna URI:n i C++."
type: docs
weight: 600
url: /sv/cpp/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix method


Registrerar [WebRequest](../)-efterföljaren för den angivna URI:n.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| prefix | String | URI:n eller URI-prefixet. |
| creator | System::SharedPtr\<IWebRequestCreate\> | Skapar nya instanser av klassen [WebRequest](../). |

### ReturnValue

Sant när [WebRequest](../)-efterföljaren har registrerats framgångsrikt för den angivna URI:n, annars falskt.

## Se även

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
