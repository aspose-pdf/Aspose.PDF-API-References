---
title: System::SequencePosition::SequencePosition constructor
linktitle: SequencePosition
second_title: Aspose.PDF for C++ API Reference
description: 'System::SequencePosition::SequencePosition constructor. Constructs a default SequencePosition that refers to no segment in C++.'
type: docs
weight: 100
url: /cpp/system/sequenceposition/sequenceposition/
---
## SequencePosition::SequencePosition() constructor


Constructs a default [SequencePosition](../) that refers to no segment.

```cpp
System::SequencePosition::SequencePosition() noexcept
```

## See Also

* Class [SequencePosition](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SequencePosition::SequencePosition(const SharedPtr\<Object\>\&) constructor


Constructs a [SequencePosition](../) that identifies the specified segment reference.

```cpp
System::SequencePosition::SequencePosition(const SharedPtr<Object> &object)
```


| Parameter | Type | Description |
| --- | --- | --- |
| object | const SharedPtr\<Object\>\& | The reference to the segment this position points into. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [SequencePosition](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## SequencePosition::SequencePosition(const SharedPtr\<Object\>\&, int32_t) constructor


Constructs a [SequencePosition](../) that identifies the specified segment reference and an integer offset within that segment.

```cpp
System::SequencePosition::SequencePosition(const SharedPtr<Object> &object, int32_t integer)
```


| Parameter | Type | Description |
| --- | --- | --- |
| object | const SharedPtr\<Object\>\& | The reference to the segment this position points into. |
| integer | int32_t | The offset (in elements) within the referenced segment. |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [SequencePosition](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
