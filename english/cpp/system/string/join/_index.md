---
title: System::String::Join method
linktitle: Join
second_title: Aspose.PDF for C++ API Reference
description: 'System::String::Join method. Joins array using string as separator in C++.'
type: docs
weight: 7200
url: /cpp/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | const String\& | [String](../) to put between array elements when joining them. |
| parts | const ArrayPtr\<SharedPtr\<Object\>\>\& | [Array](../../array/) of parts to join. |

### ReturnValue

[String](../) representing joint elements.

## See Also

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | const String\& | [String](../) to put between array elements when joining them. |
| parts | const ArrayPtr\<String\>\& | [Array](../../array/) of parts to join. |
| startIndex | int | First index in array to start joining from. |
| count | int | Number of array elements to join. -1 means 'until array ends'. |

### ReturnValue

[String](../) representing joint array elements.

## See Also

* Class [String](../)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | const String\& | [String](../) to put between array elements when joining them. |
| parts | const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\& | - parts enumerable object |

### ReturnValue

[String](../) representing joint elements.

## See Also

* Class [String](../)
* Typedef [SharedPtr](../../sharedptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method


Joins array using string as separator.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


| Parameter | Type | Description |
| --- | --- | --- |
| separator | const String\& | [String](../) to put between array elements when joining them. |
| parts | const System::Details::ArrayView\<String\>\& | ArrayView of parts to join. |
| startIndex | int | First index in array to start joining from. |
| count | int | Number of array elements to join. -1 means 'until array ends'. |

### ReturnValue

[String](../) representing joint array elements.

## See Also

* Class [String](../)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
