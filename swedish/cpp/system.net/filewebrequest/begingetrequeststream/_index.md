---
title: "System::Net::FileWebRequest::BeginGetRequestStream metod"
linktitle: "BeginGetRequestStream"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Net::FileWebRequest::BeginGetRequestStream metod. Initierar en asynkron operation för att hämta en ström för att skriva data till resursen i C++."
type: docs
weight: 300
url: /sv/cpp/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream method


Initierar en asynkron operation för att hämta en ström för att skriva data till resursen.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | AsyncCallback | En callback som ska anropas när operationen är klar. |
| state | System::SharedPtr\<Object\> | Användar‑tillhandahållen data som används för att unikt identifiera varje asynkron operation. |

### ReturnValue

Ett [IAsyncResult](../../../system/iasyncresult/)‑objekt som representerar den initierade asynkrona operationen.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [Object](../../../system/object/)
* Class [FileWebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
