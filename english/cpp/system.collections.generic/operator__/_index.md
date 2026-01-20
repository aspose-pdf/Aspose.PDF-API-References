---
title: System::Collections::Generic::operator<< method
linktitle: operator<<
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::operator<< method. Insert data into the stream using UTF-8 encoding in C++.'
type: docs
weight: 5400
url: /cpp/system.collections.generic/operator__/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) method


Insert data into the stream using UTF-8 encoding.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::ostream\& | Output stream to insert data to. |
| pair | const KeyValuePair\<TKey, TValue\>\& | [Data](../../system.data/) to insert. |

### ReturnValue

**stream**.

## See Also

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) method


Insert data into the stream.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::wostream\& | Output stream to insert data to. |
| pair | const KeyValuePair\<TKey, TValue\>\& | [Data](../../system.data/) to insert. |

### ReturnValue

**stream**.

## See Also

* Class [KeyValuePair](../keyvaluepair/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
