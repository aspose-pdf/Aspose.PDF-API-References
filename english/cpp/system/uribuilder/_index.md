---
title: System::UriBuilder class
linktitle: UriBuilder
second_title: Aspose.PDF for C++ API Reference
description: 'System::UriBuilder class. Provides methods to construct and modify universial resource identifiers (URIs). Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 6800
url: /cpp/system/uribuilder/
---
## UriBuilder class


Provides methods to construct and modify universial resource identifiers (URIs). Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UriBuilder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_Scheme](./get_scheme/)() const | Returns the scheme of the URI constructed by the current object. |
| [get_Uri](./get_uri/)() const | Returns the [Uri](../uri/) object constructed by the current object. |
| [set_Port](./set_port/)(int) | Sets the sets the port number of the URI. |
| [set_Scheme](./set_scheme/)(const String\&) | Sets the scheme of the URI constructed by the current object to the specified value. |
| [ToString](./tostring/)() const override | Returns the string representation of the URI constructed by the current object. |
| [UriBuilder](./uribuilder/)(const String\&) | Constructs a [UriBuilder](./) object that represents that represents the specified URI. |
| [UriBuilder](./uribuilder/)(const SharedPtr\<Uri\>\&) | Constructs a [UriBuilder](./) object that represents that represents the specified URI. |
## See Also

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
