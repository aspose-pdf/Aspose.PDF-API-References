---
title: "System::Net::WebRequest::EndGetResponse метод"
linktitle: "EndGetResponse"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::WebRequest::EndGetResponse метод. Ожидает завершения указанного асинхронного запроса к ресурсу в C++."
type: docs
weight: 1300
url: /ru/cpp/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse method


Ожидает завершения указанного асинхронного запроса к ресурсу.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| asyncResult | System::SharedPtr\<IAsyncResult\> | Объект [IAsyncResult](../../../system/iasyncresult/) , представляющий асинхронный запрос ресурса. |

### ReturnValue

Веб‑ответ.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WebResponse](../../webresponse/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
