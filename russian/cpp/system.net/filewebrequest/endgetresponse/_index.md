---
title: "System::Net::FileWebRequest::EndGetResponse метод"
linktitle: "EndGetResponse"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Net::FileWebRequest::EndGetResponse метод. Ожидает завершения указанного асинхронного запроса ресурса в C++."
type: docs
weight: 600
url: /ru/cpp/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse method


Ожидает завершения указанного асинхронного запроса к ресурсу.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
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
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
