---
title: System::Net::WebClient class
linktitle: WebClient
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::WebClient class. WebClient provides common methods for sending and receiving data. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 3500
url: /cpp/system.net/webclient/
---
## WebClient class


[WebClient](./) provides common methods for sending and receiving data. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class WebClient : public System::ComponentModel::Component
```

## Methods

| Method | Description |
| --- | --- |
| [DownloadData](./downloaddata/)(const String\&) const | Downloads the specified resource as a byte array. |
| [DownloadData](./downloaddata/)(const SharedPtr\<Uri\>\&) const | Downloads the specified resource as a byte array. |
| [DownloadString](./downloadstring/)(const String\&) const | Downloads the specified resource as a string. |
| [DownloadString](./downloadstring/)(const SharedPtr\<Uri\>\&) const | Downloads the specified resource as a string. |
| [get_Encoding](./get_encoding/)() const | Gets the encoding used to download or upload strings. |
| [set_Encoding](./set_encoding/)(const SharedPtr\<Text::Encoding\>\&) | Sets the encoding used to download or upload strings. |
| [set_UseDefaultCredentials](./set_usedefaultcredentials/)(bool) | NOT IMPLEMENTED. |
| [WebClient](./webclient/)() | RTTI information. |
| [~WebClient](./~webclient/)() | Destructs the current instance. |
## See Also

* Class [Component](../../system.componentmodel/component/)
* Namespace [System::Net](../)
* Library [Aspose.PDF for C++](../../)
