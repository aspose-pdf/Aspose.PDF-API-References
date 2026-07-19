---
title: "System::Net::WebRequest::CreateHttp метод"
linktitle: "CreateHttp"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::WebRequest::CreateHttp метод. Создаёт новый экземпляр класса WebRequest, используя указанный URI в C++."
type: docs
weight: 300
url: /ru/cpp/system.net/webrequest/createhttp/
---
## WebRequest::CreateHttp(String) method


Создаёт новый экземпляр класса [WebRequest](../), используя указанный URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(String requestUriString)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| requestUriString | String | URI, который используется для создания нового экземпляра класса [WebRequest](../). |

### ReturnValue

Новый экземпляр класса WebRequest.
## Примечания



NotSupportedException будет выброшено, когда указанный URI начинается с любой схемы, кроме [http://](http://) или [https://](https://).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [String](../../../system/string/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
## WebRequest::CreateHttp(System::SharedPtr\<Uri\>) method


Создаёт новый экземпляр класса [WebRequest](../), используя указанный URI.

```cpp
static System::SharedPtr<HttpWebRequest> System::Net::WebRequest::CreateHttp(System::SharedPtr<Uri> requestUri)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| requestUri | System::SharedPtr\<Uri\> | URI, который используется для создания нового экземпляра класса [WebRequest](../). |

### ReturnValue

Новый экземпляр класса WebRequest.
## Примечания



NotSupportedException будет выброшено, когда указанный URI начинается с любой схемы, кроме [http://](http://) или [https://](https://).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpWebRequest](../../httpwebrequest/)
* Class [Uri](../../../system/uri/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
