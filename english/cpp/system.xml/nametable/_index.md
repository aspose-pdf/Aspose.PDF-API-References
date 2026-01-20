---
title: System::Xml::NameTable class
linktitle: NameTable
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::NameTable class. Implements a single-threaded XmlNameTable in C++.'
type: docs
weight: 500
url: /cpp/system.xml/nametable/
---
## NameTable class


Implements a single-threaded [XmlNameTable](../xmlnametable/).

```cpp
class NameTable : public System::Xml::XmlNameTable
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const String\&) override | Atomizes the specified string and adds it to the [NameTable](./). |
| [Add](./add/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) override | Atomizes the specified string and adds it to the [NameTable](./). |
| [Get](./get/)(const String\&) override | Returns the atomized string with the specified value. |
| [Get](./get/)(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) override | Returns the atomized string containing the same characters as the specified range of characters in the given array. |
| [NameTable](./nametable/)() | Initializes a new instance of the [NameTable](./) class. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [XmlNameTable](../xmlnametable/)
* Namespace [System::Xml](../)
* Library [Aspose.PDF for C++](../../)
