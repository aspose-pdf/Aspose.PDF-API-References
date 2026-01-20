---
title: System::Net::Http::Headers::HttpHeaders class
linktitle: HttpHeaders
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::HttpHeaders class. The collection of the HTTP headers. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 700
url: /cpp/system.net.http.headers/httpheaders/
---
## HttpHeaders class


The collection of the HTTP headers. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpHeaders : public System::Collections::Generic::IEnumerable<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<System::Collections::Generic::IEnumerable<System::String>>>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Validates a new name-values pair and adds it to the current collection. |
| [Add](./add/)(String, String) | Validates a new name-value pair and adds it to the current collection. |
| virtual [AddHeaders](./addheaders/)(System::SharedPtr\<HttpHeaders\>) | Concatenates the specified HttpHeaders-class instance with the current one. |
| [AddParsedValue](./addparsedvalue/)(String, System::SharedPtr\<Object\>) | Gets a header by the specified name and adds a parsed value to the header. |
| [Clear](./clear/)() | Removes all items from the collection. |
| [Contains](./contains/)(String) |  |
| [ContainsParsedValue](./containsparsedvalue/)(String, System::SharedPtr\<Object\>) | Checks if the header contains the specified value. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator. |
| [GetHeaderString](./getheaderstring/)(String) | Returns a string representation of values by the specified header name. |
| [GetHeaderString](./getheaderstring/)(String, System::SharedPtr\<Object\>) | Returns a string representation of values by the specified header name. |
| [GetHeaderStrings](./getheaderstrings/)() | Returns a collection that contains string representations of headers' values. |
| [GetParsedValues](./getparsedvalues/)(String) | Returns parsed values by the specified header name. |
| [GetValues](./getvalues/)(String) | Returns corresponding values by the specified name. |
| static [ParsedValuesAsList](./parsedvaluesaslist/)(const System::SharedPtr\<Object\>) | Converts parsed values to list. |
| [Remove](./remove/)(String) | Tries to remove an item by the specified name. |
| [RemoveParsedValue](./removeparsedvalue/)(String, System::SharedPtr\<Object\>) | Gets a header by the specified name and removes a parsed value from the header. |
| [SetConfiguration](./setconfiguration/)(System::SharedPtr\<Collections::Generic::Dictionary\<String, System::SharedPtr\<HttpHeaderParser\>\>\>, System::SharedPtr\<Collections::Generic::HashSet\<String\>\>) |  |
| [SetOrRemoveParsedValue](./setorremoveparsedvalue/)(String, System::SharedPtr\<Object\>) | Gets a header by the specified name and sets or removes its value. The header value will be removed when the 'value' parameter is nullptr, otherwise a parsed value will be set. |
| [SetParsedValue](./setparsedvalue/)(String, System::SharedPtr\<Object\>) | Gets a header by the specified name and sets a parsed value to the header. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, String) | Tries to add a new name-value pair to the current collection. |
| [TryAddWithoutValidation](./tryaddwithoutvalidation/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>) | Adds a collection of name-value pairs to the current collection. |
| [TryGetValues](./trygetvalues/)(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) | Tries to get corresponding values by the specified name. |
| [TryParseAndAddValue](./tryparseandaddvalue/)(String, String) | Tries to parse the specified value and add it to the header values. |
## See Also

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
