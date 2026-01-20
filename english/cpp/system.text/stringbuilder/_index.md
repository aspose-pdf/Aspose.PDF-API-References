---
title: System::Text::StringBuilder class
linktitle: StringBuilder
second_title: Aspose.PDF for C++ API Reference
description: 'System::Text::StringBuilder class. Buffer to accumulate string part by part. This type can be allocated either in stack as value type or in heap using System::MakeObject() function. Once the object is allocated, never mix up these two usecases: having SmartPtr pointers onto stack-allocated objects is strictly prohibited in C++.'
type: docs
weight: 2400
url: /cpp/system.text/stringbuilder/
---
## StringBuilder class


[Buffer](../../system/buffer/) to accumulate string part by part. This type can be allocated either in stack as value type or in heap using [System::MakeObject()](../../system/makeobject/) function. Once the object is allocated, never mix up these two usecases: having [SmartPtr](../../system/smartptr/) pointers onto stack-allocated objects is strictly prohibited.

```cpp
class StringBuilder : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [Append](./append/)(char_t) | Adds character to builder. |
| [Append](./append/)(char_t, int) | Adds characters to builder. |
| [Append](./append/)(const ArrayPtr\<char_t\>\&) | Adds characters array to builder. |
| [Append](./append/)(const ArrayPtr\<char_t\>\&, int, int) | Adds characters array slice to builder. |
| [Append](./append/)(const String\&) | Adds string to builder. |
| [Append](./append/)(const String\&, int, int) | Adds string slice to builder. |
| [Append](./append/)(const SharedPtr\<T\>\&) | Adds object's string representation to builder. |
| [Append](./append/)(const SharedPtr\<StringBuilder\>\&) | Adds builder's content to builder. |
| [Append](./append/)(float) | Adds floating point value to builder. |
| [Append](./append/)(double) | Adds floating point value to builder. |
| [Append](./append/)(int) | Adds integer value to builder. |
| [Append](./append/)(T) | Adds arithmetic value to builder. |
| [Append](./append/)(E) | Adds enum value string representation to builder. |
| [AppendFormat](./appendformat/)(const String\&, const TArgs\&...) | Appends formated string to builder. |
| [AppendFormat](./appendformat/)(const SharedPtr\<IFormatProvider\>\&, const String\&, const TArgs\&...) | Appends formated string to builder. |
| [AppendLine](./appendline/)() | Appends new line character to builder. |
| [AppendLine](./appendline/)(const String\&) | Appends string followed by new line character to builder. |
| [Clear](./clear/)() | Removes all characters from the builder. |
| [CopyTo](./copyto/)(int, System::ArrayPtr\<char_t\> const\&, int, int) | Copies builder's data into existing array positions. |
| [get_Capacity](./get_capacity/)() const | Gets current capacity of string builder. |
| [get_Length](./get_length/)() const | Gets length of string currently in builder. |
| [idx_get](./idx_get/)(int) const | Gets character at specified position. |
| [idx_set](./idx_set/)(int, char_t) | Sets character at specified position. |
| [Insert](./insert/)(int, const String\&) | Inserts string into builder's fixed position. |
| [Insert](./insert/)(int32_t, const String\&, int32_t) | Inserts repeated string into builder's fixed position. |
| [Insert](./insert/)(int, char_t) | Inserts character into builder's fixed position. |
| [Insert](./insert/)(int, const System::ArrayPtr\<char_t\>\&, int, int) | Inserts characters into builder's fixed position. |
| [Insert](./insert/)(int, T) | Inserts value into builder's fixed position. |
| [operator[]](./operator[]/)(int) const | Gets character at specified position. |
| [Remove](./remove/)(int, int) | Removes fragment from builder. |
| [Replace](./replace/)(const String\&, const String\&) | Replaces substring through the builder. |
| [Replace](./replace/)(const String\&, const String\&, int, int) | Replaces substring through the builder's range. |
| [Replace](./replace/)(char_t, char_t) | Replaces character through the builder. |
| [Replace](./replace/)(char_t, char_t, int, int) | Replaces character through the builder's range. |
| [set_Capacity](./set_capacity/)(int) | Sets current capacity of string builder. |
| [set_Length](./set_length/)(int) | Trunkates or extends string builder to specified length. |
| [StringBuilder](./stringbuilder/)() | Constructor. |
| [StringBuilder](./stringbuilder/)(int) | Constructor. |
| [StringBuilder](./stringbuilder/)(const String\&) | Constructor. |
| [StringBuilder](./stringbuilder/)(const String\&, int) | Constructor. |
| [StringBuilder](./stringbuilder/)(const String\&, int, int, int) | Constructor. |
| [ToString](./tostring/)() const override | Gets string currently contained in builder. |
| [ToString](./tostring/)(int, int) const | Gets substring currently contained in builder. |
| [~StringBuilder](./~stringbuilder/)() | Destructor. |
## See Also

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.PDF for C++](../../)
