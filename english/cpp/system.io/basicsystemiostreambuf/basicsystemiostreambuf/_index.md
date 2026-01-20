---
title: System::IO::BasicSystemIOStreamBuf::BasicSystemIOStreamBuf constructor
linktitle: BasicSystemIOStreamBuf
second_title: Aspose.PDF for C++ API Reference
description: 'System::IO::BasicSystemIOStreamBuf::BasicSystemIOStreamBuf constructor. Constructs a new instance of the BasicSystemIOStreamBuf in C++.'
type: docs
weight: 100
url: /cpp/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() constructor


Constructs a new instance of the [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## See Also

* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) constructor


Move constructor.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


| Parameter | Type | Description |
| --- | --- | --- |
| right | BasicSystemIOStreamBuf\&& | [Object](../../../system/object/) to be move |

## See Also

* Class [BasicSystemIOStreamBuf](../)
* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) constructor


Copy constructor. Deleted.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## See Also

* Class [BasicSystemIOStreamBuf](../)
* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) constructor


Constructs a new instance of the [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


| Parameter | Type | Description |
| --- | --- | --- |
| str | const SharedPtr\<Stream\>\& | Smart pointer to the stream |
| mode | SystemIOStreamWrappingMode | Wrapping mode |
| locale | const std::locale\& | [Stream](../../stream/)'s locale |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
