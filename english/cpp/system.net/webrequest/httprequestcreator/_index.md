---
title: System::Net::WebRequest::HttpRequestCreator class
linktitle: HttpRequestCreator
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebRequest::HttpRequestCreator class. Creates the WebRequest-class instances. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3900
url: /cpp/system.net/webrequest/httprequestcreator/
---
## HttpRequestCreator class


Creates the WebRequest-class instances. Objects of this class should only be allocated using [System::MakeObject()](../../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpRequestCreator : public System::Net::IWebRequestCreate
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Create](./create/)(System::SharedPtr\<Uri\>) | Creates a new instance of the WebRequest-class using the specified URI. |
## See Also

* Class [IWebRequestCreate](../../iwebrequestcreate/)
* Class [WebRequest](../)
* Namespace [System::Net](../../)
* Library [Aspose.PDF for C++](../../../)
