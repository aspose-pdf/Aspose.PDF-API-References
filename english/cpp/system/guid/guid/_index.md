---
title: System::Guid::Guid constructor
linktitle: Guid
second_title: Aspose.PDF for C++ API Reference
description: 'System::Guid::Guid constructor. Constructs an object that represents a GUID consisting of all zeroes in C++.'
type: docs
weight: 100
url: /cpp/system/guid/guid/
---
## Guid::Guid() constructor


Constructs an object that represents a GUID consisting of all zeroes.

```cpp
System::Guid::Guid()
```

## See Also

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const ArrayPtr\<uint8_t\>\&) constructor


Constructs an object that represents a GUID specified as an array of unsigned 8-bit integer values.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```


| Parameter | Type | Description |
| --- | --- | --- |
| b | const ArrayPtr\<uint8_t\>\& | A byte-array containing separate bytes of the GUID |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const Guid\&) constructor


Constructs an object that represents the same GUID as the specified object.

```cpp
System::Guid::Guid(const Guid &guid)
```


| Parameter | Type | Description |
| --- | --- | --- |
| guid | const Guid\& | The [Guid](../) object to copy the GUID value from |

## See Also

* Class [Guid](../)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const String\&) constructor


Constructs an object that represents a GUID specified as a string.

```cpp
System::Guid::Guid(const String &g)
```


| Parameter | Type | Description |
| --- | --- | --- |
| g | const String\& | The string representation of a GUID to be represented by the object being constructed |

## See Also

* Class [String](../../string/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) constructor


Constructs an object that represents a GUID specified as an array view of unsigned 8-bit integer values.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```


| Parameter | Type | Description |
| --- | --- | --- |
| b | const System::Details::ArrayView\<uint8_t\>\& | A byte-array containing separate bytes of the GUID |

## See Also

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) constructor


Constructs an instance of [Guid](../) class from the specified GUID components.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | int32_t | Bits 0-31 of the GUID |
| b | int16_t | Bits 32-47 of the GUID |
| c | int16_t | Bits 48-63 of the GUID |
| d | const ArrayPtr\<uint8_t\>\& | A byte array containing bits 64-127 of the GUID |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) constructor


Constructs an instance of [Guid](../) class from the specified GUID components.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | int32_t | Bits 0-31 of the GUID |
| b | int16_t | Bits 32-47 of the GUID |
| c | int16_t | Bits 48-63 of the GUID |
| d | const System::Details::ArrayView\<uint8_t\>\& | A byte array view containing bits 64-127 of the GUID |

## See Also

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Constructs an instance of [Guid](../) class from the specified unsigned integers and bytes.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | int32_t | Bits 0-31 of the GUID |
| b | int16_t | Bits 32-47 of the GUID |
| c | int16_t | Bits 48-63 of the GUID |
| d | uint8_t | Bits 64-71 of the GUID |
| e | uint8_t | Bits 72-79 of the GUID |
| f | uint8_t | Bits 80-87 of the GUID |
| g | uint8_t | Bits 88-95 of the GUID |
| h | uint8_t | Bits 96-103 of the GUID |
| i | uint8_t | Bits 104-111 of the GUID |
| j | uint8_t | Bits 112-119 of the GUID |
| k | uint8_t | Bits 120-127 of the GUID |

## See Also

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) constructor


Constructs an instance of [Guid](../) class from the specified unsigned integers and bytes.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


| Parameter | Type | Description |
| --- | --- | --- |
| a | uint32_t | Bits 0-31 of the GUID |
| b | uint16_t | Bits 32-47 of the GUID |
| c | uint16_t | Bits 48-63 of the GUID |
| d | uint8_t | Bits 64-71 of the GUID |
| e | uint8_t | Bits 72-79 of the GUID |
| f | uint8_t | Bits 80-87 of the GUID |
| g | uint8_t | Bits 88-95 of the GUID |
| h | uint8_t | Bits 96-103 of the GUID |
| i | uint8_t | Bits 104-111 of the GUID |
| j | uint8_t | Bits 112-119 of the GUID |
| k | uint8_t | Bits 120-127 of the GUID |

## See Also

* Class [Guid](../)
* Namespace [System](../../)
* Library [Aspose.PDF for C++](../../../)
