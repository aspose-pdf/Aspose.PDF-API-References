---
title: "Метод System::Net::HttpWebRequest::EndGetResponse"
linktitle: "EndGetResponse"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Net::HttpWebRequest::EndGetResponse. Ожидает завершения указанного асинхронного запроса ресурса в C++."
type: docs
weight: 700
url: /ru/cpp/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse method


Ожидает завершения указанного асинхронного запроса к ресурсу.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
