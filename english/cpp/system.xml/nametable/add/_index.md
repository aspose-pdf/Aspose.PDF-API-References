---
title: System::Xml::NameTable::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'System::Xml::NameTable::Add method. Atomizes the specified string and adds it to the NameTable in C++.'
type: docs
weight: 200
url: /cpp/system.xml/nametable/add/
---
## NameTable::Add(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) method


Atomizes the specified string and adds it to the [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const ArrayPtr<char16_t> &key, int32_t start, int32_t len) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const ArrayPtr\<char16_t\>\& | The character array containing the string to add. |
| start | int32_t | The zero-based index into the array specifying the first character of the string. |
| len | int32_t | The number of characters in the string. |

### ReturnValue

The atomized string or the existing string if one already exists in the [NameTable](../). If **len** is zero, [String::Empty](../../../system/string/empty/) is returned.

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
## NameTable::Add(const String\&) method


Atomizes the specified string and adds it to the [NameTable](../).

```cpp
const String & System::Xml::NameTable::Add(const String &key) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const String\& | The string to add. |

### ReturnValue

The atomized string or the existing string if it already exists in the [NameTable](../).

## See Also

* Class [String](../../../system/string/)
* Class [NameTable](../)
* Namespace [System::Xml](../../)
* Library [Aspose.PDF for C++](../../../)
