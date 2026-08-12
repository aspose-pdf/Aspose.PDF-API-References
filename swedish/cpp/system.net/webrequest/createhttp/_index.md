---
title: "System::Net::WebRequest::CreateHttp metod"
linktitle: "CreateHttp"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::WebRequest::CreateHttp metod. Skapar en ny instans av WebRequest-klassen med den angivna URI:n i C++."
type: docs
weight: 300
url: /sv/cpp/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) method


Skapar en ny instans av klassen [WebRequest](../) med den angivna URI:n.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| requestUriString | String | URI‑n som används för att skapa en ny instans av klassen [WebRequest](../). |

### ReturnValue

En ny skapad WebRequest-class-instans.
## Anmärkningar



NotSupportedException kommer att kastas när den angivna URI:n börjar med något schema förutom [http://](http://) eller [https://](https://).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) method


Skapar en ny instans av klassen [WebRequest](../) med den angivna URI:n.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| requestUri | System::SharedPtr\<Uri\> | URI‑n som används för att skapa en ny instans av klassen [WebRequest](../). |

### ReturnValue

En ny skapad WebRequest-class-instans.
## Anmärkningar



NotSupportedException kommer att kastas när den angivna URI:n börjar med något schema förutom [http://](http://) eller [https://](https://).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [Uri](../../../system/uri/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
