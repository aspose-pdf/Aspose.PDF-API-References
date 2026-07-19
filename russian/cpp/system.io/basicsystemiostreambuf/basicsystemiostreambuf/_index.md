---
title: "System::IO::BasicSystemIOStreamBuf::BasicSystemIOStreamBuf конструктор"
linktitle: "BasicSystemIOStreamBuf"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::IO::BasicSystemIOStreamBuf::BasicSystemIOStreamBuf конструктор. Создаёт новый экземпляр BasicSystemIOStreamBuf в C++."
type: docs
weight: 100
url: /ru/cpp/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() constructor


Создаёт новый экземпляр [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## См. также

* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) constructor


Конструктор перемещения.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| right | BasicSystemIOStreamBuf\&& | [Object](../../../system/object/) для перемещения |

## См. также

* Class [BasicSystemIOStreamBuf](../)
* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) constructor


Конструктор копирования. Удалён.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## См. также

* Class [BasicSystemIOStreamBuf](../)
* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) constructor


Создаёт новый экземпляр [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| str | const SharedPtr\<Stream\>\& | Умный указатель на поток |
| режим | SystemIOStreamWrappingMode | Режим обёртывания |
| locale | const std::locale\& | Локаль [Stream](../../stream/) |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Class [BasicSystemIOStreamBuf](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
