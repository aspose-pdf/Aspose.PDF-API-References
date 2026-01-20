---
title: System::Net::Http::Headers::HttpHeaderValueCollection class
linktitle: HttpHeaderValueCollection
second_title: Aspose.PDF for C++ API Reference
description: 'System::Net::Http::Headers::HttpHeaderValueCollection class. Represents the collection of the headers values. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument in C++.'
type: docs
weight: 800
url: /cpp/system.net.http.headers/httpheadervaluecollection/
---
## HttpHeaderValueCollection class


Represents the collection of the headers values. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T>class HttpHeaderValueCollection : public System::Collections::Generic::ICollection<T>
```


| Parameter | Description |
| --- | --- |
| The | type of the headers values represented in the collection. |
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const T\&) override | Adds element into collection. |
| [Clear](./clear/)() override | Deletes all elements from collection. |
| [Contains](./contains/)(const T\&) const override | Checks if element is present in collection. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int32_t) override | Copies all collection elements to existing array elements. |
| [get_Count](./get_count/)() const override | RTTI information. |
| [get_IsReadOnly](./get_isreadonly/)() | Gets a value that indicates if the current collection is read-only. |
| [get_IsSpecialValueSet](./get_isspecialvalueset/)() | Gets a value that indicates if the current collection contains a "special value". |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator. |
| [GetHeaderStringWithoutSpecial](./getheaderstringwithoutspecial/)() | Returns a string representation of the current collection without a "special value". |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>) | Constructs a new instance. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Constructs a new instance. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T) | Constructs a new instance. |
| [HttpHeaderValueCollection](./httpheadervaluecollection/)(String, System::SharedPtr\<HttpHeaders\>, T, Action\<System::SharedPtr\<HttpHeaderValueCollection\<T\>\>, T\>) | Constructs a new instance. |
| [ParseAdd](./parseadd/)(String) | Parses a header string representation and adds it to the current collection. |
| [Remove](./remove/)(const T\&) override | Deletes element from collection. |
| [RemoveSpecialValue](./removespecialvalue/)() | Removes a "special value". |
| [SetSpecialValue](./setspecialvalue/)() | Sets a "special value". |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| [ToString](./tostring/)() const override | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [TryParseAdd](./tryparseadd/)(String) | Tries to parse a header string representation and add it to the current collection. |

## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.PDF for C++](../../)
